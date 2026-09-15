<p align="center">
  <img src="docs/assets/logo.png" alt="Ryuk Reminder" width="128"/>
</p>

<h1 align="center">Ryuk Reminder</h1>

<p align="center">
  <strong>Offline-first Android reminder app</strong><br/>
  Reminders, birthdays, countdown timer, and alarms that fire even when the phone is locked — no account, no cloud, no ads.
</p>

<p align="center">
  <a href="https://github.com/heema2/RyukReminder/releases/latest"><img src="https://img.shields.io/badge/Download-Latest%20APK-E2554A?style=for-the-badge&logo=android&logoColor=white" alt="Download APK"/></a>
  <a href="https://github.com/heema2/Ryuk-Dev"><img src="https://img.shields.io/badge/Hub-Ryuk--Dev-1A1A1A?style=for-the-badge&logo=github" alt="Ryuk-Dev"/></a>
  <a href="https://discord.com/users/198843596558958601"><img src="https://img.shields.io/badge/Discord-Ryuk-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android%208%2B-3DDC84?logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Version-2.0.1-E2554A" alt="Version"/>
  <img src="https://img.shields.io/badge/Languages-EN%20%7C%20AR-2D2D2D" alt="Languages"/>
  <img src="https://img.shields.io/badge/Offline-No%20internet%20permission-2D2D2D" alt="Offline"/>
  <img src="https://img.shields.io/badge/Code-Proprietary-lightgrey" alt="Proprietary"/>
</p>

---

> **Repository notice**  
> Public product page + official APK only. **Source code is not open source.**  
> Developer hub: **[Ryuk-Dev](https://github.com/heema2/Ryuk-Dev)**

---

## What is Ryuk Reminder?

Ryuk Reminder is a **Kotlin / Jetpack Compose** Android app for people who want alarms that actually fire — without an account, cloud, or ads.

| | Feature |
|---|---|
| Reminders | One-time and recurring (daily, weekly, monthly, yearly, custom) |
| Birthdays | Eve alert (09:00) + **midnight** birthday alert (00:00 local) with Happy Birthday sound |
| Languages | **English** and **Arabic** (RTL) — switch anytime in Settings |
| Organize | Categories, priorities, search, and filters |
| Alerts | Sound, vibration, **Complete** / **Snooze**, and screen wake on lock screen |
| Timer | Countdown timer with presets, Pause / Stop live notification, **Silence** when done |
| Simulation | Preview reminder, timer, and birthday notifications from Settings |
| Themes | Light, dark, and system |
| Privacy | Works **fully offline** (no internet permission) |

---

## What's new in v2.0.1

### Critical fix
- **Birthday day notification now fires at local midnight (00:00:00)** — not 9:00 AM
- Eve (“1 day left…”) alert still fires at **09:00** the day before

### Localization
- Full **English + Arabic** UI and notifications
- Language picker in **Settings** (English default; العربية available)
- Proper RTL layout when Arabic is selected

### Design & branding
- Modernized theme, cards, and visual polish (light + dark)
- Refreshed launcher icon and splash screen
- Clearer birthday status labels (Today / Tomorrow / days left)

### Reliability
- Safer delivery when multiple birthdays share the same midnight
- Birthday triggers recomputed on launch / reboot / timezone change

### Recent versions

| Version | Highlights |
|---------|------------|
| **2.0.1** | Midnight birthday alerts, EN/AR + RTL, UI refresh |
| **1.6.2** | Editable birthday date fields + validation |
| **1.6.1** | Simulation screen for notification previews |
| **1.6.0** | Birthdays tab, yearly scheduling, celebration sound |
| **1.5.6** | Lock-screen wake, full-screen alert UI |

---

## Look & feel

<p align="center">
  <img src="docs/assets/home.png" alt="Home" width="280"/>
  &nbsp;
  <img src="docs/assets/editor.png" alt="Editor" width="280"/>
</p>

---

## Download

**[Latest APK (v2.0.1)](https://github.com/heema2/RyukReminder/releases/latest/download/RyukReminder-v2.0.1-release.apk)**  
All versions: **[Releases](https://github.com/heema2/RyukReminder/releases)**

### Install on your phone

1. Copy the APK to your phone.
2. Open the file and tap **Install** (allow *Install unknown apps* if asked).
3. Open **Ryuk Reminder** and allow:
   - **Notifications**
   - **Alarms & reminders** (exact alarms)
   - **Battery optimization → Don't optimize**

Package: `com.ryuk.reminder` · Android 8.0+ (API 26)

---

## Contact & copyright

Built by **Heema Star (Ryuk)** under **Ryuk Developments**.

| | |
|---|---|
| Main hub | [github.com/heema2/Ryuk-Dev](https://github.com/heema2/Ryuk-Dev) |
| GitHub | [github.com/heema2](https://github.com/heema2) |
| Discord | [discord.com/users/198843596558958601](https://discord.com/users/198843596558958601) |

© 2026 Ryuk. All rights reserved. Ryuk Reminder and the Ryuk brand, logo, and visual identity are property of Ryuk.  
Unauthorized copying, redistribution, or rebranding is not permitted.
