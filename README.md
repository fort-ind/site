# Fort.ind

![Fort.ind Logo](https://github.com/user-attachments/assets/eda1c7c8-6a51-423a-8a69-d9fe1ea2bfdb)

The official fort.ind repo

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B5XRQID)

## Welcome to Fort.ind

> [!NOTE]
> This git is still unfinished, and most things are from Fort.ind is not here yet

## screenshots 🖼️

![Screenshot 2025-12-22 113221](https://github.com/user-attachments/assets/0712fe55-bec9-4e44-9970-949d868f0c80)

![image](https://files.catbox.moe/cm53ty.png)

## So what's the site all about? :o

fort.ind is a website made by nerds, silly people, and so on. We do a range of things, from maintaining a large collection of unblocked games to running our own fedi instance! and hosting many cool things from time to time :3

## What's coming? ✨

Everything here is done! If you've got ideas, please open an issue :P

- [x] finish fort.social instance 
- [X] fix bugs
- [X] add more flash games
- [X] read your guys' ideas posted in [the form](https://forms.gle/K14hXqdQjfksyQnA8)
- [x] rebuild the desktop app from the ground up
- [x] integrate a new CDN that isn't blocked and makes games load faster

## Development 🛠️

Built with [Eleventy](https://www.11ty.dev/) (based on [eleventy-high-performance-blog](https://github.com/google/eleventy-high-performance-blog)).

```
npm install
npm run watch   # local dev server with live reload
npm run build   # full production build into _site/
```

### Repo layout

| Path | What it is |
| --- | --- |
| `pages/` | Site pages with explicit permalinks (archive, tags, sitemap, favicon, …) |
| `index.njk`, `about/` | Home and about pages |
| `_includes/` | Layouts and partials |
| `_data/` | Global site data (`metadata.json`, CSP, analytics) |
| `_11ty/` | Custom Eleventy plugins (image optimization, CSP, JSON-LD, HTML minify) |
| `css/`, `js/`, `fonts/`, `img/` | Static assets (`js/min.js` is built by Rollup from `src/main.js`) |
| `api/` | Vercel serverless functions |
| `feed/` | Atom/JSON feed templates |
| `scripts/` | Maintenance scripts |
| `third_party/` | Vendored `eleventy-plugin-local-images` |
| `site/generated-artifacts/` | Generated site artifacts — do not edit by hand |
