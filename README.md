# SANDMAN — Website Design Variations

Four design directions for the **Sandman** custom toy artist portfolio. Same content,
copy, and commission flow in every version — only the visual design differs. Open the
landing page and pick the one that fits the brand best.

## 🔗 Live

**Landing page:** https://jiesparago05.github.io/sandman-portfolio-variations/

| # | Variation | Vibe | Live |
|---|-----------|------|------|
| 1 | **Cinematic Amber** | Dark, cinematic, collector-focused | https://jiesparago05.github.io/sandman-portfolio/ |
| 2 | **Gallery Editorial** | Light, airy, museum-catalog | `/gallery/` |
| 3 | **Urban Vinyl** | Bold street / art-toy, neon | `/urban/` |
| 4 | **Industrial Blueprint** | Raw workshop, blueprint, monospace | `/industrial/` |
| 5 | **Retro Toybox** | Vintage 70s/80s toy packaging | `/retro/` |

> Variation 1 lives in the main repo: [`sandman-portfolio`](https://github.com/jiesparago05/sandman-portfolio).

## Structure

```
index.html              Landing page (compare all 4)
gallery/index.html      Variation 2 — Gallery Editorial
urban/index.html        Variation 3 — Urban Vinyl
industrial/index.html   Variation 4 — Industrial Blueprint
retro/index.html        Variation 5 — Retro Toybox
portfolio_materials/    Shared photos & videos
previews/               Thumbnail screenshots for the landing page
```

## Editing

Each variation is a single self-contained `index.html` (inline CSS + JS, no build step).
Open any one and look for the **`EDIT ME`** guide comment near the top, plus `// REPLACE`
markers showing where to swap in real photos, project details, and social links. The
`SOCIAL` object in each file is the single place to set Instagram / Facebook / Messenger /
email — change it once and every button updates.

Built for GitHub Pages — no backend required.
