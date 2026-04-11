# Project State

**Project:** Workshop Certificate App — Template Edition
**Milestone:** 1.0 — Template MVP
**Status:** Planning complete — ready to execute

## Current Phase
Phase 01: Scaffold & Config System — Not Started

## Phase Status

| # | Phase | Status | Plans |
|---|-------|--------|-------|
| 01 | Scaffold & Config System | Not Started | 5 plans |
| 02 | Certificate Rendering | Not Started | 4 plans |
| 03 | Interactive Features | Not Started | 3 plans |
| 04 | Search & SPA Routing | Not Started | 3 plans |
| 05 | SEO & Structured Data | Not Started | 4 plans |
| 06 | Contribution & Polish | Not Started | 3 plans |

## Completed Phases
(none yet)

## Accumulated Context

### Decisions
- Stack: Single `index.html`, pure HTML/CSS/Vanilla JS (ES6+), no build pipeline
- CDN libs: qrcode.js v1.0.0, html2pdf.js v0.10.1, Google Fonts (Playfair Display + Lato)
- Hosting: GitHub Pages (static, zero backend)
- Certificate ID convention: email sanitization — `jane.doe@gmail.com` → `jane-doe-at-gmail-com`
- Clean URL paths (e.g. `/john-doe`) explicitly out of scope — conflicts with OG scraper requirement
- v2 deferral: CI validator, certificate gallery, multiple workshops per person, opaque IDs, sitemap

### Todos
(none yet)

### Blockers
(none)

## Last Updated
April 11, 2026 — Roadmap created
