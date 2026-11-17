# Software Engineering — Group 8 Project

Course project repository for **Software Engineering, Group 8**.

## Overview

This repository holds the source code, documentation, and design artefacts for our
group project. It is organised so every member can work in parallel without
blocking each other, and so the lecturer/reviewer can follow the history.

> Replace the sections below with your actual project details once the team has
> agreed on the topic.

## Team

| Name | Role | GitHub |
| --- | --- | --- |
| _TBD_ | Project Lead | `@username` |
| _TBD_ | Backend | `@username` |
| _TBD_ | Frontend | `@username` |
| _TBD_ | QA / Testing | `@username` |
| _TBD_ | Documentation | `@username` |

## Tech stack

- _Language / runtime:_ TBD
- _Framework:_ TBD
- _Database:_ TBD
- _Tooling:_ Git, GitHub Actions

## Getting started

```bash
# 1. Clone
git clone https://github.com/<owner>/software-engineering-group-8.git
cd software-engineering-group-8

# 2. Install dependencies (update for the chosen stack)
# npm install   |   pip install -r requirements.txt   |   etc.

# 3. Run the project
# npm run dev   |   python main.py   |   etc.
```

## Repository layout

```
.
├── docs/          Project documentation, diagrams, meeting notes
├── src/           Application source code
├── tests/         Unit and integration tests
└── README.md
```

## Branching strategy

| Branch | Purpose | Rules |
| --- | --- | --- |
| `main` | Stable, demo-ready code | Protected. Merges only from `dev` via pull request with at least 1 approval. |
| `dev` | Integration branch for the team | All feature work merges here first. Must stay buildable. |

Feature workflow:

```bash
git checkout dev
git pull origin dev
git checkout -b feature/<short-name>
# ... commit your work ...
git push -u origin feature/<short-name>
# open a pull request into dev
```

Branch naming:

- `feature/<name>` — new functionality
- `fix/<name>` — bug fixes
- `docs/<name>` — documentation only

## Commit messages

Use short, imperative summaries, optionally with a scope:

```
feat(auth): add email login
fix(api): handle empty response
docs(readme): add setup steps
```

## Working agreements

1. Pull `dev` before starting any new work.
2. Open a pull request for every change — no direct pushes to `main`.
3. At least one teammate reviews before merge.
4. Keep pull requests small and focused.
5. Record decisions and meeting notes in `docs/`.

## Deliverables checklist

- [ ] Requirements specification
- [ ] System design / architecture diagrams
- [ ] Implementation
- [ ] Test plan and test results
- [ ] User documentation
- [ ] Final presentation

## Contact

Group 8 — _add course code, lecturer, and team contact here._
