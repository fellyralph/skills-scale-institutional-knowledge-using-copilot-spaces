# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation hub. This folder contains guides, templates, and checklists for running successful projects at OctoAcme.

## Overview

OctoAcme runs projects through a clear lifecycle: initiation (one-pager, stakeholder alignment, go/no‑go), planning (kickoff, prioritized backlog, estimates, Definition of Done), execution (small, iterative deliveries managed on a project board), release (pre-release checks, smoke tests, automated pipelines), and close (retrospectives and action tracking). Key artifacts include the Project One‑pager, roadmap/release plan, backlog items with acceptance criteria, a risk register, and release notes.

Work is managed on a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined pull request workflow that encourages small PRs, links to issues and acceptance criteria, and requires CI (tests, linting, security scans) and at least one approval before merging. Planning breaks initiatives into shippable increments with checkpoints for dependencies and mitigation; backlog items follow a template that captures description, acceptance criteria, priority, estimate, and owner. The release process distinguishes patch/minor/major releases and includes a rollback/incident playbook and explicit pre‑release requirements.

Roles and responsibilities are explicitly defined: Product Managers own the problem, success metrics, and prioritization; Project Managers coordinate delivery, risks, timelines and stakeholder communications; Developers implement and test; QA focuses on validation and acceptance criteria. Communication cadence centers on short daily standups for progress and blockers, weekly delivery syncs and PM+PdM alignments, demo/review at the end of sprints or milestones, and monthly stakeholder updates. There are templates for weekly status and incident communications, and an escalation path from team → PM → Product Lead → Sponsor (with a separate path for security incidents).

Quality and continuous improvement are built into the process: unit and integration tests are required for new logic, end‑to‑end smoke tests are run for critical flows, CI enforces tests and security scans, and manual QA is used when needed for acceptance. Retrospectives capture what went well, improvement opportunities, and 2–3 priority action items which are tracked back into the backlog with owners and due dates. Risk management is lightweight and pragmatic—maintain a risk register (impact, likelihood, owner, mitigation), review it weekly, and escalate according to the documented paths when issues threaten delivery.

## Quick Navigation

- Foundation
  - [Project Management Overview](./octoacme-project-management-overview.md)
  - [Roles & Personas](./octoacme-roles-and-personas.md)
- Project Phases
  - Initiation: [Project Initiation Guide](./octoacme-project-initiation.md)
  - Planning: [Project Planning](./octoacme-project-planning.md)
  - Execution & Tracking: [Execution & Tracking](./octoacme-execution-and-tracking.md)
  - Risks & Communication: [Risk Management & Communication](./octoacme-risks-and-communication.md)
  - Release & Deployment: [Release & Deployment Guide](./octoacme-release-and-deployment.md)
  - Closure & Improvement: [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## When to use each document

- Initiation: Project Initiation Guide — Start here when validating new ideas and preparing the one‑pager.
- Planning: Project Planning — Use when breaking approved initiatives into backlog items and release plans.
- Execution: Execution & Tracking — Daily delivery, PR workflow, and team rhythm.
- Risk/Communication: Risk Management & Communication — For identifying, tracking, and escalating risks.
- Release: Release & Deployment Guide — For production rollouts and rollback procedures.
- Closure: Retrospective & Continuous Improvement — After sprints, releases, or incidents to capture learnings.

## Contributing

These docs are living artifacts. If you identify gaps or want to add new processes, please create an issue using the "Add Content to Project Management Process Docs" template.
