# Klarkx

Public site for klarkx.com, published by Sparta Labs.

Hosted on Cloudflare Pages from this repository.

## New pages

This repo has no page generator. New article pages are copied from a live article (for example `/stocking-stuffer-games/` or `/game-night-gift-basket/`). Every public page must include a self-referencing canonical in `<head>`, with https and a trailing slash (the home page is `https://klarkx.com/`):

```html
<link rel="canonical" href="https://klarkx.com/<path>/" />
```

Do not add a canonical to `google6586653657b36282.html`.

