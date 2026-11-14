# Nashik demo sites

Live index: **https://swarajpatil-tech.github.io/nashik-demos/**

39 demo websites, built for local businesses in Nashik that either had no website or a domain in their Instagram bio that no longer loaded. Each demo is a real, working site for that specific business, not a template with a placeholder name.

## Who they're for

Chartered accountants, advocates, dental and physiotherapy clinics, architects, interior designers, gyms and fitness studios, event and wedding planners, UPSC/MPSC coaching academies, tax consultants.

## How it's built

- `index.html` — the gallery, one card per demo, filterable.
- `manifest.json` — metadata for every demo: business name, category, folder, theme.
- `demos/<slug>/index.html` — one self-contained site per business. Inline CSS and JS, no framework, no build step, no dependencies.

Slugs carry a short hash suffix (`ca-kiran-zade-and-associates-d22e0e`) so two businesses with similar names never collide.

## Adding a demo

1. Drop the site into `demos/<slug>/`.
2. Add its entry to `manifest.json`.
3. The gallery picks it up. GitHub Pages serves the rest.

## Honest note

The photography inside each demo is stock, standing in for the business's own photos. Copy is drafted from public listings, so a real handover means a pass from the owner.
