# Emotion Wheel

An interactive emotion wheel: start from a core emotion at the centre and step
outward ring by ring to name a more precise feeling. A side panel tracks your
selection with breadcrumbs, a definition, and a reset.

It is a single, self-contained static page — the only external dependency is
Google Fonts, loaded at runtime.

## Files

- `index.html` — the deployable page (served at the site root).
- `emotion-wheel.html` — identical source, kept under its original name.

## Local preview

Open the file directly in a browser:

```sh
open index.html
```

## Hosting (Cloudflare Pages)

Connect this repo to a Cloudflare Pages project with:

- **Build command:** none
- **Deploy command:** none
- **Build output directory:** `/`

Pages then serves `index.html` at the root URL.
