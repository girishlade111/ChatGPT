# ChatGPT — Portfolio Website

A modern, responsive personal portfolio website built as a single static HTML file. Features a light/dark theme toggle, glassmorphism card design, and sections covering projects, skills, and contact information.

## Features

- **Single-file static site** — no build step, no dependencies; just open `index.html` in a browser
- **Light / dark theme toggle** with CSS variables and persistent theme selection
- **Responsive layout** — mobile-first design that adapts to tablets and desktops
- **Glassmorphism UI** — frosted-glass cards, soft shadows, rounded corners
- **Portfolio sections** — hero/intro, skills, projects, about, and contact
- **Smooth scroll navigation** with a sticky nav bar
- **SEO basics** — semantic HTML, meta description, descriptive title

## Tech Stack

- HTML5 (semantic markup)
- CSS3 (custom properties, flexbox/grid, media queries, backdrop-filter)
- Vanilla JavaScript (theme toggle, nav interactions) — no frameworks

## Quick Start

```bash
# Clone the repo
git clone https://github.com/girishlade111/ChatGPT.git
cd ChatGPT

# Option 1: open directly
open index.html          # or double-click it in your file manager

# Option 2: serve locally (recommended, avoids file:// quirks)
npx serve .              # then visit http://localhost:3000
```

## Project Structure

```
.
├── index.html   # The entire site — markup, styles (<style>), and scripts (<script>)
└── README.md    # This file
```

All CSS lives in a `<style>` block in `<head>`; all JavaScript lives in a `<script>` block at the end of `<body>`. To customize colors, edit the CSS variables under `:root` (light theme) and `[data-theme='dark']` (dark theme).

## Deploy Notes

- Static — deploy anywhere: **GitHub Pages**, Cloudflare Pages, Netlify, or Vercel (no build command needed, publish directory is `.`)
- GitHub Pages is enabled on the `main` branch (`/`) — live at the repo homepage URL

## Environment Variables

None — fully client-side, no secrets required.

---

**Built by [Girish Lade](https://ladestack.in)** — Web Developer, UI/UX Designer & AI Tools Creator.
