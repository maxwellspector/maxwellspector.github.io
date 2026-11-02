# maxwellspector.com

Personal site of Maxwell Spector. A single static page (`index.html`, no build step) served by GitHub Pages.

## Waterline

Scroll to row a single scull down the Willamette, from the Lake Oswego Railroad Bridge to the Broadway Bridge in downtown Portland. Each bridge opens a chapter of the career.

- **The boat** is drawn on a `<canvas>` from a model of the rowing stroke: real single-scull dimensions, legs-body-arms sequencing, oar angle derived from hand position, feathered vs. squared blades, and puddles spaced one stroke's run apart. Stroke phase is tied to scroll distance.
- **The river** minimap and bridge distances come from OpenStreetMap (`design/willamette-reach.json`). © OpenStreetMap contributors, ODbL.
- **Type:** Anton and Work Sans from Google Fonts.
- Respects `prefers-reduced-motion` (the rower sits easy and does not animate).

`design/` holds working material: the original storyboards and the river geometry.
