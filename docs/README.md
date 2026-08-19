# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder centralizes the program-level processes and guidance teams use to initiate, plan, execute, release, and improve work. The docs are intended to be a single source of truth for project roles, rhythms, artifacts, and escalation paths, making it easier for new team members and stakeholders to find what they need.

OctoAcme runs projects as iterative, outcome-focused efforts anchored by a small set of living artifacts. Work begins with a Project One-pager that names the problem, measurable success metrics, stakeholders, and a high-level timeline; the Decision Gate requires clear success metrics, stakeholder alignment, and resourcing before moving into planning. From there the lifecycle moves through planning (kickoff, prioritized backlog, estimates, Definition of Done), execution (sprint work tracked on a project board), release, and close with a retrospective that captures action items and promotes continuous improvement.

The day-to-day workflow is lightweight and structured. Teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done columns and follow a standard backlog-item template (title, description, acceptance criteria, estimate, owner). Sprint planning is timeboxed and pulls only items that meet the Definition of Done. The pull request process favors small, reviewable changes (target ≤ 400 lines), requires linking the related issue and acceptance criteria in the PR description, runs automated tests and linting in CI before review, and enforces at least one approval prior to merging.

Roles and communication are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and stakeholder communications; Developers implement and test; QA validates acceptance criteria; stakeholders provide inputs and approvals. The team rhythm includes daily standups, weekly delivery syncs, sprint/milestone demos, a weekly PM+PdM alignment, and monthly stakeholder updates. Quality is enforced through unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scans, and manual QA when needed. Release checklists and rollback plans are required for production deployments, and incidents are handled with an on-call notification, triage, rollback when necessary, and a blameless retrospective to capture improvements.

Quick links to the existing docs in this folder:
- OctoAcme Project Management Overview — octoacme-project-management-overview.md
- Project Initiation Guide — octoacme-project-initiation.md
- Project Planning — octoacme-project-planning.md
- Execution & Tracking — octoacme-execution-and-tracking.md
- Risk Management & Communication — octoacme-risks-and-communication.md
- Release & Deployment Guide — octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — octoacme-retrospective-and-continuous-improvement.md
- Roles and Personas — octoacme-roles-and-personas.md

How to use this README
1. Start with the Project Management Overview to understand principles and roles.
2. Use the phase-specific guides (Initiation → Planning → Execution → Release → Retrospective) as your project moves forward.
3. If you spot gaps or have suggestions, please open an issue referencing this docs folder.
