<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-sodium/brand/main/social/go-ruby-sodium.png" alt="go-ruby-sodium/go-ruby-sodium.github.io" width="720"></p>

# go-ruby-sodium.github.io

The organization's institutional landing page, served at
<https://go-ruby-sodium.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-sodium/docs](https://github.com/go-ruby-sodium/docs), served at
<https://go-ruby-sodium.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
