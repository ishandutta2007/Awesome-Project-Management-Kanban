# Awesome-Project-Management-Kanban

# Top Project Management & Kanban Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Self-Hosted Boards, Agile Workflows & Real-Time Collaboration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Project Management & Kanban**. These tools help teams visualize work, limit work-in-progress, and move tasks through stages — from simple personal boards to full agile project management suites with sprint planning, Gantt charts, and time tracking.

**Examples** include Trello, Asana, Monday.com, Jira, ClickUp, Vikunja, WeKan, Planka, Kanboard, and Focalboard (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Trello-style boards, and transparent data ownership — ideal for teams prioritizing privacy, avoiding per-seat SaaS pricing, and running project management they fully control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Trello](https://trello.com/)**  
  **The reference Kanban tool** that popularized boards, lists, and cards. Simple drag-and-drop interface with Power-Ups for extensions. Free tier with unlimited cards and 10 boards per workspace; paid plans from **$5/user/month** (annual) . **Best for teams wanting the simplest possible Kanban** with minimal setup.

- **[Asana](https://asana.com/)**  
  Team work management with list, board, timeline, and calendar views. Strong for cross-team coordination and project portfolios. Free tier for up to 10 users; paid plans scale per-user.

- **[Monday.com](https://monday.com/)**  
  Work OS with customizable boards, automations, and dashboards. Broader than pure Kanban — focused on workflow and project tracking with database-like structures.

- **[Jira Software](https://www.atlassian.com/software/jira)**  
  **The standard for agile software teams** with Scrum and Kanban boards, sprint planning, backlog management, and issue tracking. Deep integration with the Atlassian ecosystem (Confluence, Bitbucket). Free tier for up to 10 users.

- **[ClickUp](https://clickup.com/)**  
  All-in-one productivity platform with boards, lists, docs, goals, and time tracking. Free tier with unlimited users and storage limits.

- **[Notion Projects](https://www.notion.com/)**  
  Project management within the Notion workspace — boards, timelines, and databases alongside docs and wikis. Free for personal use; team plans per-user.

- **[Wrike](https://www.wrike.com/)**  
  Enterprise work management with Kanban boards, Gantt charts, resource management, and proofing.

- **[Kanbanchi](https://www.kanbanchi.com/)**  
  Kanban board and Gantt chart app integrated with Google Workspace.

- **[MeisterTask](https://www.meistertask.com/)**  
  Visual task management with Kanban boards, automations, and integrations.

- **[Kanbanize (Businessmap)](https://kanbanize.com/)**  
  Enterprise Kanban platform with portfolio management, analytics, and workflow automation.

## Open-Source GitHub Projects

- **[Vikunja](https://github.com/go-vikunja/vikunja)**  
  **The most actively maintained open-source project management tool** — AGPL-3.0 licensed, **5,600+ GitHub stars** . **Four views of the same tasks**: List, Gantt, Table, and Kanban — switch between them based on workflow . **Reminders, repeating tasks, and importers for Trello and Todoist** . **Single binary or Docker deployment** with releases for Linux, macOS, and Windows plus deb, rpm, apk, and Arch packages . **Native OIDC support** and REST API . **Official Android and iOS apps** (described as alpha — treat as companion to web) . **Admin panel, audit logs, and time tracking** planned for paid Vikunja Pro . **Best for teams wanting a modern, actively developed all-in-one task manager** with Kanban plus Gantt and list views.

- **[WeKan](https://github.com/wekan/wekan)**  
  **The closest open-source Trello clone** — MIT licensed, **21,000+ GitHub stars**, in development since 2014 with several releases a week . **Real-time boards, lists, and cards** with swimlanes, WIP limits, and webhooks . **Importers for Trello, Jira, Asana, and CSV** . **No telemetry** — the project states this plainly . **LDAP, OAuth2, OIDC, and SAML** support for authentication . **Requires MongoDB** and at least **1 GB RAM minimum, 4 GB recommended for production** . **Trade-offs**: **no undo** — maintainers ask for daily database backups and only support the newest release; disk-full events can corrupt the MongoDB database . **Best for teams wanting the closest Trello experience** on their own server with active development.

- **[Planka](https://github.com/plankanban/planka)**  
  **The elegant, minimal self-hosted Kanban** — **fair-code licensed** (PLANKA Community License, not OSI-approved) . **Real-time collaboration** with projects, boards, lists, and cards; markdown descriptions; attachments; comments; custom fields; stopwatch and due dates . **Notifications through 100+ providers** and a documented REST API . **Two-factor authentication** included . **Community edition is free to self-host** with your database and backups . **PLANKA Pro** adds mobile support, calendar/timeline/map views, templates, guest roles, SSO (OIDC), and PDF export — **one-way upgrade, no downgrade back to Community** . **Trello JSON import works but is lossy** — users and attachments do not import, only one checklist per card, and Trello's default export stops at 1,000 actions without warning . **Best for teams wanting a clean, modern Kanban UI** with real-time collaboration and a free self-hosted tier.

- **[Kanboard](https://github.com/kanboard/kanboard)**  
  **The minimal, finished option** — MIT licensed, **9,900+ GitHub stars**, **maintenance mode** . **Small PHP app** with WIP limits, a search language, automatic actions, and plugins on SQLite, MySQL, or PostgreSQL . **LDAP/Active Directory and OAuth2** login . **Automatic actions** change assignees, colors, and categories when events happen . **Trade-offs**: **in maintenance mode** — author is not building major new features; interface is intentionally plain and desktop-oriented . **Best for teams wanting something tiny that just works** with minimal resource requirements.

- **[Focalboard](https://github.com/mattermost-community/focalboard)**  
  **The self-hosted Kanban and project management tool** — **community maintenance mode** as of 2026; new feature development concentrated on **Mattermost Boards** . **Kanban, Table, and Gallery views** of the same underlying data . **Custom properties** (dates, selects, text) for specialized metadata . **Robust REST API** — stable endpoints for legacy integrations . **Single lightweight Docker container** on port 8000 . **Limitations**: **no commits since June 2025** per one source ; **no native real-time WebSockets in standalone mode** (unlike the Mattermost plugin version) ; **potential security debt** in the long term . **Best for historical project archival or personal/homelab boards** where API stability takes precedence over new features — **not for mission-critical production requiring active security patching** .

### Additional Strong Open-Source Options

- **Taiga** — Open-source agile project management with Kanban and Scrum boards, sprint planning, and issue tracking. AGPL-3.0 licensed, Python/Django stack. Top integrations include GitHub, GitLab, Slack, and Zapier . Best for agile development teams.
- **Nextcloud Deck** — Kanban integrated with the Nextcloud ecosystem. Free for unlimited users. Seamless file sharing, comments, labels, and real-time updates. Best for teams already using Nextcloud apps .
- **Leantime** — Open-source project management combining design thinking, lean methodology, and Agile practices. Designed for neurodiverse teams. Best for startup-minded teams wanting a full project manager .
- **4ga Boards** — Straightforward real-time Kanban with dark mode, collapsible todo lists, and multitasking tools. MIT licensed, Node.js/Docker/K8s stack .
- **AppFlowy** — Open-source Notion alternative with Kanban boards, databases, and to-do lists. AGPL-3.0 licensed, Rust/Dart stack .
- **Nullboard** — Single-page minimalist Kanban board. Compact, highly readable, and quick to use .
- **OpenProject** — Comprehensive open-source project management with Gantt charts, agile boards, and team collaboration. GPLv3 licensed, Ruby on Rails stack . More complex than Kanban-only tools.

**Frameworks for building custom systems**: Combine **Vikunja** for modern all-in-one task management with Kanban plus Gantt and list views, **WeKan** for the closest Trello clone with active development and importers, **Planka** for an elegant minimal Kanban with real-time collaboration and a free self-hosted tier, **Kanboard** for a tiny finished board with minimal resource requirements, and **Taiga** for agile teams needing sprint planning alongside Kanban — to build a project management stack tailored to your workflow, team size, and infrastructure constraints.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Project management tools differ significantly in maintenance status, licensing, and feature scope. **Focalboard's standalone project is in community maintenance mode** with no commits since June 2025 — not suitable for mission-critical production requiring active security patching . **Planka's Community License is fair-code, not OSI-approved** — free for internal use but commercial licensing required to resell access . **WeKan has no undo** — maintainers require daily database backups, and disk-full events can corrupt MongoDB . **Kanboard is in maintenance mode** — no major new features . **Vikunja is the most actively maintained option** with the broadest view support .
- Self-hosted open-source solutions require proper database backups, regular security updates, and monitoring of resource usage — especially WeKan's MongoDB and Planka's PostgreSQL.

---

**Made for project managers, engineering teams, and organizations building self-hosted Kanban and project management workflows.**
Let's make project management and Kanban more open, self-hosted, and workflow-flexible.
