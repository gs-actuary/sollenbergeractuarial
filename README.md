# Sollenberger Actuarial Technologies

Source repository for [sollenbergeractuarial.com](https://sollenbergeractuarial.com/).

The site publishes open-source actuarial software and technical work by Greg Sollenberger, FCAS, CSPA, with a focus on insurance rating, pricing, predictive modeling, and reproducible implementation workflows.

## Projects featured on the site

- [`ratingtables`](https://github.com/gs-actuary/ratingtables) — table-driven insurance rating in R
- [`raterevision`](https://github.com/gs-actuary/raterevision) — reproducible rate-table revision workflows
- [`aglmtools`](https://github.com/gs-actuary/aglmtools) — development-stage tools for interpretable regularized GLMs

Video demonstrations are available on the [Armchair Actuary YouTube channel](https://www.youtube.com/@Armchair-Actuary).

## Website structure

- `index.qmd` — home page
- `software.qmd` — software overview
- `about.qmd` — background and project purpose
- `contact.qmd` — contact information
- `_quarto.yml` — Quarto website configuration
- `styles.css` — site-specific styling
- `CNAME` — custom domain configuration

The rendered website is written to `docs/` for GitHub Pages.

## Local preview

With Quarto installed:

```bash
quarto preview
```

To render the production site:

```bash
quarto render
```
