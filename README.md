# Prajakta Limbore - Portfolio Website

A personal portfolio website modeled on a clean single-page Bootstrap layout (iPortfolio style), tailored to Prajakta Limbore's career story. Built with plain HTML, CSS and a little JavaScript - no build step required.

## Folder structure

```
prajakta-portfolio/
├── index.html
├── README.md
└── assets/
    ├── css/style.css
    ├── js/main.js
    └── img/
        ├── profile.svg   (replace with your own photo: profile.jpg/.png)
        └── portfolio/    (add project screenshots here)
```

## Preview locally

Just open `index.html` in your browser, or run a quick server:

```bash
cd prajakta-portfolio
python -m http.server 8000
# then visit http://localhost:8000
```

## Host on GitHub Pages (like your friend's site)

1. Create a new GitHub repository. Name it either:
   - `prajakta-limbore.github.io` (user site, served at `https://prajakta-limbore.github.io`), or
   - any name like `portfolio` (project site, served at `https://<username>.github.io/portfolio`).

2. Copy everything inside this folder into the repo (the repo root should contain `index.html`).

3. Commit and push:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

4. Enable GitHub Pages: Repository -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main` / folder `/ (root)` -> Save.

5. Wait a minute; your site will be live at the URL shown.

## Customise

- Replace `assets/img/profile.svg` with a real photo (update the `src` in `index.html` if you change the filename).
- Add project screenshots to `assets/img/portfolio/` and reference them in the Impact section.
- Update links (resume PDF, etc.) as needed.
- Edit text in `index.html`; styles in `assets/css/style.css`.

## Credits

Layout inspired by the BootstrapMade "iPortfolio" template. Icons by Bootstrap Icons. Fonts by Google Fonts.
