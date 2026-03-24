# OctoAcme Project Management Docs

Welcome! This folder contains OctoAcme's project management process documentation, which standardizes how we plan, execute, release, and continuously improve our projects.

## Overview of OctoAcme Project Management Processes

**Lifecycle and Workflows**

OctoAcme follows a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. During initiation, teams validate business needs and create a lightweight Project One-pager that outlines the problem statement, objectives, success metrics, stakeholders, and initial timeline. Once approved, the planning phase breaks work into shippable increments with clear acceptance criteria, prioritized backlogs, and defined dependencies. Execution relies on a project board (using GitHub Projects) with columns for Backlog, Ready, In Progress, In Review, QA, and Done. The team follows a pull request workflow emphasizing small PRs (≤ 400 lines), automated CI testing, and at least one approval before merging. After deployment, OctoAcme conducts retrospectives to capture learnings and convert them into actionable improvements.

**Core Roles and Communication**

OctoAcme operates with four primary roles working in concert: **Project Managers (PMs)** coordinate delivery, manage schedules, risks, and communications; **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success; **Developers** implement features, collaborate on design, and participate in quality assurance; and **QA/Testing teams** validate quality and acceptance criteria. The organization emphasizes clear ownership—each project has a named PM and PdM—and uses a regular communication cadence including twice-weekly standups, weekly syncs between PM and PdM, monthly stakeholder updates, and ad-hoc escalations when needed. Risk escalation follows three levels: team-level triage in daily standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

**Quality Assurance and Delivery Standards**

Quality is embedded throughout OctoAcme's delivery process through multiple checkpoints: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI pipelines. Teams define a clear **Definition of Done (DoD)** during planning and require manual QA for feature acceptance when needed. Release management is standardized with pre-release requirements including passing CI/security scans, drafted release notes, and documented rollback plans. The team tracks velocity and burndown metrics, monitors success indicators from the Project One-pager, and uses dashboards for key signals like errors, latency, and usage.

**Guiding Principles**

All OctoAcme processes are grounded in five core principles: **Customer-first** prioritization of value and usability, **Iterative delivery** of small testable increments, **Clear ownership** with named roles and responsibilities, **Data-informed decisions** based on measurement and evidence, and a culture of **Psychological safety** that encourages feedback and learning. This comprehensive approach enables consistent, repeatable project execution while accelerating onboarding and reducing single-person dependency risks across the organization.

## Process Documents

- [**Project Management Overview**](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, core roles, and key artifacts.
- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Steps to validate business needs, align stakeholders, and create a Project One-pager.
- [**Project Planning**](./octoacme-project-planning.md) — How to break work into shippable increments, define acceptance criteria, and create a release plan.
- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Day-to-day guidance for managing progress, pull requests, quality assurance, and metrics.
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — How to identify, assess, and mitigate risks; plus communication templates and escalation paths.
- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardized process for releasing to production, including pre-release checks and rollback procedures.
- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Running effective retrospectives and tracking action items for improvement.
- [**Roles and Personas**](./octoacme-roles-and-personas.md) — Detailed descriptions of Project Managers, Product Managers, Developers, and QA/Testing roles.

Each document is versioned and reviewed to ensure best practices and alignment with OctoAcme's evolving needs.

---

**How to Use These Docs**

- **Onboarding**: Start with [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's approach.
- **Starting a Project**: Follow the [Project Initiation Guide](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) workflows.
- **Running a Project**: Use [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) for day-to-day guidance.
- **Preparing to Release**: Consult [Release & Deployment Guide](./octoacme-release-and-deployment.md) before shipping to production.
- **Improving**: Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive enhancements.
