# Never Work Alone

Official website for **Never Work Alone**, an independent software development team.

**Website:** https://neverworkalone.net

## Products

- **Translight · 빛번역** — web page translation Chrome extension
- **NaverDic · 네이버 영어사전** — English dictionary Chrome extension
- **Typewriter** — thesaurus and writing tool for writers

## Site

This repository contains the static Never Work Alone website.

- Plain HTML
- CSS
- Minimal JavaScript
- Korean / English language switching
- Responsive desktop and mobile layouts
- No framework, build step, or runtime dependency

The site is deployed with GitHub Pages from the repository root. The custom domain is `neverworkalone.net`.

Individual product documentation remains in each product repository and is served under its own project path, such as `/naverdic/` and `/translight/`.

## Development

Because the site is fully static, it can be opened directly or served with any local static HTTP server.

Main files:

- `index.html` — page structure and content
- `styles.css` — layout and visual design
- `script.js` — language switching and small client-side behavior
- `assets/` — Never Work Alone visual assets

## Design

The website follows the Never Work Alone Figma design and keeps the implementation intentionally small and dependency-free.
