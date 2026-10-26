# Academic Portfolio

Static site (plain HTML + CSS, no build step) for GitHub Pages.

## Edit
- `index.html` – all content.
- `style.css` – styling (light/dark automatic).
- `assets/photo.jpg` – your portrait; `assets/cv.pdf` – your CV.

## Preview locally
```
python -m http.server 8000
```
Open http://localhost:8000.

## Deploy
Create a repo named `<username>.github.io`, push these files to `main`, then
Settings → Pages → Deploy from branch → `main` / root.
