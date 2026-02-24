# heyhinano.com

Standalone GitHub Pages site for Hinano portfolio.

## DNS setup
At your domain provider for `heyhinano.com`:

- `A` records for apex (`@`) to:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `CNAME` for `www` -> `nissmogt.github.io`

Then in GitHub repo settings:
- Pages source: `main` / root
- Custom domain: `heyhinano.com`
- Enable `Enforce HTTPS` after DNS propagates.

