# Penn Embodied AI — Website

The official website for **Penn Embodied AI**, a student organization at the University of Pennsylvania building robots that perceive, learn, and act in the physical world.

🔗 **Live:** https://pennhumanoid.github.io

---

## Overview

A single-page static site — no framework and no build step. The entire site is one `index.html` file with inline CSS, JavaScript, and SVG. The only external dependency is Google Fonts; the logo and favicon are embedded directly in the file, so it works anywhere with zero setup.

## Repository structure

```
.
├── index.html     # the entire website
└── README.md      # this file
```

## Editing locally

Open `index.html` in any browser to preview it — that's the whole workflow. All styles live in the `<style>` block in the `<head>`, and all behavior is in the `<script>` block at the bottom.

### Placeholders to fill in

Search the file for `TODO` to find each one:

- **Discord invite** link (Join section)
- **Contact email** — currently `hello@pennembodiedai.org`
- **Social profile URLs** — LinkedIn, Instagram, X, YouTube, GitHub (footer)
- **Meeting day & time** — currently "TBD" (Join section)
- **Domain** in the `og:` meta tags, if a custom domain is purchased

## Deploying & updating

Hosted on **GitHub Pages** from the `main` branch root. Updates publish automatically: edit `index.html`, commit to `main`, and the live site refreshes in about 30 seconds.

To re-enable Pages from scratch: **Settings → Pages → Source: Deploy from a branch → `main` → `/ (root)`**.

## Brand

| Token        | Value                                   |
|--------------|-----------------------------------------|
| Penn Red     | `#990000` (PMS 201)                     |
| Penn Blue    | `#011F5B` (PMS 288)                     |
| Display font | Space Grotesk                           |
| Body font    | IBM Plex Sans                           |
| Mono font    | IBM Plex Mono                           |

The mark is a sharp-cornered "E" with square nodes capping the bar ends. Source logo files (avatar, lockup, inverted, transparent, favicon) are kept separately as SVG masters.

## Penn brand compliance

This site follows Penn's [Student Brand Guidelines](https://universitylife.upenn.edu/student-brand-guidelines/):

- Uses only the approved Penn Red and Penn Blue.
- Does **not** use the Penn shield, seal, official wordmark/typography, Athletic "Split P," or "UPenn."
- Identifies the group as **"A Student Organization at the University of Pennsylvania"** (footer).

> **Note:** The club logo itself must go through Penn's annual logo-approval process via [Penn Clubs](https://pennclubs.com/), facilitated by the Office of Student Affairs (OSA). This is required before the logo is considered officially approved.

## License

© Penn Embodied AI. Site content and the Penn Embodied AI mark are property of the organization.
