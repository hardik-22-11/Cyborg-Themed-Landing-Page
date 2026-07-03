# VESSEL — Where Flesh Ends, We Begin

A cyborg-themed landing page for a fictional cybernetic integration studio. Built on one idea: a cyborg isn't a robot with skin on — it's the **seam** where organic and synthetic argue and eventually agree. Every design decision runs through that split.

🔗 **Live demo:** [add your GitHub Pages / hosted link here]
🎥 **Walkthrough:** [add your Drive link here]

---

## The concept

Two systems, one body. Coral (`#FF6B4A`) is the organic half — pulse, tissue, warmth. Teal (`#3ED6C4`) is the synthetic half — signal, circuit, precision. They never fully blend; they run in parallel and meet at a seam, which is the whole visual language of the page.

## Highlights

- **Split-identity palette** — no single accent color; two colors in tension, used consistently across type, buttons, and data
- **Live vitals strip** — a signature animated waveform: heartbeat on one side, signal pulse on the other, converging into a single line
- **A procedure that's actually a procedure** — the 5-step integration timeline is numbered because it's a real sequence, not decoration
- **Type system with a job** — Chakra Petch for machine-precision headlines, Inter for human-readable body copy, JetBrains Mono for HUD/data readouts
- **Fully responsive** — collapses cleanly down to mobile, no dropped content
- **Scroll-reveal + reduced-motion respected** — animations are there to earn attention, not to show off

## Stack

Plain HTML/CSS/JS. No build step, no framework, no dependencies beyond Google Fonts. Open `index.html` and it just works.

## Structure

```
├── Hero          — split pulse/signal visual + headline
├── Modules       — 4 augmentation systems
├── Integration   — the 5-phase procedure
├── Readout       — live stats strip
├── Subjects      — testimonials from "integrated" users
└── CTA           — book a baseline scan
```

## Run locally

```bash
git clone <your-repo-url>
cd vessel
open index.html   # or just double-click it
```

No install, no server required.

---

Built for Techfest CA — Task 1: Cyborg-Themed Landing Page Development.
