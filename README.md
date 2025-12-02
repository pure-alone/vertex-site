# Vertex Solutions — course website

This repository contains an example group business website built with R Markdown and deployed to GitHub Pages.

Structure:
- `_site.yml` — site configuration (output_dir: docs)
- `index.Rmd`, `about.Rmd`, `team.Rmd`, `projects.Rmd` — pages
- `reflection.Rmd` — the submission reflection document (single-file)
- `.github/workflows/deploy-rmarkdown.yml` — GitHub Actions workflow to render site

To render locally: `Rscript -e 'rmarkdown::render_site(encoding="UTF-8")'`
