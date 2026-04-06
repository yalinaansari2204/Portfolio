# Yalina Ansari Portfolio

Static portfolio website for resume, experience, skills, and projects.

## Folder Structure

All files are in a single folder root (`Portfolio`) for easy GitHub upload.

- `index.html` - Main homepage
- `styles.css` - Global styles
- `script.js` - Small JavaScript (footer year)
- `envi-safe-tech.html` - Project webpage
- `iot-energy-optimisation.html` - Project webpage
- `envi-safe-tech-genuine.png` - Project image
- `iot-energy-genuine.png` - Project image

## Run Locally

Open `index.html` directly, or run a local server:

```bash
python -m http.server 5500
```

Then open `http://localhost:5500`.

## Deploy on GitHub

1. Upload the full `Portfolio` folder contents to a GitHub repository.
2. Keep all files in the repository root as provided.
3. Enable GitHub Pages:
   - Repository Settings -> Pages
   - Source: Deploy from a branch
   - Branch: `main` (root)
4. Save and wait for deployment.

All paths are relative, so the site works correctly on GitHub Pages.
