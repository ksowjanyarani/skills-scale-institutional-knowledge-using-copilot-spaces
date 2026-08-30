# OctoAcme Project Management Documentation

## Overview

OctoAcme runs projects with a customer-first, iterative approach focused on delivering small, testable increments and measuring impact. Projects follow a clear lifecycle—Initiation, Planning, Execution, Release, and Retrospective—backed by role clarity and data-informed decisions so teams can align on outcomes, reduce risk, and iterate based on evidence.

## Key workflows

Workflows center on lightweight planning and disciplined execution. Teams use a visual project board (Backlog → Ready → In Progress → In Review → QA → Done), a prioritized backlog with defined acceptance criteria, and a pull request workflow that encourages small PRs with linked issues, CI and security checks, and at least one approval before merging. Planning activities include kickoff, estimation, and Definition of Done; execution emphasizes automated tests, CI, and a cadence of demos and syncs.

## Roles & personas

Roles and personas ensure clear ownership: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and risks, Developers implement and test, and QA validates acceptance criteria and quality gates. These role definitions help teams delegate responsibility, surface dependencies early, and keep communication channels focused and effective.

## Quality assurance & communication

Quality practices and communication are built into every phase. CI, unit and integration tests, security scanning, and smoke tests guard releases; manual QA is used for feature acceptance when required. Regular rituals—daily standups, a weekly delivery sync, sprint demos, and scheduled stakeholder updates—are reinforced by a simple risk register and escalation path. Retrospectives capture actionable improvements and feed them back into the backlog to continuously improve the process.

## Quick Links by Project Phase

- Initiation
  - [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and decide go/no-go for planning
- Planning
  - [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments and create prioritized backlogs with acceptance criteria
- Execution & Tracking
  - [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, team rhythm, quality standards, and blocker escalation
- Release & Deployment
  - [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize release processes and reduce deployment risk
- Retrospectives & Continuous Improvement
  - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

## Core Resources

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, core roles, and key artifacts
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of Project Managers, Product Managers, Developers, and QA roles
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies

## For new team members

Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a quick introduction to our approach, then follow the phase-specific guides relevant to your work. Look for acceptance criteria on backlog items and the Definition of Done when preparing work for a sprint.

## Contributing to process documentation

To suggest updates or add new content, use the Add Content to Project Management Process Docs issue template:
../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
