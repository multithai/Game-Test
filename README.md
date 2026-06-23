# 🏍️ Road to Liberty

A 2D top-down arcade game. Ride your motorcycle, **drag** to collect falling
bike parts, and dodge the rocks. Beat the target before time runs out!

## ▶️ Play

Open `index.html` in any modern browser (desktop or mobile). No build step,
no dependencies — it's a single self-contained file.

```bash
# from the repo root
open index.html      # macOS
xdg-open index.html  # Linux
# or just double-click the file
```

## 🎮 How to Play

| | |
|---|---|
| **Move** | Drag (touch) or click-and-drag the bike left/right at the bottom |
| **Collect** | ⛽ fuel tank · 🛞 wheel · 🔧 handlebar · 💡 headlight → **+points** |
| **Avoid** | 🪨 rocks → **lose points** |
| **Goal** | Reach **13 points** before the **20-second** timer ends |

## ✨ Features

- **Start screen** with game logo, rules, and a motorcycle picker
  (*Choose Your Liberty Edition* — 3 colored models).
- **3 · 2 · 1 · GO!** animated countdown.
- **Gameplay**: items rain from the top and speed up over time; live HUD with
  **Score** (top-left) and **Time** (top-right, 20.0s limit).
- **Result screen** showing the final score, a verdict
  (*"WELL DONE! You hit the target!"* when you reach 13), and a **REPLAY** button.

See [`GAME_DESIGN.md`](./GAME_DESIGN.md) for the full design specification.
