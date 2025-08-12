# Pixel Outrider

A single-file, 8-bit, endless run-and-gun with day/night parallax, on-screen visibility AI, lives & respawns, HP packs, and retro-hardcoded pixel sprites.

## Play
Open `index.html` locally, or enable **GitHub Pages** for instant web play (Settings → Pages → Deploy from `main` / root).

## Features
- Calmer physics & pacing
- 3 lives, last-ground respawn (+60% HP, i-frames, −10% score)
- Enemies only shoot when **visible** (with wind-up & aim jitter)
- HP packs (+25%) with safe spawns
- Day 🌤 / Night 🌙 toggle + optional B/W ◻️ filter
- Hardcoded pixel sprites (no assets), crisp (smoothing off)
- Backgrounds rebuild on resize (no tearing)

## Controls
- **Move**: A/D or ←/→
- **Jump**: W / ↑ / Space (coyote time + jump buffer; no auto-hop)
- **Aim/Shoot**: Mouse (hold to fire)
- **Pause**: `P`
- **Debug**: `H`
- **Restart** (game over): `R`
- **Toggles** (top-right): Pause • Music • Night/Day • B/W

## Build/Tech
- HTML5 Canvas, single file
- No external assets required
- Pixel-perfect rendering (image smoothing disabled everywhere)
