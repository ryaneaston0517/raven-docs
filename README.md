# raven-docs

Documentation for **Raven AI** — served at **[docs.ravenintelligence.ai](https://docs.ravenintelligence.ai)** via GitHub Pages.

Currently a placeholder (`index.html` only). Real documentation will ship here as it's written.

## Stack

- Plain static HTML, served directly by GitHub Pages
- No build step, no framework
- Custom domain configured via the `CNAME` file + a `CNAME docs → ryaneaston0517.github.io` record in GoDaddy
- `.nojekyll` disables Jekyll preprocessing so files are served verbatim

## Editing

```sh
# Edit index.html locally, commit, push.
# Pages auto-redeploys on every push to main.
git clone https://github.com/ryaneaston0517/raven-docs.git
cd raven-docs
# ...edit...
git add -A
git commit -m "docs: update landing page"
git push
```

## Related

- [`ravenai-site`](https://github.com/ryaneaston0517/ravenai-site) — marketing site at [ravenintelligence.ai](https://ravenintelligence.ai). Shared brand palette (`raven-black` / `raven-navy` / `raven-red` / `raven-blue`) and Fraunces + Inter typography. Keep this placeholder visually consistent if you edit it.
