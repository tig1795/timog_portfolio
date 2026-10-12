# guenthertimo.de

Personal portfolio website of **Timo Günther**: Digital Humanities, data & AI, IT projects.

🔗 **Live:** [guenthertimo.de](https://guenthertimo.de)

## About

A handcrafted, single-page portfolio — no framework, no site generator, no template. Just semantic HTML, modern CSS and a few lines of vanilla JavaScript.

**Featured on the site:**
- Resumé: experience, education & certifications
- Nine selected projects (machine learning, usability & prototyping, e-publishing) with tag filtering
- My master's thesis on hit song prediction (XGBoost + Transformer-based NLP, 40,000+ songs)

## Tech

| | |
|---|---|
| Stack | Plain HTML / CSS / JS — zero dependencies, zero build step |
| Typography | [Fraunces](https://fonts.google.com/specimen/Fraunces) · [Archivo](https://fonts.google.com/specimen/Archivo) · [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) |
| Hosting | [Netlify](https://www.netlify.com/), auto-deploys from `main` |
| A11y | Keyboard focus states, `prefers-reduced-motion` support, semantic markup |

## Structure

```
site/
├── index.html        # the entire site — content, styles & scripts
├── assets/           # images
└── files/            # resumé PDF
netlify.toml          # deploy config (publish: site/)
```

> **Note:** The remaining folders (`content/`, `config/`, `assets/`, `data/`) are legacy files from the previous Hugo/Wowchemy version of this site and are no longer used.

## Local preview

No build needed — just open the file:

```
site/index.html
```

## Deploy

Every push to `main` triggers an automatic Netlify deploy:

```bash
git add -A
git commit -m "Update content"
git push
```

---

© 2026 Timo Günther
