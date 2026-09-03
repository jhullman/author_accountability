# author_accountability

A one-page website hosting the **Reviewer Commitment to Authorial Accountability**.

## Contents

- `index.html` — the whole site. Self-contained: no build step, no dependencies, no external requests.

## Publishing with GitHub Pages

1. Repo **Settings → Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main`, folder `/ (root)`

The site is then served at `https://<owner>.github.io/author_accountability/`.
To use a custom domain, add a `CNAME` file at the repo root containing the domain,
and point the DNS at GitHub Pages.

## Editing

Everything — text, styles, and the copy-to-clipboard script — lives in `index.html`.
Open it in a browser to preview locally.

Line length is controlled by one variable, `--measure` (currently `41rem`) near the top
of the `<style>` block. Raise or lower it to widen or narrow the text column.

The "Suggested response" link points at `./`, i.e. the page itself. Once the site has a
final URL, consider making it absolute so the text survives being pasted into an email.
