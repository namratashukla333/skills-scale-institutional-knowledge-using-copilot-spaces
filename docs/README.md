# OctoAcme Project Management Processes

This README provides a quick summary of OctoAcme's project management processes and direct links to detailed process documents stored in this folder. Use this as the canonical entry point for process-related guidance, onboarding, and Copilot Spaces context.

## Overview

OctoAcme operates on a **structured lifecycle approach** that moves projects through five distinct phases: Initiation, Planning, Execution, Release, and Close & Retrospective. The process is grounded in customer-first principles with emphasis on iterative delivery and clear ownership.

**Initiation** validates business need and stakeholder alignment by creating a lightweight Project One-pager that captures the problem statement, success metrics, and resource requirements. Once approved, projects advance to **Planning**, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a Release Plan.

**Execution and tracking** are coordinated through regular team rhythms and transparent project boards. The team conducts daily standups (15 minutes), weekly delivery syncs, and sprint/milestone demos to maintain alignment and surface blockers early. Pull Requests follow a lightweight convention (≤400 lines preferred) with linked issues and acceptance criteria, supported by automated CI/CD testing and linting.

**Risk management and communication** are central to OctoAcme's execution model. The team maintains a Risk Register tracking impact, likelihood, owner, and mitigation plans, with status reviewed at weekly syncs. A tiered escalation path ensures issues are surfaced and resolved efficiently. Stakeholder communication follows a regular cadence using templated formats to keep visibility consistent.

After each sprint, release, or significant milestone, OctoAcme conducts **retrospectives** to capture learnings and drive continuous improvement. Releases follow a pre-release checklist, deploy to staging with smoke tests, run post-deploy verifications, and maintain a rollback/incident playbook to minimize production risk. This cycle of plan → execute → release → reflect creates a feedback loop that steadily improves both product quality and team capability.

## Process Documents

### Core References
- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, principles, core roles, and lifecycle overview.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of Project Manager, Product Manager, Developers, QA, and Stakeholder responsibilities.

### Lifecycle Phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into an actionable plan and backlog for delivery.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance, team rhythm, workflows, quality assurance, and reporting metrics.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies; stakeholder communication templates.

## Quick Reference

| Phase | Key Activities | Artifacts | Success Criteria |
|-------|---|---|---|
| **Initiation** | Validate need, align stakeholders | One-pager, stakeholder list, timeline | Problem & metrics clear, stakeholders aligned |
| **Planning** | Break work into increments, estimate | Backlog, acceptance criteria, DoD, release plan | Backlog prioritized, dependencies mapped |
| **Execution** | Build, test, review | PRs, project board, risk register | Team rhythm established, quality gates passed |
| **Release** | Deploy to production | Release notes, deployment checklist, rollback plan | Deployment successful, smoke tests pass |
| **Retrospective** | Capture learnings, improve | Action items, metrics, next steps | Team alignment on improvements, action owners clear |

## How to Use These Docs

1. **New team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to understand the framework.
2. **Project kickoff**: Use [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) to establish your project.
3. **Active delivery**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day guidance.
4. **Release preparation**: Use [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release and deployment checklists.
5. **Learning & improvement**: Conduct retrospectives using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
6. **Copilot Spaces context**: Add this README to your Copilot Space for AI-assisted guidance aligned with OctoAcme practices.

## Process Improvement

Have feedback or want to improve these docs? Use the [Add/Update Content to Process Docs issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest updates or new content.
