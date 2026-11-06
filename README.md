# Kalkallo Maps

Doorknock maps for the Kalkallo district, served with GitHub Pages.

- `index.html`: home page
- `progress.html`: District Progress (share knocked, share answered, volunteer-adjusted support)
- `projections.html`: Map Projections (expected support for unknocked homes, ranked across the district or within suburb)
- `timeline.html`: Campaign Timeline (doors knocked each week and in total, with projections)

Each page is self-contained and uses Leaflet with OpenStreetMap tiles. The pages hold per-map totals only, with no names or addresses. They are regenerated from the analysis pipeline whenever new knock data comes in.
