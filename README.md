# Mornfolk site (GitHub Pages)

Static pages for App Store Connect: landing, privacy, terms, support.

Pattern matches Lanternway: `https://n2welike.github.io/lanternway/`.

## Planned public URLs

- https://n2welike.github.io/mornfolk/
- https://n2welike.github.io/mornfolk/privacy/
- https://n2welike.github.io/mornfolk/terms/
- https://n2welike.github.io/mornfolk/support/

## Publish

From a GitHub repo named `mornfolk` under `n2welike` (or this monorepo with Pages root = `/site`):

1. Push `site/` to `gh-pages`, **or** enable Pages → Deploy from branch → folder `/site`.
2. Confirm the four URLs open over https.
3. Keep `release/app.env` pointing at privacy/terms URLs.

Local preview:

```sh
cd site && python3 -m http.server 8765
# open http://127.0.0.1:8765/
```
