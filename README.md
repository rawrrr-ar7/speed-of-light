# The Speed of Light, But You Can Feel It

A scroll-driven visual experience that turns your scroll position into the actual speed of light — so you can feel how far light travels to the Moon, the Sun, and the nearest star, just by scrolling.

**[Live Demo →](https://your-deployed-link-here.vercel.app)**

---

## Why This Exists

Light moves at 299,792 km per second — a number that means nothing until you try to *feel* it. This experience maps your scroll distance directly to light-years traveled, so the gap between "the Moon" and "the nearest star" stops being abstract and starts being something you physically experience by scrolling.

No login. No data entry. No explanation needed. Just scroll.

---

## What It Does

- Tracks scroll position in real time and converts it into distance traveled at the speed of light
- Visualizes the journey from Earth → Moon → Sun → Proxima Centauri on an animated canvas
- Shows live distance and elapsed "light time" as you scroll
- Built-in share buttons (Twitter, Facebook, Reddit, WhatsApp, LinkedIn, Email, native share, copy link)

---

## Tech Stack

- Pure HTML, CSS, and vanilla JavaScript — zero dependencies, zero build step
- Canvas API for the animated light beam and celestial bodies
- Native Web Share API with clipboard fallback for sharing

---

## Running It Locally

No installation required.

```bash
git clone https://github.com/your-username/speed-of-light.git
cd speed-of-light
open index.html
```

Or just double-click `index.html` — it runs entirely in the browser.

---

## Deploying Your Own Copy

This is a single static file, so any free static host works:

- **Vercel** — import this repo, deploy, done in under a minute
- **GitHub Pages** — enable in repo Settings → Pages → deploy from `main` branch root
- **Netlify** — drag and drop the file directly

---

## Project Status

Built as a quick, self-contained experiment in making abstract numbers feel physical. Not actively maintained as a product — pull requests and forks welcome if you want to extend it (other distances, other speeds, other journeys).

---

## License

MIT — do whatever you want with it.
