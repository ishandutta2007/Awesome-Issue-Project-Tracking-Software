# Awesome-Issue-Project-Tracking-Software

## Top Issue & Project Tracking Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Agile Issue Tracking, Sprint Planning & Self-Hosted Project Management*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Issue & Project Tracking Software**. These tools enable software teams to manage backlogs, track bugs, plan sprints, and visualize work on boards—turning chaotic development workflows into predictable, measurable delivery.



**Examples** include Jira, Linear, Asana, Monday.com, ClickUp, GitHub Issues, Wrike, Shortcut, Bugzilla, and Redmine (the category leaders).



**Open-source emphasis**: Issue & Project Tracking is a domain where open-source tooling is **genuinely mature, with clear leaders for different team sizes and methodologies**. **Plane** is the standout modern option—AGPL-3.0 Community Edition, actively developed (v1.4.0 in August 2026), with issues, cycles (sprints), modules, and a spec-workflow that product teams recognize from Linear or Jira . **OpenProject** is the most complete classic PM suite—GPLv3, self-hosted with unlimited users, Gantt charts, agile boards, and budget management . **Taiga** excels at proper Scrum mechanics for teams that actually run sprints . **Redmine** remains the battle-tested veteran with two decades of ecosystem and plugins for almost anything—but its interface is dated, and modern conveniences come from third-party plugins maintained by volunteers . The critical caveat: **Focalboard's standalone version has been unmaintained since 2024** , and **Apache Bloodhound is effectively frozen** . Choose based on whether you need a modern Jira replacement (Plane), a complete classic PM suite (OpenProject), or a proven plugin ecosystem (Redmine).



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Jira](https://www.atlassian.com/software/jira)**  

  The enterprise standard for issue and project tracking; Scrum/Kanban boards, backlogs, roadmaps, and deep integration with the Atlassian ecosystem. Powerful but often criticized for configuration complexity.



- **[Linear](https://linear.app/)**  

  The modern, keyboard-first issue tracker beloved by startups; fast, opinionated, with cycles, projects, and a clean interface. Positioned as the anti-Jira for product teams.



- **[Asana](https://asana.com/)**  

  Work management platform with portfolio views, goals tracking, and timeline dependencies for cross-team project visibility and accountability.



- **[Monday.com](https://monday.com/)**  

  Work OS with customizable boards, dashboards, and automation for tracking projects and team workload across departments.



- **[ClickUp](https://clickup.com/)**  

  All-in-one productivity platform with tasks, docs, goals, and multiple views (List, Board, Gantt, Calendar) for teams seeking to consolidate tools.



- **[GitHub Issues](https://github.com/features/issues)**  

  Native issue tracking within GitHub; issues, labels, milestones, and project boards tightly integrated with repositories and pull requests.



- **[Wrike](https://www.wrike.com/)**  

  Enterprise work management with Kanban boards, Gantt charts, and resource management; supports custom workflows.



- **[Shortcut](https://shortcut.com/)**  

  Project management for software teams; stories, epics, milestones, iterations, and a clean workflow focused on developer productivity.



- **[Bugzilla](https://www.bugzilla.org/)**  

  Long-standing open-source bug tracker from Mozilla; powerful query system and mature permissions, but dated UI and no Agile/kanban features.



- **[Redmine](https://www.redmine.org/)**  

  Classic open-source issue tracking and project management; supports multiple projects, Gantt charts, calendars, and flexible role-based access.



## Open-Source GitHub Projects



### Modern Jira/Linear Alternatives (Plane, Huly)



- **[Plane](https://github.com/makeplane/plane)**  

  The **most mature open-source Jira/Linear alternative** (AGPL-3.0 Community Edition, ~60k GitHub stars) . Features: **issues, cycles (sprints), modules, and a spec-workflow** that product teams recognize from Linear or Jira; multiple views including Kanban and Gantt . **v1.4.0** (August 2026) added lightweight REST API endpoints for list views, a new translation architecture, webhook workspace_slug, and accessibility improvements . **Caveats**: the project moves fast—upgrades are regular and occasionally breaking; if you need stability over motion, wait a release cycle before committing . **Best for modern product teams** wanting a fast, opinionated tracker with kanban boards.



- **[Huly](https://github.com/hcengineering/platform)**  

  Open-source **all-in-one project management platform** positioned as a self-hostable alternative to Linear, Jira, Slack, and Notion (EPL-2.0, ~28k GitHub stars) . Combines project tracking, team chat, virtual office, and collaborative docs in a single workspace. **Best for teams wanting an integrated workspace** rather than a focused issue tracker—each module is less deep than dedicated tools.



### Full Classic PM Suites (OpenProject, Redmine)



- **[OpenProject](https://github.com/opf/openproject)**  

  The **most complete classic open-source PM suite** (GPLv3, ~16k GitHub stars) . Features: **Gantt charts** with drag-and-drop dependencies, **Agile boards** (Kanban/Scrum), time tracking, cost reporting, budgets, and portfolio views . **Free self-hosted with unlimited users** . **Caveats**: heavier than Plane or Taiga; the Gantt chart is functional but less polished than dedicated tools . **Best for teams needing traditional project management** with detailed planning and reporting—especially public sector and organizations needing budgets and cost tracking.



- **[Redmine](https://github.com/redmine/redmine)**  

  The **battle-tested open-source issue tracker** (GPLv2, free) with two decades of development and an enormous plugin ecosystem—there is a plugin for almost anything . Features: issue tracking, subprojects, roles and permissions, time tracking, wikis, forums, Gantt charts, and calendar views . **Caveats**: the interface is dated; Kanban boards, OIDC login, and most modern conveniences come from **third-party plugins pinned to versions and maintained by volunteers** . **Best for teams comfortable assembling and maintaining a plugin stack**—zero license cost, complete control, and a mature ecosystem in exchange for less modern UX.



### Agile & Scrum-Focused (Taiga, Tuleap)



- **[Taiga](https://github.com/kaleidos-ventures/taiga)**  

  Open-source **Agile project management** (MPL-2.0, free to self-host) organized around **Scrum ceremonies**—sprints, story points, burndown charts, epics, and both Kanban and Scrum boards . **The methodology is baked in**: if your team runs Scrum properly rather than aspirationally, it supports that better than most alternatives . **Caveats**: if you do not run Scrum, much of it is overhead; reporting and automation depth may not match a heavily customized Jira . **Best for teams committed to Scrum** who want sprint mechanics as first-class features.



- **[Tuleap](https://github.com/Enalean/tuleap)**  

  Open-source **application lifecycle management platform** (GPL) for software development teams; features ticketing/bug tracking, Agile planning, document management, version control, CI, and customizable workflows; available on-premises or cloud . **Best for organizations wanting a unified ALM platform** with agile planning and DevOps integration—but it is a broader platform than a simple issue tracker.



### Additional Strong Open-Source Options



- **Leantime** — Open-source project management combining design thinking and Agile practices; kanban boards, Gantt charts, goals, and time tracking. Free self-hosted version limited to 150 tasks; Pro hosted at $10/user/month . **Best for startups** wanting an integrated PM + strategy tool.

- **Vikunja** — Lightweight task management with List, Kanban, Gantt, and Table views; single binary or Docker. **Best for individuals and small teams** wanting Trello-like boards plus Gantt—not enterprise governance .

- **Kanboard** — Minimal open-source kanban board (MIT, ~9.9k stars) with WIP limits and automatic actions; in maintenance mode but stable for simple boards .

- **Focalboard** — **CAUTION**: standalone version unmaintained since 2024; no commits since June 2025 . Only viable for Mattermost users via its Boards plugin.

- **Phorge** — Community-maintained fork of Phabricator; provides code review, task management, and project communication with ongoing updates . **Best for teams already invested in the Phabricator workflow**.

- **MantisBT** — Simple PHP/MySQL bug tracker; straightforward interface for small to mid-sized teams .



**Frameworks for building custom systems**: For a **modern Jira/Linear replacement with kanban**, Plane (accepting fast releases) . For a **complete classic PM suite with Gantt and budgets**, OpenProject . For **Scrum-first teams**, Taiga . For **maximum plugin flexibility with dated UX**, Redmine . For **lightweight kanban**, Kanboard or Vikunja . **Avoid Focalboard standalone**—it is unmaintained . No open-source project matches Jira's **enterprise configuration depth** or Linear's **polished UX** out of the box—choose based on whether you need depth (OpenProject, Redmine) or speed (Plane, Taiga).



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Issue and project tracking platforms handling engineering data must comply with organizational security policies; **self-hosted solutions place full responsibility for security patches, backups, and uptime on the operator**.

- **Open-source issue tracking is mature but requires matching tool to team**—Plane provides a modern Jira alternative , OpenProject provides a complete classic PM suite , and Taiga provides Scrum mechanics . **Focalboard standalone is unmaintained since 2024** and **Apache Bloodhound is effectively frozen**—do not deploy for new projects. **Redmine's interface is dated** and modern features come from volunteer-maintained plugins. Choose based on whether you need modern UX (Plane), classic PM depth (OpenProject), or Scrum methodology (Taiga).

- Verify license terms for commercial use; Plane Community uses AGPL-3.0 , OpenProject uses GPLv3 , and Taiga uses MPL-2.0 .



---



**Made for engineering managers, product teams, and developers choosing their issue tracking stack.**  

Let's make issue and project tracking more open, but with clear eyes about the maintenance status and methodology fit that define each tool's real value.
