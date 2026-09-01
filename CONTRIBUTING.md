# Contributing to MinSpec

Thank you for your interest in MinSpec.

MinSpec is currently in founder-controlled incubation.

During this phase, MinSpec is not accepting unsolicited external contributors, code pull requests, documentation pull requests, package submissions, recipe submissions, workflow changes, dependency changes, or unsolicited AI-generated contribution patches. Work the maintainer directs through explicitly granted accounts is governed by the Maintainer-Directed Agent Work section below.

MinSpec is public for visibility, review, reproducible feedback, and source-of-truth development. Public visibility does not imply public governance, public write access, or an open contribution process.

---

## Current Contribution Posture

MinSpec is public before it is publicly governable.

The project may accept:

- questions
- reproducible bug reports
- security reports through the published security process
- design feedback
- documentation clarity suggestions
- evidence that an existing claim, package boundary, or workflow is wrong

The project does not currently accept:

- unsolicited code pull requests
- unsolicited documentation pull requests
- third-party package implementations
- copied code snippets
- generated code from outside approved source paths
- dependency changes
- GitHub Actions or workflow changes
- broad doctrine rewrites
- unsolicited AI-agent-generated mutation patches (maintainer-directed agent work has its own lane, below)
- pull requests that imply contributor authority

Pull requests are enabled but restricted to collaborators only. Only users with repository write, maintain, or admin access may open pull requests.

Collaborator PR access is an operational mechanism for trusted maintainers and approved collaborators. It is not a public contribution path.

Opening an issue or providing feedback does not grant contribution authority, source authority, maintainer status, or approval to submit code changes.

---

## Source Authority

Only official MinSpec repositories and explicitly approved source paths may provide trusted project material.

Security review is not a substitute for source authority.

A change must enter through an approved source path before it can be considered for inclusion.

---

## Maintainer-Directed Agent Work

Added 2026-09-01 by maintainer decision.

Work produced by AI agents operating under the maintainer's explicit direction is maintainer work, not an external contribution. This section exists so the incubation rules above cannot be misread as barring the maintainer's own development process.

A change enters through this lane only when all of the following hold:

- the maintainer directed the work and named its scope
- it is submitted by an account the maintainer explicitly granted repository access (collaborator PR access remains an operational mechanism, not a public contribution path)
- it arrives as a reviewable pull request, opened as a draft, with the change and its reason stated in the body
- every commit names its origin in trailers: `Source:` for where the content came from, and `Co-Authored-By:` naming the specific agent that did the work
- the maintainer reviews and ratifies; nothing merges on an agent's own authority

Under this lane, agents may prepare, commit, and submit changes. Authority does not move: agents still do not decide project direction, approve, merge, release, tag, publish, or change repository settings. Access grants operation, not authority; ratification remains the maintainer's act.

Unsolicited agent-generated patches from outside this lane remain unaccepted, exactly as stated above.

---

## AI-Assisted Work

AI-assisted analysis may be useful as review input.

AI agents, GitHub Apps, bots, automation, Dependabot, Copilot agents, browser agents, and external tools are not maintainers and do not gain source authority from collaborator-only PR settings.

AI-generated code, documentation patches, workflow changes, package changes, or repository mutations are not accepted from unapproved external sources during incubation.

The MinSpec rule remains:

> AI reasons. MinSpec commands mutate.
