# gregweinstein.art

The website for Greg Weinstein's hand-cut collage work.

## How this is built

This folder is generated, not hand-edited. The source lives in the Cowork
project at `Projects/Collage Art Website/`:

- `mockup/artifact-src.html` — the page itself, with `__IMG_name__` placeholders
- `mockup/img_zoom/`, `mockup/img_about/` — the photographs
- `build-site.py` — writes this folder

To change the site, edit the source and re-run:

    python3 "Projects/Collage Art Website/build-site.py"

then commit and push from here. Editing `index.html` in this repo directly will
be overwritten by the next build.

## Hosting

GitHub Pages, served at https://gregweinstein.art
