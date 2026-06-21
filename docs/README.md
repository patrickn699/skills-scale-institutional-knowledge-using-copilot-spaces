# OctoAcme Project Management Process Docs

This folder contains OctoAcme's program and project management process documents. The README indexes each document and provides a short overview of our approach so team members and contributors can quickly find the guidance they need.

## Overview

OctoAcme follows a lightweight, iterative lifecycle that begins with a focused initiation phase and proceeds through planning, execution, release, and continuous improvement. Initiation centers on validating the business need and measurable success metrics (one‑pager), identifying stakeholders, and confirming go/no‑go to planning. Planning turns approved initiatives into prioritized, shippable work with estimates, a Definition of Done, and a simple risk register to capture impact, likelihood, and mitigations.

Execution emphasizes predictable workflows and team cadence. Work is tracked on a project board with columns: Backlog → Ready → In Progress → In Review → QA → Done. Pull requests should be small, reference related issues and acceptance criteria, and pass automated CI and lint checks before review. Team rhythms include daily standups, weekly delivery syncs, and demos at the end of each sprint or milestone. Blockers follow a tiered escalation path (team → PM → Product Lead → Sponsor) to ensure timely resolution of business‑impacting issues.

Roles, communication, and quality practices are explicit. Project Managers coordinate delivery, timelines, and risks while Product Managers own problem definition, prioritization, and success metrics. Developers deliver and test features, QA validates acceptance criteria and runs manual checks when appropriate, and stakeholders provide inputs and approvals. Communication uses templated status updates (progress, next steps, risks, asks), a single source of truth (project README/release doc), and a cadence of PM+PdM alignment meetings, delivery check‑ins, and monthly stakeholder updates. Quality is enforced via unit and integration tests, end‑to‑end smoke tests for critical flows, security scans in CI, and pre‑release staging verifications; releases include rollback plans and post‑deploy checks.

## Documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

Notes:
- Keep this README concise and use the linked documents for full details.
- When proposing changes to process docs, use the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template so updates are tracked and reviewed.
