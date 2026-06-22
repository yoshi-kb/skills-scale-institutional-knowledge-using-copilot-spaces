# OctoAcme Project Management Docs

## Purpose

This documentation set is the central reference for how OctoAcme plans, executes, and continuously improves its projects. It is intended for all team members — new and existing — including Project Managers, Product Managers, Developers, and QA/Testing.

Use these docs to understand our processes, find the right artifact templates, and navigate governance expectations consistently across teams.

---

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that moves work through five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Each project begins with a lightweight One-pager capturing the problem statement, SMART objectives, success metrics, and stakeholder alignment before a formal go/no-go decision is made. Once approved, the team holds a kickoff, builds a prioritized backlog with clear acceptance criteria, defines a Definition of Done (DoD), and maps out release milestones and dependencies. Risks and cross-team dependencies are captured in a Risk Register and reviewed continuously throughout the project lifecycle.

Day-to-day execution is driven by a steady team rhythm — 15-minute daily standups, weekly delivery syncs, and end-of-sprint demos. Work flows through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with a strong emphasis on small, reviewable pull requests (≤400 lines where possible) that include issue links, pass automated CI checks, and require at least one peer approval before merging. Blockers are escalated through a three-level path: team-level triage → PM escalation to Product Lead → Sponsor-level escalation for business-impacting issues.

OctoAcme recognizes four core **personas**: the **Project Manager (PM)**, who owns schedules, risk, and communication; the **Product Manager (PdM)**, who defines outcomes and prioritizes the backlog; **Developers**, who implement and test features while contributing to design and estimation; and **QA/Testing**, who validate acceptance criteria. Communication is structured around weekly PM–PdM syncs, twice-weekly standups, monthly stakeholder updates, and a standardized Weekly Status Template covering progress, next steps, risks/blockers, and decisions needed. Stakeholder updates are anchored to a single source of truth such as a project README or release doc.

Quality and continuous improvement are embedded throughout the process. The engineering workflow requires unit, integration, and end-to-end smoke tests, along with security scanning in CI and manual QA for feature acceptance. Releases are categorized as Patch, Minor, or Major, each requiring passing CI, completed release notes, a rollback plan, and post-deploy verification before stakeholder announcement. After every sprint, release, or significant milestone, the team holds a **retrospective** — timeboxed to 45–75 minutes — to surface what went well, identify improvements, and commit to 2–3 actionable items with clear owners and due dates, ensuring a culture of measurable, iterative improvement.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle stages |
| [Project Initiation](octoacme-project-initiation.md) | How to validate and authorize new work, align stakeholders, and create an initial plan |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog, release plan, and milestone map |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery, team rhythm, PR workflow, quality standards, and escalation paths |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running cadence, and tracking improvement action items |
| [Roles & Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for all core project personas |

---

## How to Use

### Suggested reading order for new team members

1. [Project Management Overview](octoacme-project-management-overview.md) — Start here for the big picture
2. [Roles & Personas](octoacme-roles-and-personas.md) — Understand your role and others on the team
3. [Project Initiation](octoacme-project-initiation.md) — Learn how projects get started
4. [Project Planning](octoacme-project-planning.md) — See how work gets organized and scheduled
5. [Execution & Tracking](octoacme-execution-and-tracking.md) — Understand day-to-day delivery practices
6. [Risk Management & Communication](octoacme-risks-and-communication.md) — Know how risks and stakeholder updates are managed
7. [Release & Deployment](octoacme-release-and-deployment.md) — Review how features are safely shipped to production
8. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Learn how the team captures and acts on learnings

### Keeping docs current

- If you identify a gap, outdated content, or a process improvement, open an issue using the **[Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.
- Propose changes via pull request referencing the relevant issue.
- Ensure updates align with existing process docs and have been reviewed with stakeholders where needed.
