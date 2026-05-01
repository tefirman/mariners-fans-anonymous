# mariners-fans-anonymous

League site for the Mariners Fans Anonymous Fantasy Football League.

The by-laws live in [`docs/bylaws.md`](docs/bylaws.md) and are published as a static site via MkDocs Material + GitHub Pages.

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000.

## Deployment

The site auto-deploys to GitHub Pages on every push to `main` via `.github/workflows/deploy.yml`.

To enable: in the repo's **Settings → Pages**, set **Source** to **GitHub Actions**.
