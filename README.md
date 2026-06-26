<div align="center">

# WorkoutPro

**A premium, offline-first fitness tracking app built for serious athletes.**

[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org)
[![Capacitor](https://img.shields.io/badge/Capacitor-8-119EFF?style=flat-square&logo=capacitor)](https://capacitorjs.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

</div>

---

## Overview

WorkoutPro is a fully featured, mobile-first fitness tracking application that works entirely offline. Built with Next.js and Capacitor, it delivers a native-app experience on both web and mobile — no account, no backend, no internet required.

Designed with the aesthetics of Apple Fitness and Linear in mind, WorkoutPro combines a premium dark UI with powerful training tools: live workout execution, load progression tracking, body measurements, and a full XP-based gamification system.

---

## Features

### Workout Management
- Create unlimited custom workouts with names, colors, and icons
- Organize exercises by muscle group (14 categories)
- Add notes and observations to each exercise
- Edit and reorder exercises within a workout

### Live Workout Execution
- Real-time workout timer with pause and resume
- Set-by-set tracking: weight, reps, and RPE (Rate of Perceived Exertion)
- Automatic volume calculation (`Weight × Reps × Sets`)
- Configurable rest timer with presets: 30s, 45s, 60s, 90s, 120s, 180s
- Background notifications when the rest period ends

### Statistics & Analytics
- Weekly, monthly, and yearly views
- Volume bar charts by period
- Weekly frequency area charts (last 8 weeks)
- Annual activity heatmap (GitHub-style, 52-week view)
- All-time totals: workouts, volume, training time

### Body Measurements
- Track 9 metrics: weight, body fat %, lean mass, chest, arm, forearm, waist, hip, thigh, and calf
- Weight and body composition evolution charts

### Gamification
- XP earned per completed set, workout, personal record, and streak
- Progressive level system from 1 to 100 with a 1.4× XP curve per level
- 10 level titles: Beginner → Legend → Iron God
- 14 unlockable achievements tied to volume, streaks, and workouts
- Real-time achievement toast notifications

### Dashboard
- Time-based greeting
- Active workout quick-access banner
- Level card with XP progress bar
- Weekly stats snapshot
- Recent activity feed

### Data & Privacy
- 100% offline — all data stored locally via IndexedDB
- Zero backend dependencies, zero accounts
- JSON export and import for full backup and restore

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 16 (static export) |
| Language | TypeScript 5 |
| Styling | Tailwind CSS 4 |
| State | Zustand 5 |
| Database | Dexie 4 (IndexedDB) |
| Animations | Framer Motion 12 |
| Charts | Recharts 3 |
| Icons | Lucide React |
| Mobile | Capacitor 8 (Android + iOS) |
| Notifications | @capacitor/local-notifications |
| Date utilities | date-fns 4 |

---

## Screenshots

> The screenshots below showcase the main screens of WorkoutPro across the app experience.

<!-- Replace the placeholders below with actual screenshots -->

| Dashboard | Workouts |
|:---:|:---:|
| ![Dashboard](docs/screenshots/dashboard.png) | ![Workouts](docs/screenshots/workouts.png) |

| Live Execution | Rest Timer |
|:---:|:---:|
| ![Execute](docs/screenshots/execute.png) | ![Timer](docs/screenshots/timer.png) |

| Statistics | Achievements |
|:---:|:---:|
| ![Stats](docs/screenshots/stats.png) | ![Achievements](docs/screenshots/achievements.png) |

| Profile | Body Measurements |
|:---:|:---:|
| ![Profile](docs/screenshots/profile.png) | ![Measurements](docs/screenshots/measurements.png) |

---

## Coming Soon to the Play Store

WorkoutPro is actively being prepared for its official launch on the **Google Play Store**.

A native Android build is already in progress via Capacitor. The app will be available as a free download, offering the same premium experience already available on the web — with full native notification support, home screen integration, and offline-first performance.

> **Stay tuned.** The Play Store release is coming soon.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
  <sub>Built with passion for athletes who take training seriously.</sub>
</div>
