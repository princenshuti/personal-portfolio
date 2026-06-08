# personal-portfolio

Personal one-page portfolio for **[princenshuti.com](https://princenshuti.com)** — Prince Nshuti, Network & Cybersecurity infrastructure engineer and Technical Account Manager based in Kigali, Rwanda.

## Stack

A single, self-contained `index.html` — no build step, no dependencies. Pure HTML, CSS and vanilla JavaScript.

- **Fonts:** Space Grotesk, Inter, JetBrains Mono (Google Fonts)
- **Theme:** light/dark toggle, persisted to `localStorage`, defaults to the visitor's system preference (no flash on load)
- **Motion:** scroll-reveal via `IntersectionObserver`, animated certifications marquee — all gated behind `prefers-reduced-motion`
- **Accessible:** semantic markup, `aria` labels on interactive controls, responsive from 375px up

## Run locally

Any static file server works, e.g.:

```bash
python3 -m http.server 4181
# then open http://localhost:4181
```

## Deploy

Because it's a single static file, it can be hosted anywhere — GitHub Pages, Netlify, Vercel, or a cPanel host. Point the `princenshuti.com` domain at wherever it's served.
