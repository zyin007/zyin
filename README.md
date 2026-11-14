# Zihan Yin · portfolio site

Plain HTML/CSS/JS, no build step. Open `index.html` or host the folder anywhere.

## Two versions, one site
- Research version: `…/index.html?v=research` (default)
- Commercial version: `…/index.html?v=commercial`

Each version reorders the sections and swaps the hero, about, experience and closing copy.

Visitors can also flip between them with the "Lens" switch in the nav.
Version-specific text sits in elements marked `data-only="research"` or `data-only="industry"`.
Section order is set by `--r` (research) and `--i` (commercial) on each `<section>`.
`?v=internship` still works and maps to the commercial version.

## Research section
Four project cards; the synthetic biology / iGEM one spans the full width above the other three (`.page.wide`).

## No contact details
The site deliberately carries no email, no LinkedIn and no CV. The closing section states
research interests instead of asking for work. If you want to be contactable later, add the
details back to the `#interests` section.

## To fill in (search for `TODO` in index.html)
- Link to the Bioscience Review article

## Publish free on GitHub Pages
1. Create a repo (e.g. `zihanyin.github.io`) and upload everything in this folder.
2. Go to Settings → Pages → Deploy from branch → `main` / root.
