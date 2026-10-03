# SHADO-PUZZLE

**Shape the darkness.**

A fully offline HTML5 puzzle game built with pure vanilla JavaScript. Arrange geometric shapes in front of light sources so their **shadows** match the target silhouette.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile-lightgrey)
![No Dependencies](https://img.shields.io/badge/dependencies-none-success)

---

## 🎮 What is SHADO PUZZLE?

SHADO PUZZLE is a single-file browser puzzle game where you manipulate geometric shapes — squares, triangles, hexagons, stars — by dragging, rotating, and scaling them. A light source projects each shape onto a dark plane, and your goal is to align the resulting **shadow** with a dashed cyan target silhouette.

Hold a **90% match** and the level locks in.

No internet. No installs. No frameworks. Just open `index.html` and play.

---

## ✨ Features

- 🎯 **100 handcrafted levels** across 7 distinct worlds
- 🌍 **7 Worlds**: First Shadow, Geometry, Combination, Light Shift, Mirror, Multi Light, Shadow Master
- 💡 **Dual lighting system** — point lights and directional lights
- 🪞 **Mirror mechanics** — reflections cast twin shadows
- 📅 **Daily Puzzle** — new challenge every day with streak tracking
- 🏆 **20 Achievements** to unlock
- ⭐ **Star rating system** (1–3 stars per level)
- 🎨 **Real-time match meter** showing percentage alignment
- 💾 **Auto-save** — all progress stored locally via `localStorage`
- 📱 **Mobile-first design** — touch, pinch, and twist gestures
- 🔊 **Procedural audio** — synthesized with the Web Audio API
- ♿ **Accessibility options** — Reduced Motion, Visual Intensity control
- 🚫 **Zero dependencies** — no libraries, no build step, no CDN

---

## 🕹️ How to Play

1. **Select an object** — tap any glowing shape. A dashed ring marks the selection.
2. **Move it** — drag with one finger.
3. **Rotate & Scale** — use `↺ ↻` for 15° rotation steps and `− +` for size. Or pinch and twist with two fingers.
4. **Study the light** — closer objects cast larger shadows. Mirrors create reflected twin shadows.
5. **Match the target** — fill the dashed cyan silhouette. The match meter rises as you get closer.
6. **Complete the puzzle** — hold a match of 90% or more and the level locks in. Fewer moves and no hints earn three stars.

---

## 🚀 Getting Started

### Run Locally

```bash
# Clone the repository
git clone https://github.com/sakibsheikho69252-netzen/SHADO-PUZZLE.git
cd SHADO-PUZZLE

# Open in your browser — just double-click index.html
# Or serve it locally:
python3 -m http.server 8000
# Then visit http://localhost:8000
