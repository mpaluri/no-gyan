# No Gyan

A lightweight GitHub Pages site for short essays by Manohar Paluri.

## Publish

Create a public GitHub repository named `no-gyan`, then from this folder:

```bash
git init
git add .
git commit -m "Launch No Gyan"
git branch -M main
git remote add origin git@github.com:mpaluri/no-gyan.git
git push -u origin main
```

In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save**.

The site will publish at:

`https://mpaluri.github.io/no-gyan/`

## Add a new essay

1. Copy an existing numbered post folder, e.g. `02-adapting-the-hiring-bar`.
2. Rename it, e.g. `03-precision-over-perfection`.
3. Edit its `index.html`.
4. Add a card for it near the top of the `.posts` section in root `index.html`.
5. Commit and push. GitHub Pages republishes automatically.

There is intentionally no build system or dependency: plain HTML + one CSS file.
