# The Refugee Bureau · Data

Public charts for The Refugee Bureau, served by GitHub Pages at https://data.refugeebureau.org (the `CNAME` file sets the custom domain; keep it when copying `site/` here).

- `index.html`: the landing page
- `charts/refugee-admissions/`: the interactive admissions chart and its link-preview image

The chart is generated, not hand-edited. In the explainer build, run `python3 interactive/build.py --site https://data.refugeebureau.org`
after `data/extract.py` and `verify.py`, then copy `site/` here.
