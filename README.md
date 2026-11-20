# Jiahong Chen

[Visit the portfolio](https://jh13c.github.io/)

## Preview and build

Install [Quarto](https://quarto.org/docs/get-started/) (the deployment uses
version 1.10.18). From the root of this repository, run:

```sh
quarto preview
```

Run `quarto render` to generate the static site in `_site/`. The
homepage is `index.qmd`. The stylesheet, portrait, and résumé are in
`assets/`. Quarto is the only build dependency.

## Publish

In the repository's **Settings → Pages**, set **Source** to **GitHub Actions**.
The workflow renders and deploys the site on pushes to `main`. To redeploy
the current version, run **Publish Quarto site** from the **Actions** tab.
