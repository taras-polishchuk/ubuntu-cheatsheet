# Ubuntu CLI Cheat Sheet

> An interactive, searchable reference for Ubuntu/Debian command-line essentials. Covers 18 categories with 150+ commands — sidebar navigation, instant search, dark/light theme, and one-click clipboard copy. Zero dependencies, pure HTML/CSS/JS.

**Live demo:** https://taras-polishchuk.github.io/ubuntu-cheatsheet/

---

## Features

- **18 categorized sections** covering day-to-day and advanced CLI tasks
- **Instant search** — filters commands and descriptions in real time as you type
- **Sidebar navigation** — jump directly to any section; active section highlights on scroll (Intersection Observer)
- **One-click copy** — click any command block to copy it to the clipboard
- **Dark / Light theme** — toggle persisted to `localStorage`
- **Fully responsive** — sidebar collapses on mobile, readable on any screen size
- **Zero JS frameworks** — pure HTML, CSS, and Vanilla JS

## Sections covered

| # | Section | # | Section |
|---|---------|---|---------|
| 1 | System Info | 10 | Text Processing |
| 2 | Monitoring | 11 | APT Package Manager |
| 3 | Services (systemd) | 12 | Snap Packages |
| 4 | Cron Jobs | 13 | Users & Groups |
| 5 | File Management | 14 | Networking |
| 6 | Navigation | 15 | Firewall (UFW) |
| 7 | Permissions & Ownership | 16 | SSH |
| 8 | Search & Find | 17 | LXD Containers |
| 9 | Archives & Compression | 18 | Ubuntu Pro |

## Tech stack

| Layer | Detail |
|-------|--------|
| Markup | Semantic HTML5 |
| Styles | CSS custom properties, responsive layout, light/dark tokens |
| Logic | Vanilla JavaScript — search filtering, Intersection Observer, clipboard API |
| Fonts | Inter + JetBrains Mono (Google Fonts) |

## Project structure

```
ubuntu-cheatsheet/
└── index.html    # entire app — styles + markup + JS in one file
```

## How to run

Open `index.html` directly in any modern browser. No build step needed.

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

## How to use

1. **Browse** — click any section in the left sidebar to jump directly to it
2. **Search** — type in the search bar to filter commands across all sections
3. **Copy** — click any code block to copy the command to your clipboard
4. **Theme** — toggle dark/light mode via the button in the top-right corner

## Motivation

Built as a personal quick-reference while learning Linux system administration. The goal was a fast, offline-friendly cheat sheet that loads instantly and never needs an internet connection.
