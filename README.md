<p align="center">
  <img src="screenshots/icon128.png" alt="Study Loop" width="80" />
</p>

<h1 align="center">Study Loop</h1>

<p align="center">
  <strong>A Chrome extension for repeating and saving A-B loop sections on YouTube videos.</strong><br>
  Perfect for language learning, music practice, exam prep, and online courses.
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/dkdhafdpjeafkmojbmikjgaeckankggn">
    <img src="https://img.shields.io/badge/Chrome%20Web%20Store-Install%20Free-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Install from Chrome Web Store" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-green" alt="Version" />
  <img src="https://img.shields.io/badge/manifest-v3-orange" alt="Manifest V3" />
  <img src="https://img.shields.io/badge/license-proprietary-lightgrey" alt="License" />
  <img src="https://img.shields.io/badge/languages-EN%20%7C%20JA-blueviolet" alt="Languages" />
</p>

---

## The Problem

You're watching a YouTube lecture and hear something you need to review. You rewind, overshoot, try again, lose your place. Repeat 10 times. Sound familiar?

YouTube has no way to:
- Loop a specific section of a video
- Save that section for later
- Track which parts you've mastered
- Organize your study materials

**Study Loop fixes all of this.**

---

## Demo

<p align="center">
  <img src="screenshots/demo.gif" alt="Study Loop Demo" width="800" />
</p>

> Set A/B points → Loop automatically → Save with tags → Track mastery

---

## Use Cases

| Who | How they use it |
|-----|----------------|
| 🎓 **Exam students** | Loop difficult lecture explanations, track mastery per topic |
| 🌍 **Language learners** | Repeat native speech until you catch every word |
| 🎸 **Musicians** | Loop riffs, solos, and chord progressions for practice |
| 💃 **Dancers** | Repeat choreography sections at any speed |
| 💻 **Coding students** | Re-watch complex tutorial sections |
| 📚 **Anyone studying on YouTube** | Turn passive watching into active learning |

---

## Features

### 🔁 AB Loop Playback
Set precise start and end points on any YouTube video. Fine-tune by **0.5 seconds** (or **0.1s** with Shift). Loop runs automatically until you stop it.

<p align="center">
  <img src="screenshots/control-bar.png" alt="Control Bar" width="700" />
</p>

### 📌 Save & Tag Segments
Save loop sections with custom names and tags:
- 🔴 **Weak** — sections you struggle with
- 🟠 **Important** — key concepts
- 🟣 **Needs Review** — come back later

### ⭐ Mastery Tracking
Track your progress on every saved segment:

`Unlearned` → `Learning` → `Mastered`

See at a glance which sections still need work.

### 📁 Courses & Folders
Organize your videos by subject:
```
📂 Real Estate Exam
  📁 Property Law
    📄 Lecture #1 — Mortgage basics
    📄 Lecture #2 — Lien priority
  📁 Contract Law
    📄 Lecture #5 — Breach remedies
```

### 📅 Monthly Study Calendar
Visualize your daily study time on a calendar heatmap. Stay consistent, build streaks.

<p align="center">
  <img src="screenshots/calendar.png" alt="Study Calendar" width="400" />
</p>

### ⏸ Loop Interval
Add a **pause between loops** (1–10 seconds) to test your recall before the next repetition. Great for active recall practice.

### 🏆 Achievement Badges
14 badges to keep you motivated:

| Badge | Condition |
|-------|-----------|
| 🎯 First Step | Save your first segment |
| 📚 Collector | Save 10 segments |
| 🔄 Repeater | 100 loop plays |
| 🔥 Loop Master | 500 loop plays |
| ⚔️ 7-Day Warrior | 7-day study streak |
| 🛡️ Iron Will | 30-day study streak |
| 👑 Conqueror | Complete 10 videos |
| 🎓 50 Hours | 50 hours total study time |

### ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `A` | Set point A |
| `B` | Set point B |
| `L` | Toggle loop ON/OFF |
| `N` | Jump to next segment |
| `P` | Jump to previous segment |
| `◀▶` | Fine-tune A/B points (0.5s, Shift: 0.1s) |

### 🎨 3 Color Themes
- **Dark** — easy on the eyes for late-night study
- **Light** — clean and bright
- **Natural** — warm, paper-like tones

### 🌐 Multilingual
Full support for **English** and **Japanese**. Auto-detects your browser language.

---

## Free vs Pro

| | Free | Pro |
|---|---|---|
| AB Loop Playback | ✅ | ✅ |
| Save Segments | 5 | **Unlimited** |
| Mastery Tracking | ✅ | ✅ |
| Courses & Folders | ✅ | ✅ |
| Study Calendar | ✅ | ✅ |
| Achievement Badges | ✅ | ✅ |
| 3 Themes | ✅ | ✅ |
| Keyboard Shortcuts | ✅ | ✅ |
| Loop Interval | ✅ | ✅ |
| Price | **Free** | **¥300/mo** or **¥2,400/yr** |

> All data is stored locally in your browser. No account required. No data sent to any server.

---

## Install

<a href="https://chromewebstore.google.com/detail/eaoebngdfobicneaaacpjjldnknhcpdg">
  <img src="https://img.shields.io/badge/Install%20from-Chrome%20Web%20Store-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome Web Store" />
</a>

1. Click the link above
2. Click "Add to Chrome"
3. Go to any YouTube video
4. The Study Loop control bar appears below the player
5. Start learning!

---

## How It Works

```
1. Play a YouTube video
2. Press A at the start of the section you want to loop
3. Press B at the end
4. Toggle Loop ON → it repeats automatically
5. Click "Save Segment" → name it, tag it
6. Come back anytime → one tap to resume looping
7. Mark as "Mastered" when you've got it ✓
```

---

## Tech Stack

- **TypeScript** — type-safe codebase
- **Chrome Manifest V3** — latest extension platform
- **chrome.storage.local** — all data stored locally
- **YouTube IFrame API** — player control
- **esbuild** — fast builds

---

## Privacy

- ✅ All data stored locally in your browser
- ✅ No external servers
- ✅ No tracking or analytics
- ✅ No account required
- ✅ Payment processed securely via Stripe (for Pro only)
- ✅ Uninstall removes all data automatically

[Full Privacy Policy](https://studyloop-privacy.pages.dev/)

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the full update history.

### v1.0.0 (2026-05-04)
- 🎉 Initial release
- AB loop playback with fine-tuning (0.5s / 0.1s)
- Segment saving with tags and mastery tracking
- Course and folder organization
- Monthly study calendar
- 14 achievement badges
- Loop interval (1–10 seconds)
- 3 color themes (Dark / Light / Natural)
- Data export/import
- English and Japanese support

---

## Feedback & Feature Requests

Found a bug? Have an idea? 

- 🐛 [Report a Bug](../../issues/new?template=bug_report.md)
- 💡 [Request a Feature](../../issues/new?template=feature_request.md)

---

## Support

If Study Loop helps your learning, please consider:
- ⭐ **Starring this repo** — it helps others find the project
- 📝 **Leaving a review** on the [Chrome Web Store](https://chromewebstore.google.com/detail/eaoebngdfobicneaaacpjjldnknhcpdg/reviews)
- 🔄 **Sharing** with friends who study on YouTube

---

<p align="center">
  Made with ☕ in Japan<br>
  <a href="https://chromewebstore.google.com/detail/eaoebngdfobicneaaacpjjldnknhcpdg">Chrome Web Store</a> · <a href="https://studyloop-privacy.pages.dev/">Privacy Policy</a>
</p>
