# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management knowledge base. This collection of documents provides comprehensive guidance on how OctoAcme runs projects to deliver product features, services, and integrations consistently and effectively.

## Quick Start

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Ready to plan?** See the [Project Planning](./octoacme-project-planning.md) guide
- **In execution?** Reference the [Execution & Tracking](./octoacme-execution-and-tracking.md) guide
- **Need to release?** Check the [Release & Deployment](./octoacme-release-and-deployment.md) guide

## Core Principles

OctoAcme projects are built on five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

All OctoAcme projects follow a five-stage lifecycle:

1. **Initiation** → Define the problem and validate business need
2. **Planning** → Break work into shippable increments and identify risks
3. **Execution** → Build, test, and review with clear team rhythm
4. **Release** → Deploy features and verify quality
5. **Close & Retrospective** → Capture learnings and continuous improvements

## Project Management Overview

OctoAcme's project management approach is a structured, cross-functional lifecycle that moves work from idea to delivery and reflection. It begins with project initiation, where the team validates the business need, defines outcomes and success metrics, identifies stakeholders, and creates a lightweight one-pager to decide whether the work should proceed into planning. The project management approach emphasizes clear ownership, measurable goals, and a standard set of artifacts such as a charter, risk list, stakeholder plan, and roadmap.

Once a project is approved, the planning phase turns the concept into an actionable backlog. Teams hold kickoff meetings, prioritize work, estimate effort, document acceptance criteria and definition of done, and map dependencies, milestones, and release timing. The planning process also incorporates risk management by tracking issues in a risk register, identifying cross-team dependencies, and ensuring work is aligned with team capacity.

Communication is a central part of the operating model. OctoAcme uses a mix of regular team rhythms and stakeholder-facing updates, including daily standups, weekly delivery or PM syncs, milestone demos, and ad hoc escalation when blockers emerge. The process uses a single source of truth for status, such as a project README or release document, ensuring everyone receives consistent updates and decision-making remains transparent.

Quality assurance is built into both delivery and release workflows. Teams are expected to write unit and integration tests, conduct smoke testing for critical flows, run security scans, and require PR review and approvals before merging work. Releases are gated by acceptance criteria, CI validation, rollback planning, and post-deploy verification to reduce production risk. After each sprint or milestone, OctoAcme encourages retrospectives to capture what worked, what needs improvement, and which actions should be tracked to closure, creating a continuous improvement loop that connects delivery discipline, communication, and learning into a consistent project operating model.

## Complete Documentation

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Framework overview, roles, artifacts, and lifecycle |
| [Project Initiation](./octoacme-project-initiation.md) | Initial steps to validate, authorize, and kickoff work |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into actionable backlogs and milestones |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day workflows, quality, and blocker escalation |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk registers, dependencies, and stakeholder updates |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Standardized release types, checklists, and rollback |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting to improvements |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Detailed descriptions of key team roles |

## Core Roles

OctoAcme projects depend on clear role definitions and cross-functional collaboration:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications. Ensures projects stay on track and stakeholders remain aligned.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision and customer value delivery.
- **Developers**: Implement features, collaborate on design and testability. Write tests and maintain code quality.
- **QA/Testing**: Validate quality and acceptance criteria. Conduct user acceptance testing and identify defects.
- **Stakeholders**: Provide inputs, approvals, and business context to guide project decisions.

For detailed role descriptions and responsibilities, see [Roles and Personas](./octoacme-roles-and-personas.md).

## Communication Cadence

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync** — Alignment on priorities, risks, and decisions
- **Twice-weekly delivery team standups** — Team coordination and progress updates
- **Sprint/Milestone demos** — Show progress and gather feedback
- **Monthly stakeholder updates** — Status reporting and visibility
- **Ad-hoc escalations** — For blockers and business-impacting issues

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items
- Weekly status updates
- Release notes and deployment verification logs

## Questions or Feedback?

These docs are living artifacts. If you have questions, suggestions, or identify gaps, please:

1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Submit a pull request with improvements
3. Reach out to the Project Management team for clarification

---

**Last Updated:** October 2026
