# GAA Pitch Size Calculator

A static webpage that suggests GAA pitch dimensions based on the number of
players. The calculator scales the official full-size pitch dimension ranges
proportionally to a 15-player team. For example, a team of half the size gets
half of each full-size dimension range.

The full-size reference is 80–90 metres wide and 130–145 metres long, as stated
in the [GAA Official Guide (page 4)](https://www.gaa.ie/api/images/image/upload/prd/v7cjvfyfh6kdadozonrx.pdf).
Smaller-team dimensions are estimates derived from those ranges, not separate
official GAA dimensions. Decimal player counts are accepted for proportional
estimates (for example, 7.5 players is half of a full team).

## Run locally

Open `index.html` in a browser. No build step or dependencies are required.

## GitHub Pages

In the repository's GitHub settings, enable Pages and deploy from the `main`
branch and root (`/`) folder. GitHub Pages will serve `index.html` as the site
homepage.
