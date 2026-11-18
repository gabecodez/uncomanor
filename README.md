# The Uncomanor — The Archive

A short history of **The Uncomanor** (2020–2022), the independent
Pennsylvania news publication I founded as a teenager. It covered news,
politics, the internet, crypto, culture, and whatever else the news cycle
dragged in. It gathered more than 120,000 page views before it stopped
publishing.

The domain `uncomanor.com` now points here. This repository is the whole site:
plain HTML, CSS, and a few kilobytes of fonts. No framework, no build step,
no analytics, no ads.

## What is here

| File | Purpose |
| --- | --- |
| `index.html` | The history, masthead, headlines, and archive links |
| `style.css` | Newsprint-inspired design, responsive layout, print styles |
| `404.html` | A small archival 404 |
| `CNAME` | Points GitHub Pages at `uncomanor.com` |
| `assets/` | The original publication mark and self-hosted fonts |
| `robots.txt`, `sitemap.xml` | Basic crawler metadata |

## Preview locally

```bash
python3 -m http.server 8080
```

Then open <http://localhost:8080>. Opening `index.html` directly also works.

## Publish

This repo is intended to deploy with GitHub Pages from the `main` branch,
root folder. The `CNAME` file tells Pages to serve it at `uncomanor.com`.
In the domain's DNS settings, point the apex `A` records at GitHub Pages and
`www` at `gabecodez.github.io`.

## Sources

The history and quoted material come from archived captures of
`uncomanor.com` in the Internet Archive, the publication's Medium page, and
public project notes. Headlines are reproduced from the archive.

— Gabe Sullivan
