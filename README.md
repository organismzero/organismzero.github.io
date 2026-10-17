# organismzero.github.io

Personal GitHub Pages site, served at https://organismzero.github.io from the `main` branch root.

## Adding a page

Drop any `.html` file (plus its assets) into the repo, commit, and push. It's published at the
same path, e.g. `pages/foo.html` → https://organismzero.github.io/pages/foo.html.

Changes usually go live within a minute or two.

## Notes

- `.nojekyll` disables Jekyll, so files are served exactly as committed (including names starting with `_`).
- `index.html` is the landing page. The avatar uses `https://github.com/organismzero.png`, which always
  redirects to the current GitHub avatar.
- `404.html` is shown for any missing path.
- Everything in this repo is public. Don't commit secrets.
