# CLAUDE.md — portfolio-2026

## What this repo is
A personal digital business card / portfolio site for Aleksander Szewczak.
Single-page HTML + Tailwind CSS (CDN). Deployed via GitHub Actions to GitHub Pages.

**Live URL:** https://olekturbo.github.io/portfolio-2026/

## Key files
- `index.html` — the entire site (one file, no build step)
- `.github/workflows/deploy.yml` — GitHub Actions Pages deployment
- `skills.md` — source of truth for Aleksander's real skills and experience

## Content rules
- **Always** consult `skills.md` before editing any copy, bio, project descriptions, or tech tags
- Do not invent technologies, project names, or experience that isn't in `skills.md`
- Persona name: **Aleksander Szewczak** · initials: **AS** · email: **aleks.szewczak@gmail.com**

## Workflow
- Propose all content/copy changes before editing
- Commit everything in a single commit at the end (don't commit after each small change)
- Push triggers automatic Pages deployment — no manual steps needed

## Design tokens
| Token | Value |
|---|---|
| Background | `slate-900` |
| Accent | `emerald-400` |
| Font | Inter (Google Fonts) |
| Animations | CSS `reveal` class via IntersectionObserver |
