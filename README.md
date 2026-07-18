# CapturePro

**Capture your screen like a pro.**

CapturePro is a free, local-first screen capture app for Windows and macOS. Take screenshots, record your screen, annotate, run OCR, and share — all on your machine. No account required.

**Website:** [capturepro.dev](https://capturepro.dev)  
**Support:** [support@capturepro.dev](mailto:support@capturepro.dev)

---

## Download

| Platform | Requirements | Download |
|----------|--------------|----------|
| **Windows** | Windows 10 or later | [CapturePro-Setup.exe](https://capturepro.dev/downloads/CapturePro-Setup.exe) |
| **macOS** | macOS 13 Ventura or later | [CapturePro.dmg](https://capturepro.dev/downloads/CapturePro.dmg) |

You can also grab the latest installers from [GitHub Releases](https://github.com/harshkolte01/capturepro/releases/latest).

---

## Features

- **Quick Access** — Save, copy, or drag-and-drop captures straight into Slack, Figma, Explorer, or Finder
- **Annotate** — Arrows, shapes, text, blur, and spotlight tools in the built-in editor
- **Screen recording** — Record as MP4 with pause, resume, and restart controls
- **Scrolling capture** — Capture long pages, chat histories, and large code blocks
- **Effects** — Padding, corner radius, drop shadows, and custom backgrounds before export
- **OCR** — Copy text from screenshots with on-device text recognition
- **Pin screenshots** — Keep references visible above other windows
- **Crop** — Rule-of-thirds grid, non-destructive, works on video
- **Video editor** — Trim timeline, thumbnail strip, export with effects
- **GIF export** — Optimized GIF output from recordings
- **Color picker** — Pick any pixel color from your screen
- **Hide desktop icons** — Clean captures on both platforms

---

## Keyboard shortcuts

### Windows

| Action | Shortcut |
|--------|----------|
| Capture region | `Ctrl + Shift + 4` |
| Capture screen | `Ctrl + Shift + 3` |
| Capture window | `Ctrl + Shift + 5` |
| Record screen | `Ctrl + Shift + 2` |
| OCR text scan | `Ctrl + Shift + O` |
| Color picker | `Ctrl + Shift + C` |
| Open editor | `Ctrl + Shift + E` |
| Pin screenshot | `Ctrl + Shift + P` |

### macOS

| Action | Shortcut |
|--------|----------|
| Capture region | `⌘ + Shift + 4` |
| Capture screen | `⌘ + Shift + 3` |
| Capture window | `⌘ + Shift + 5` |
| Record screen | `⌘ + Shift + 2` |
| OCR text scan | `⌘ + Shift + O` |
| Color picker | `⌘ + Shift + C` |
| Open editor | `⌘ + Shift + E` |
| Pin screenshot | `⌘ + Shift + P` |

---

## Privacy

CapturePro is local-first. Screenshots, recordings, and annotations stay on your computer unless you choose to share or export them. The app does not require an account and does not upload your capture content.

When checking for updates, the app may contact our servers to see if a newer version is available. No capture content is sent during update checks.

Read the full policy at [capturepro.dev/privacy](https://capturepro.dev/privacy).

---

## Changelog

See [capturepro.dev/changelog](https://capturepro.dev/changelog) for release notes.

### v1.0.0 — July 2026

- Initial public release for Windows and macOS
- Screenshots, screen recording, and scrolling capture
- Built-in editor with annotations, effects, and OCR
- Pin screenshots and Quick Access overlay

---

## Repository

This public repository contains the **CapturePro desktop application** for Windows and macOS, including release binaries.

The marketing website lives separately at [capturepro.dev](https://capturepro.dev).

---

## Releasing (maintainers)

Releases are published manually via GitHub Releases.

1. Tag the release commit (e.g. `v1.0.0`)
2. Create a new [GitHub Release](https://github.com/harshkolte01/capturepro/releases/new) from that tag
3. Upload installers with these exact asset names:
   - `CapturePro-Setup.exe`
   - `CapturePro.dmg`
4. Write release notes and mark the release as **Latest**

The website download links at `capturepro.dev/downloads/*` redirect to the latest GitHub release assets, so users always get the newest build without updating the site.

After publishing, update the changelog at [capturepro.dev/changelog](https://capturepro.dev/changelog).