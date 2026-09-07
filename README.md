# mule-fuel-x-nana-glue-dashboard-legacy

Archived static HTML dashboard for the **Mule Fuel x Nana Glue** breeding project.

## What this is

This repo holds the *legacy* hand-generated dashboard that used to live alongside
the breeding data in `joeydouglas/mule-fuel-x-nana-glue`. It was split out
(NICK-701) so that the original repo can be a pure **data** repo:

- `joeydouglas/mule-fuel-x-nana-glue` — canonical data (`project.md`, `plants/<ID>.md`),
  read by `breeding-data-api`. This is what the live pipeline writes to.
- `joeydouglas/mule-fuel-x-nana-glue-dashboard-legacy` (this repo) — frozen HTML snapshot.

## Contents

- `index.html` — dashboard index page
- `style.css` — dashboard styles
- `plants/MG*.html` — per-plant HTML pages (45 files)

## Status

**Frozen / archival.** Nothing writes here automatically. GitHub Pages is not
enabled. The generated HTML is a point-in-time snapshot and will drift from the
markdown data in the data repo; treat the markdown as the source of truth.
