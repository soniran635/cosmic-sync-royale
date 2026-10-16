cd ~/Projects/cosmic-sync-royale && cat << 'EOF' > README.md
# 🌌 Cosmic Sync: Take The Mic!

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-38bdf8?style=for-the-badge&logo=github)](https://soniran635.github.io/cosmic-sync-royale/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **Turn meeting fatigue into momentum.** A zero-install, browser-based sci-fi arcade icebreaker that automates meeting turn order, gamifies standups, and exports speaking queues directly to Slack and Microsoft Teams in 1 click.

---

## 🕹️ Live Demo
Play immediately in your browser:  
👉 **[https://soniran635.github.io/cosmic-sync-royale/](https://soniran635.github.io/cosmic-sync-royale/)**

---

## ✨ Features

- **⏱️ 90-Second Mission Clock:** Designed strictly for agile standups, sprint reviews, and engineering syncs to eliminate awkward "who speaks next?" dead air without eating into meeting time.
- **👥 Dynamic Roster Engine:**
  - Add or remove team pilots dynamically with smooth, flicker-free tag chips.
  - Inline click-to-edit rename support for all squad members.
  - Automatically encodes room code and pilot lists into shareable query URLs (`?room=XYZ&crew=Name1,Name2`).
- **⚔️ Arena Combat & Scoring Mechanics:**
  - **✨ Stardust Crystals:** Collect 4-point rotating neon gold and cyan crystals to expand ship mass and stardust bounty.
  - **🎯 Tactical Absorption:** Target rivals inside a green lock-on ring to absorb their mass; evade dangerous red predator halos.
  - **🔥 Singularities:** Avoid fiery crimson black holes that inflict hull decay.
  - **⚡ Anti-Camping System:** Stationary ships passively decay to encourage active navigation.
- **📋 1-Click Meeting Export:** Formats and copies the final standup speaker sequence, stardust scores, active monthly bounty, and flight lead icebreaker prompt directly to your clipboard for Slack or Teams.
- **🎵 Retro Web Audio:** Dynamic 8-bit procedural synth audio, laser warp boosts, and victory fanfares powered by the native Web Audio API (zero external asset dependencies).

---

## 🎮 Flight Controls

| Control | Action |
| :--- | :--- |
| **Mouse / Cursor** | Aim and steer ship thrusters |
| **W, A, S, D / Arrows** | Precision directional navigation |
| **Spacebar** | Engage Warp Booster |
| **🟢 Green Ring** | Ram rival to absorb mass |
| **🔴 Red Halo / Hole** | Danger zone — evade collision |

---

## 🚀 Quick Setup & Sharing

### 1. Launch a Custom Session
1. Open [Cosmic Sync](https://soniran635.github.io/cosmic-sync-royale/).
2. Set your **Commander Call-Sign** and **Mission Room Code** (e.g., `Video-Eng-Sync`).
3. Add or edit your team's pilots in the **Crew in Orbit** box.
4. Click **🔗 Copy Link** to copy the invite URL with the encoded crew roster and share it in your team chat.

### 2. Local Development
Run locally on macOS using Python's built-in server:

```bash
# Clone the repository
git clone [https://github.com/soniran635/cosmic-sync-royale.git](https://github.com/soniran635/cosmic-sync-royale.git)
cd cosmic-sync-royale

# Start local server
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
