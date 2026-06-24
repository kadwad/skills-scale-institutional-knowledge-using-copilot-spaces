# OctoAcme Project Management Docs

Welcome to OctoAcme's project management process documentation. This README aggregates our core process guides and provides a quick overview of how we run projects across the organization.

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle designed to balance stakeholder alignment with iterative delivery: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. 

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### The Project Lifecycle

**Initiation & Validation**
Projects begin with lightweight validation through a Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. The one-pager captures the problem statement, objective, success metrics, primary stakeholders, suggested timeline, quick risks, and proposed team structure. Once stakeholders align and success metrics are clear, teams move forward to planning.

**Planning & Preparation**
During planning, work is broken into shippable increments with clear acceptance criteria, estimates, and risk mitigation strategies. Teams create a prioritized backlog, define a Definition of Done, identify dependencies and integration points, and establish a release plan and milestone map. This structure ensures clarity around outcomes before significant resources are committed.

**Execution & Quality**
Execution emphasizes small pull requests (≤400 lines when possible), automated testing in CI, and transparent progress tracking using a project board with columns: Backlog, Ready, In Progress, In Review, QA, Done. Daily standups focus on progress and blockers; weekly syncs keep stakeholders informed. Quality is enforced through unit tests, integration tests, end-to-end smoke tests before release, and security scanning in CI.

**Release & Rollback**
Releases follow a standardized checklist that includes passing CI/security scans, drafted release notes, and a documented rollback plan. Teams deploy to staging first, run smoke tests, then deploy to production through an automated pipeline when possible. Post-deploy verifications and stakeholder announcements complete the process.

**Learning & Continuous Improvement**
After each sprint, release, or milestone, teams conduct retrospectives to capture learnings and generate action items. These retrospectives emphasize candor and psychological safety. Action items are tracked in the project backlog with clear owners and timelines, and their impact is measured in weekly syncs. This formal commitment to learning enables teams to experiment safely and improve both processes and product quality over time.

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design, and contribute to planning and risk identification
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Communication Cadence

- **Daily standups** (15 min): Focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync**: Align on strategy and review risks
- **Twice-weekly delivery standups**: Keep execution team synchronized
- **Monthly stakeholder updates**: Maintain visibility across stakeholders
- **Ad-hoc escalations**: Risk and blocker escalation follows a three-level path (team → PM → Product Lead → Sponsor)

---

## Process Documents

Each document below provides detailed guidance for a specific phase or aspect of project execution:

### Overview & Strategy
- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, roles, key artifacts, and lifecycle

### Project Phases
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Project initiation guide, one-pager template, and decision gate criteria
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Planning activities, backlog and sprint planning, risk management, and planning checklist
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Day-to-day execution, PR workflow, quality standards, metrics, and blocker escalation
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, and rollback playbook
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, tracking improvements, and continuous improvement culture

### Supporting Practices
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk register management, risk lifecycle, stakeholder communication templates, and escalation paths
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Detailed role descriptions, responsibilities, goals, and typical communication for Developers, Product Managers, and Project Managers

---

## How to Use These Docs

1. **For new team members**: Start with this README and [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) to understand OctoAcme's approach
2. **For project kickoff**: Reference [octoacme-project-initiation.md](./octoacme-project-initiation.md) and [octoacme-project-planning.md](./octoacme-project-planning.md)
3. **During execution**: Use [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) and [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)
4. **Before release**: Consult [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
5. **After milestones**: Run retrospectives using [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)

## Keeping Documentation Current

- Update this README when adding new process documents or making significant changes to existing ones
- Link this README from the repository root README and any onboarding guides
- Encourage team feedback on process improvements; use the [Add Content to Project Management Process Docs issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates

---

**Last updated**: June 2026  
**Maintainer**: OctoAcme Project Management Team
