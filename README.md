# vikaskumar.github.io

Academic website scaffold for GitHub Pages using Hugo.

## What is included

- A minimalist academic homepage
- Working papers, teaching, and CV pages
- A built-in local theme in `themes/researcher/`
- GitHub Actions deployment workflow in `.github/workflows/hugo.yaml`

## Before publishing

1. Replace `youremail@example.com` in `hugo.toml` and the content files.
2. Replace `static/img/avatar-placeholder.svg` with your own photo if you want one.
3. Replace `static/files/vikas-kumar-cv.pdf` with your actual CV PDF.
4. Update the text in `content/_index.md` and `content/working-papers.md` as your draft develops.

## Local preview

Install Hugo Extended, then run:

```bash
hugo server
```

Visit `http://localhost:1313/`.

## GitHub Pages setup

1. Create or use the repository named `vikaskumar.github.io`.
2. Push this project to the `main` branch.
3. In GitHub, open `Settings -> Pages`.
4. Set the source to `GitHub Actions`.
5. Push future updates normally; the site will rebuild automatically.

## Optional next step

If you want the exact upstream `ojroques/hugo-researcher` theme later, you can replace the local theme directory with the official submodule after installing Git and enabling network access:

```bash
git submodule add https://github.com/ojroques/hugo-researcher.git themes/researcher
```
