# mattos-home

Spanish-primary marketing home page for Mattos Medical Group — published at:

**https://mattos-medical-group.github.io/mattos-home/**

## Structure

```
mattos-home/
├── index.html             — the home page (Spanish default, EN toggle)
├── colors_and_type.css    — brand tokens (colors, type, fonts)
├── assets/logos/          — mmg-logo.png, mmg-vitruvian.png (watermark)
└── fonts/                 — Trajan Pro Regular + Bold
```

All paths are local/relative. Cross-page links (BHRT, Weight Loss, Cognitiva, Oferta 10) point to the live GitHub Pages URLs of their respective repos.

## Enabling GitHub Pages

1. Push this folder to `main` on `mattos-medical-group/mattos-home`.
2. On GitHub → **Settings → Pages** → Source: `Deploy from a branch`, Branch: `main`, Folder: `/ (root)`.
3. Wait ~30s. Live at `https://mattos-medical-group.github.io/mattos-home/`.
