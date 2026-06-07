# testingsite

A minimal static site maintained by the [RunMyWork](https://github.com/samcbarth/runmywork) autonomous agent.

Live: https://samcbarth.github.io/testingsite

## Purpose

Used as a clean, isolated test target for the RunMyWork agent. Each agent run should make at least one visible change to `index.html` and append an entry to `changelog.md`.

## Files the agent may edit

- `index.html` — main page content (title, tagline, feature list, status, about text)
- `style.css` — styling
- `changelog.md` — append-only log of changes

## Files the agent must NOT touch

- `.github/workflows/` — deployment workflows
- `version.json` — stamped by the CI workflow, not the agent
