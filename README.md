<div align="center">

<img src="assets/app-icon.png" alt="Sticky Notes App Icon" width="140" style="border-radius: 28px;" />

# Sticky Notes

### A Beautiful, Freeform Digital Canvas for Your Thoughts

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white&style=for-the-badge)](https://github.com/)
[![Built With](https://img.shields.io/badge/Built_With-Next.js_16-000000?logo=nextdotjs&logoColor=white&style=for-the-badge)](https://nextjs.org/)
[![Powered By](https://img.shields.io/badge/Powered_By-Shruhh.inc-F59E0B?style=for-the-badge)](https://github.com/)
[![License](https://img.shields.io/badge/License-Proprietary-EF4444?style=for-the-badge)](https://github.com/)

<br/>

*Sticky Notes is a sleek, modern sticky notes application that lets you organize your thoughts on an infinite digital canvas. Drag, resize, color-code, and search — all with a buttery-smooth experience designed for mobile.*

<br/>

### 📥 Download

<a href="https://github.com/rahulloyal/Sticky-Notes---The-Digital-Canvas/releases/latest/download/Sticky-Notes.apk">
  <img src="https://img.shields.io/badge/⬇_Download_APK-v1.0.0-brightgreen?style=for-the-badge&logo=android&logoColor=white" alt="Download APK" height="50" />
</a>

<br/>

<sub>📱 Android 8.0+ required • No ads • 100% offline</sub>

<br/><br/>

[Features](#-features) · [Screenshots](#-screenshots) · [Tech Stack](#-tech-stack) · [Architecture](#-architecture) · [Download](#-download) · [Developer](#-developer)

</div>

---

<br/>

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 Rich Color Palette
Choose from **6 beautiful color themes** — Yellow, Pink, Blue, Green, Purple, and Orange — to categorize and personalize every note.

### 🔍 Real-Time Search
Instantly search through all your notes with **live filtering**. Matching notes are highlighted while others gracefully fade out.

### 📐 Drag & Resize
Freely **drag notes** anywhere on the infinite canvas. **Resize** them from the corner handle to fit any amount of content.

</td>
<td width="50%">

### 🔄 Pinch-to-Zoom
**Pinch to zoom** in and out of your canvas (25% → 200%). Dedicated zoom controls also available at the bottom-left corner.

### 💾 Persistent Storage
All notes are **saved automatically** to local storage. Your canvas is always there when you come back — no login required.

### ⌨️ Keyboard Shortcuts
Power-user shortcuts: **`N`** for new note, **`Ctrl+/- `** for zoom, **`Ctrl+0`** to reset zoom, and **double-click** to add a note at cursor.

</td>
</tr>
</table>

### More Features

| Feature | Description |
|---------|-------------|
| 🗑️ **Smart Delete** | Two-step delete confirmation prevents accidental data loss |
| 📋 **Board System** | Organize notes across named, renamable canvases |
| 🎯 **Context Menu** | Right-click anywhere to add a note at that exact position |
| 📱 **Mobile-First** | Designed with safe areas for notch displays & gesture navigation |
| ✏️ **Inline Editing** | Click any note to start typing — no modals, no friction |
| 🏷️ **Note Counter** | Live badge shows total note count in the toolbar |
| 🧲 **Z-Index Management** | Click a note to bring it to front — natural stacking behavior |
| 🎭 **Smooth Animations** | Micro-animations, hover effects, and transitions throughout |
| 📏 **Dot Grid Background** | Beautiful dot-pattern canvas that scales with zoom |
| 🌐 **Cross-Platform** | Runs as a web app and an Android APK via Capacitor |

<br/>

---

<br/>

## 📸 Screenshots

<div align="center">

### Empty Canvas • Getting Started

<img src="assets/screenshots/01-empty-canvas.png" alt="Empty Canvas" width="280" style="border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.12);" />

<br/><br/>

*Clean, minimal canvas with helpful onboarding — keyboard shortcuts & a call-to-action button to create your first note.*

<br/><br/>

### Notes on Canvas • Drag, Write, Organize

<img src="assets/screenshots/02-notes-with-search.png" alt="Notes with Search" width="280" style="border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.12);" /> &nbsp;&nbsp;&nbsp;&nbsp; <img src="assets/screenshots/04-multiple-notes.png" alt="Multiple Notes" width="280" style="border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.12);" />

<br/><br/>

*Multiple colored sticky notes freely placed on the canvas with drag handles, resize grips, and search bar.*

<br/><br/>

### Color Picker • Personalize Your Notes

<img src="assets/screenshots/03-color-picker.png" alt="Color Picker" width="280" style="border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.12);" />

<br/><br/>

*Beautiful popover menu with 6 color options and a delete action — keeping the interface clean and minimal.*

<br/><br/>

### Clear All • Safe Bulk Actions

<img src="assets/screenshots/05-clear-all-dialog.png" alt="Clear All Dialog" width="280" style="border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.12);" />

<br/><br/>

*Confirmation dialog prevents accidental deletion — clear UI hierarchy with destructive action highlighted in red.*

</div>

<br/>

---

<br/>

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Framework** | ![Next.js](https://img.shields.io/badge/Next.js_16-000000?logo=nextdotjs&logoColor=white&style=flat-square) | React framework with App Router |
| **Language** | ![TypeScript](https://img.shields.io/badge/TypeScript_5.7-3178C6?logo=typescript&logoColor=white&style=flat-square) | Type-safe development |
| **UI Library** | ![React](https://img.shields.io/badge/React_19-61DAFB?logo=react&logoColor=black&style=flat-square) | Component-based UI |
| **Styling** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?logo=tailwindcss&logoColor=white&style=flat-square) | Utility-first CSS framework |
| **Components** | ![Radix UI](https://img.shields.io/badge/Radix_UI-161618?logo=radixui&logoColor=white&style=flat-square) | Accessible, headless UI primitives |
| **Icons** | ![Lucide](https://img.shields.io/badge/Lucide_Icons-F56565?style=flat-square) | Modern, consistent icon set |
| **Native** | ![Capacitor](https://img.shields.io/badge/Capacitor_8-119EFF?logo=capacitor&logoColor=white&style=flat-square) | Web → Android bridge |
| **Notifications** | ![Sonner](https://img.shields.io/badge/Sonner-000000?style=flat-square) | Beautiful toast notifications |
| **Analytics** | ![Vercel](https://img.shields.io/badge/Vercel_Analytics-000000?logo=vercel&logoColor=white&style=flat-square) | Performance & usage tracking |

</div>

<br/>

---

<br/>

## 🏗️ Architecture

```
📦 Sticky Notes
├── 🎯 app/              # Next.js App Router
│   ├── page.tsx          # Main entry — board initialization
│   ├── layout.tsx        # Root layout with theme provider
│   └── globals.css       # Global styles & design tokens
│
├── 🧩 components/        # React Components
│   ├── sticky-canvas.tsx # Infinite canvas with zoom & pan
│   ├── sticky-note.tsx   # Individual note with color & resize
│   ├── canvas-toolbar.tsx# Top bar with search, add, clear
│   ├── empty-canvas.tsx  # Onboarding empty state
│   ├── note-color-picker.tsx
│   └── ui/               # Radix-based UI primitives
│
├── 🪝 hooks/             # Custom React Hooks
│   ├── use-sticky-notes  # CRUD operations & search filtering
│   └── use-canvas-interactions # Drag & resize state machine
│
├── 📚 lib/               # Core Logic
│   ├── sticky-notes-storage.ts  # LocalStorage persistence
│   ├── sticky-notes-types.ts    # TypeScript interfaces
│   ├── note-colors.ts           # Color palette configuration
│   └── utils.ts                 # Utility functions
│
└── 📱 android/           # Capacitor Android Project
    └── ...               # Native Android build files
```

<br/>

---

<br/>

## 🎨 Design Philosophy

<div align="center">

> *"The best tool is the one that gets out of your way."*

</div>

<br/>

- **🎯 Zero Friction** — Double-click to create, click to edit. No buttons, modals, or forms standing between you and your thought.

- **🌊 Infinite Canvas** — No pages, no folders, no hierarchy. Just a wide-open space that grows with your ideas.

- **🎨 Tactile & Familiar** — Real sticky-note aesthetics with tape-strip headers, soft shadows, and subtle rotations make digital feel physical.

- **📱 Mobile-Native Feel** — Built for touch-first with safe area handling, pinch-to-zoom, and gesture-friendly interactions.

<br/>

---

<br/>

## 👨‍💻 Developer

<div align="center">

### Developed by

# **Rahul Loyal Dalmas**

<br/>

<a href="https://www.instagram.com/rahul_.loyal/" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=for-the-badge" alt="Instagram" />
</a>
&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/rahul-loyal-dalmas-5baa4532b/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn" />
</a>

<br/><br/>

---

<br/>

### Powered by

<img src="https://img.shields.io/badge/Shruhh.inc-F59E0B?style=for-the-badge&logoColor=white" alt="Shruhh.inc" />

<br/><br/>

*Building beautiful, human-centered digital experiences.*

</div>

<br/>

---

<br/>

<div align="center">

### ⭐ If you like this project, give it a star!

<br/>

Made with ❤️ by **Rahul Loyal Dalmas** × **Shruhh.inc**

<br/>

© 2026 Shruhh.inc — All Rights Reserved.

</div>
