# Shashank Sphoorthi — Personal Portfolio Website 🌐

A personal portfolio website showcasing my work in ECE, Embedded Systems, Edge AI, IoT, and AIoT systems. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step.

**Live site:** [sphoorthi340-bit.github.io/Tech-Portfolio-Website](https://sphoorthi340-bit.github.io/Tech-Portfolio-Website)

## What's inside

- **Hero** — Animated particle mesh (represents ESP-NOW mesh topology), typewriter cycling through my focus areas, key stats.
- **About** — Who I am, what I build, and what I'm looking for.
- **Projects** — Four builds with architecture diagrams and real technical details:
  - **Sahayak** — Offline-first AIoT disaster response system (Kaggle × Google DeepMind Hackathon, 1st place). ESP-NOW mesh + Gemma 4 + FastAPI + React PWA.
  - **ESP32 Encrypted Chat** — P2P encrypted terminal over ESP-NOW. AES-128-ECB + ChaCha20 via mbedTLS, benchmarked at 2.3ms latency.
  - **Op-Amp Signal Conditioning** — Analog sensor pipeline from scratch: LM35 → LM358 amplifier → RC filter → 12-bit ADC → OLED display.
  - **Project Rebuild** — Flutter + Firebase fitness & mental health tracker. 60fps sustained, 5 decoupled feature modules.
- **Skills** — Six grouped categories covering Embedded & Hardware, AI/ML & Edge Intelligence, Systems & Security, Backend & Full Stack, IoT Protocols & Networking, and Focus Areas.
- **Roadmap** — Timeline from now to graduation: flagship AIoT project → embedded internship → prototype + publication → B.Tech completion.
- **Contact** — Email, LinkedIn, GitHub. Open to embedded AI / IoT internship opportunities for Summer 2026.

## File structure

```text
Tech-Portfolio-Website/
├── index.html      # Full single-page portfolio
├── style.css       # All styles (design tokens, layout, components, animations)
└── README.md       # This file
```

The site is intentionally self-contained — no npm, no bundler, no dependencies beyond Google Fonts.

## Design system

| Token | Value |
|-------|-------|
| Background | `#07090f` |
| Surface | `#0d1117`, `#111827` |
| Accent (cyan) | `#00c8ff` |
| Secondary (purple) | `#a855f7` |
| Success (green) | `#10b981` |
| Display font | Syne (600–800) |
| Code font | JetBrains Mono (300–500) |
| Body font | DM Sans (300–500) |

## Deploying on GitHub Pages

This repo already deploys via GitHub Pages. To update:

1. Edit `index.html` or `style.css` directly (or clone and push)
2. GitHub Pages automatically rebuilds from the `main` branch root
3. Live at [sphoorthi340-bit.github.io/Tech-Portfolio-Website](https://sphoorthi340-bit.github.io/Tech-Portfolio-Website) within ~30 seconds

To set up GitHub Pages for the first time on a fork:

1. Go to **Settings** → **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` / `/ (root)`
4. **Save**

## Tech stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, Grid, Flexbox, keyframe animations, `IntersectionObserver`-triggered fade-ups
- **Vanilla JS** — Particle mesh canvas, typewriter effect, scroll-triggered nav

## Contact

**Shashank Sphoorthi** — Electronics & Communication Engineering, Vasavi College of Engineering, Hyderabad, Class of 2028.

- **Email:** [Sphoorthi340@gmail.com](mailto:Sphoorthi340@gmail.com)
- **LinkedIn:** [linkedin.com/in/shashank-sphoorthi](https://www.linkedin.com/in/shashank-sphoorthi/)
- **GitHub:** [@sphoorthi340-bit](https://github.com/sphoorthi340-bit)

> *"Build at the edge. Reason at the edge. Stay offline-first."*
