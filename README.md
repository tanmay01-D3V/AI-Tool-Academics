# ⚡ Neon Particle Sandbox ⚡

**Student:** [YOUR FULL NAME]  |  **Roll No:** #35
**Live App:** https://[your-username].github.io/crazy-app-student-35/

> Your mouse is a lightning rod. The canvas is a storm. 🌩️

## What Is This?

A cyberpunk, dark-mode particle sandbox built as a single `index.html` file (HTML + CSS + JavaScript, no libraries). Every mouse movement throws off glowing neon sparks, every click detonates a shockwave, and the browser's built-in Web Audio API turns it all into synth and glitch sounds.

## How to Play

| Action | What Happens |
|---|---|
| **Move the mouse** | Neon sparks trail behind your cursor. Faster swipes make more sparks and higher-pitched synth blips. |
| **Click** | Explosion, expanding shockwave ring, screen shake, and a bass boom. |
| **Hold the mouse down** | Turns your cursor into a black hole that pulls every particle toward it. |
| **Sound button** | Turn audio on or off (browsers need a click before they allow sound). |
| **Glitch button** | Toggles glitch mode: colour shift, sliced screen, and static bursts. |
| **Clear button** | Wipes the canvas. |

Works with touch screens too.

## 🕵️ Secret Features

- Press **`G`** to toggle Glitch mode without touching the button.
- Press **`B`** to trigger the **BIG BANG**: five chained explosions across the whole screen, with shake and sound.
- Watch the **particle counter** (top right) climb as you go wild. It's capped at 2,500 so your computer survives.
- The title **flickers** like a dying neon sign.

## Under the Hood

- `requestAnimationFrame` main loop (the "traffic police officer" in the code comments)
- Canvas additive blending (`lighter`) so overlapping particles glow
- Web Audio API oscillators + generated noise buffers (no audio files)
- 3 `console.assert()` unit tests covering normal, zero, and negative inputs

## Run It Locally

Just double-click `index.html`. No install, no server.

---
*Created by Student #35 for AI Coding Lab, Unit 3: AI Applications.*
