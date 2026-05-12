# fabrik-dev-redirect

301-style HTTP redirect from `fabrik.handarbeit.dev` → `fabrik.handarbeit.io`.

This repo serves a single page that meta-refreshes and JS-redirects to the canonical Fabrik marketing site at `https://fabrik.handarbeit.io/`, preserving the path/query/hash so deep links land on the right page.

Why a separate repo: GitHub Pages allows only one custom domain per repo. The primary content lives in [handarbeit/fabrik](https://github.com/handarbeit/fabrik) (`/docs` folder). This repo exists solely to claim `fabrik.handarbeit.dev` as a GitHub Pages custom domain and serve the redirect.

DNS: the `fabrik` subdomain of `handarbeit.dev` is a CNAME → `handarbeit.github.io`.
