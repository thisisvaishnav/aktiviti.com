<div align="center">

<img src="icon.png" alt="Aktiviti App Icon" width="128" height="128" />

# aktiviti.com

**The official marketing website, interactive feature hub, and documentation for [Aktiviti](https://github.com/thisisvaishnav/aktiviti).**

[![Website](https://img.shields.io/badge/website-aktiviti.com-007AFF.svg)](https://aktiviti.com)
[![macOS](https://img.shields.io/badge/macOS-15%2B%20Sequoia-black.svg?logo=apple)](https://github.com/thisisvaishnav/aktiviti)
[![Deployed on Vercel](https://img.shields.io/badge/deployed%20on-Vercel-black.svg?logo=vercel)](https://vercel.com)

</div>

---

## 🌐 Overview

This repository contains the production web application and documentation guides for **[Aktiviti](https://github.com/thisisvaishnav/aktiviti)** — the lightweight, developer-first macOS activity monitor and system telemetry dashboard.

### Key Highlights
- **Apple HIG Design System**: Native Apple styling with frosted-glass navigation (`backdrop-filter: blur(20px)`), SF Pro typography, and automatic dark/light theme persistence.
- **Interactive Component Previews**: Live client widgets showcasing the menu bar dropdown, audio mixer sliders, and AI agent monitoring.
- **Vercel-Ready Architecture**: Zero-configuration static edge deployment with clean URLs, optimized routing, and aggressive asset caching.
- **40+ Dedicated Pages**: Full feature walkthroughs, side-by-side technical comparisons, and Mac optimization benchmarks.

---

## 📁 Repository Structure

```text
aktiviti.com/
├── _astro/                     # Production CSS stylesheets & interactive JS bundles
├── apps/                       # High-resolution application icons for process cards
├── changelog/                  # Release changelogs & version screenshots (v1.7 – v1.9)
├── download/                   # App installer landing page
├── features/                   # Deep-dive feature showcases
│   ├── agents/                 # AI Coding Agents telemetry (Claude Code, Cursor)
│   ├── ai-usage-limits/        # Rate limits & session tracking
│   ├── alerts/                 # Threshold & background alert monitor
│   ├── battery/                # Battery health & power draw diagnostics
│   ├── cli/                    # aktiviti CLI documentation
│   ├── dev-servers-and-ports/  # Port Doctor & socket manager
│   ├── docker/                 # Container resource inspection
│   ├── gpu-and-neural-engine/  # Apple Silicon GPU & ANE metrics
│   ├── mcp-server/             # Model Context Protocol integration
│   ├── menu-bar/               # Menu bar telemetry configuration
│   ├── process-inspector/      # Code signature & entitlements inspector
│   └── volume-mixer/           # Per-app audio & microphone control
├── guides/                     # macOS optimization guides & benchmarks
├── love/                       # Testimonial avatars and user feedback
├── more/                       # Ecosystem product icons (SVG/PNG)
├── pricing/                    # Pricing tiers & license options
├── roadmap/                    # Upcoming milestones
├── vs/                         # Competitor comparisons
│   ├── activity-monitor/       # Aktiviti vs Apple Activity Monitor
│   ├── cleanmymac/             # Aktiviti vs CleanMyMac
│   ├── istat-menus/            # Aktiviti vs iStat Menus
│   └── stats/                  # Aktiviti vs Stats
├── icon.png                    # Brand app icon (512x512)
├── index.html                  # Main landing page
├── package.json                # Project scripts & metadata
└── vercel.json                 # Vercel deployment & routing configuration
```

---

## 🚀 Deploying to Vercel

The site is configured for 1-click deployment on [Vercel](https://vercel.com):

1. Push or import this repository into your Vercel account.
2. In the project creation modal, select **Other** for the framework preset (static files at root).
3. The included [`vercel.json`](vercel.json) automatically sets up clean URLs (e.g. `/features`, `/pricing`, `/roadmap`) and HTTP cache-control headers.
4. Click **Deploy**.

---

## 💻 Local Preview

To preview the website locally on any machine:

```bash
# Using Python built-in server:
python3 -m http.server 3000

# Or with Node / npx:
npx serve .
```

Open `http://localhost:3000` in your browser.

---

## 🔗 Main Application Repository

The native Swift macOS application source code is maintained at:
**[github.com/thisisvaishnav/aktiviti](https://github.com/thisisvaishnav/aktiviti)**
