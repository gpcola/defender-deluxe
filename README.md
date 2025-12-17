# Defender Deluxe — Classic (v1.2 Pressure)

A **modern, Reddit-friendly homage** to the 1980s Williams arcade classic **Defender** — rebuilt from scratch as a **single-file HTML5 game** with daily challenges, rescue gameplay, and competitive leaderboards.

No backend. No installs. Just pure arcade pressure.

🎮 **Play on desktop, tablet, or mobile**  
🏆 **Daily leaderboard via GitHub Issues**  
🛰️ **Classic Defender mechanics with modern polish**

---

## 🔥 Features

### Core Gameplay
- 🌍 **World-wrap horizontal planet**
- 👾 **Landers abducting humans**
- 🧬 **Mutants spawn when humans are lost**
- 🟥 **Baiters** hunt you down if you linger
- 🧍 **Rescue loop**: catch falling humans mid-air
- 💣 **Smart bomb**
- ✨ **Hyperspace** (with classic risk)
- 📈 **Wave escalation + pressure system**

### Arcade Authenticity
- Pixel-scaled renderer (320×240 → crisp scaling)
- Defender-style ship inertia and thrust
- Abduction beams with oscillation
- Radar showing enemies, humans, and ship
- Danger meter that reflects screen pressure
- Mean enemy AI that *punishes hesitation*

### Controls
**Keyboard**
- `← / →` Rotate
- `↑` Thrust
- `Space` Fire
- `B` Smart Bomb
- `Shift` Hyperspace

**Touch / Tablet**
- Virtual joystick (left side)
- Fire / Bomb / Hyper buttons (right side)
- **Handedness swap** for left-handed players

---

## 🏆 Daily Leaderboard (No Backend)

Each day uses a **UTC daily seed**.

Scores are submitted via **GitHub Issues**:
- One submission per player per day
- You may resubmit only if you beat your best
- Leaderboard auto-parses today’s issues

✔ Transparent  
✔ Abuse-resistant  
✔ Zero server costs  

---

## 👻 Ghost Runs
- Your inputs are recorded locally
- Share a **ghost link** with others
- Open a ghost URL to race another player’s run

---

## ⚔️ Real-Time Duels (Experimental)
- Peer-to-peer **WebRTC**
- Manual offer / answer (copy-paste)
- Opponent ship rendered in cyan
- No server, no matchmaking, no tracking

---

## 📱 Performance & Compatibility
- Single `index.html` file
- No external libraries
- No images, no audio files
- Object pooling for stable frame rates
- Runs smoothly on tablets and low-power devices

---

## 🚀 How to Run

### Local
```bash
open index.html
