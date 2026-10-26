# Megharaj G Mogaveer — Portfolio

A responsive, single-page professional profile for GitHub Pages. The site includes a direct PDF download of the 2026 resume in `assets/`.

Live site: [https://meghxraj.github.io/](https://meghxraj.github.io/)

## Repository and deployment

This site is published from the public [`meghxraj.github.io`](https://github.com/meghxraj/meghxraj.github.io) repository. GitHub Pages is configured to deploy with GitHub Actions.

To update the site, edit the files in this repository and push the `main` branch. The workflow publishes `index.html`, `styles.css`, and `assets/`; its run summary shows the deployment status.

The resume PDF is a public download when this site is public. To update it later, replace the file in `assets/` and keep the same filename, or update both resume links in `index.html`.

## Files

- `index.html` — profile content and metadata
- `styles.css` — responsive layout and visual styling
- `assets/Megharaj_G_Mogaveer_Resume_2026.pdf` — downloadable resume
- `.github/workflows/pages.yml` — deployment workflow
