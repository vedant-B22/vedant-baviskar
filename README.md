# Vedant Baviskar — Personal Site

A single-file, cinematic portfolio site — built around a "blueprint" concept: the page reads as a set of numbered sheets (00–05), complete with corner registration marks, a crosshair cursor with live coordinates, and scroll-triggered reveals.

**Live file:** `index.html` — no build step, no dependencies to install. Open it in a browser or deploy as a static site.

## About

I'm Vedant Baviskar, co-founder of [Vesa Studios](https://vesastudios.site), a Pune-based studio building brand identity, cinematic websites, and AI/WhatsApp automation for small and medium businesses in India. This site is the personal counterpart to that work — one page, scroll-driven, telling the story across five sheets:

| Sheet | Section | What's there |
|---|---|---|
| 00 | Index | Hero, name, roles |
| 01 | Studio | Vesa Studios — founding, focus, partner |
| 02 | Systems | Selected builds — AeroSense, FabriPay, Speaky-Spooky, AI Lead Discovery, Study Buddy Bro |
| 03 | Craft | Cinematic client work — Verre Meridian, Cenere, Caffeine Addict, SSK Engineering |
| 04 | Beyond Code | *The Summer of Seventeen* — debut novel, releasing Sept 2026 |
| 05 | Contact | LinkedIn, Vesa Studios, The Pulse |

## Design

- **Palette** — deep ink (`#0A0E12`) background, copper (`#C1633A`) and cyan (`#5FA8A6`) accents, warm paper (`#EFE6D8`) tone-shift for the "Beyond Code" section.
- **Type** — [Fraunces](https://fonts.google.com/specimen/Fraunces) for display headlines, [Inter](https://fonts.google.com/specimen/Inter) for body text, [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) for labels, eyebrows, and sheet numbers.
- **Motion** — [GSAP](https://gsap.com/) + ScrollTrigger for scroll-based reveals, a hero title draw-in, and background grid parallax. Respects `prefers-reduced-motion`.

## Tech

Plain HTML, CSS, and JavaScript — no framework, no bundler. External dependencies are loaded via CDN:

- [GSAP](https://cdnjs.com/libraries/gsap) + ScrollTrigger — animation
- Google Fonts — Fraunces, Inter, IBM Plex Mono

## Running locally

```bash
git clone https://github.com/vedant-B22/vedant-baviskar.git
cd vedant-baviskar
open index.html   # or just double-click the file
```

No install, no server required — it's a static file.

## Deploying

Works on any static host. Simplest path with [Netlify](https://www.netlify.com/):

1. Connect this repo to Netlify (or drag-and-drop `index.html` at [app.netlify.com/drop](https://app.netlify.com/drop))
2. Publish directory: `/`
3. Done — no build command needed

## Roadmap

- [ ] Swap in a real headshot / photo
- [ ] Add a contact email
- [ ] Link book Instagram once live
- [ ] Custom domain

## License

© 2026 Vedant Baviskar. All rights reserved.
