# Christine Nicole Tecson — Portfolio

Simple static portfolio site.

## Overview
This repository contains a small static site (HTML, CSS, assets) that showcases Christine Nicole Tecson's work. The important files are:

- `index.html` — main page
- `style.css` — site styles
- `assets/` — images and PDFs (photo, resume, certificates)

## Preview locally
Open PowerShell, change to the folder containing this README and run a local server:

```powershell
cd C:\Users\christine\Downloads
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

If `python3` isn't available, install Python or use another static server (Node, Live Server extension, etc.).

## Deploy to GitHub
1. Create a new GitHub repository (do NOT upload your entire Downloads folder — only site files).
2. From this folder run:

```powershell
git init
git add index.html style.css assets README.md
git commit -m "Initial site commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. Enable GitHub Pages in the repo settings (choose branch `main` and folder `/ (root)`).

## File structure
```
index.html
style.css
assets/
  ├─ christine-photo.jpg
  ├─ Christine_Tecson_Resume.pdf
  ├─ Wadhwani_Ignite_Certificate.pdf
  └─ CertificateforVA.pdf
```

## Notes
- Keep the `assets/` folder next to `index.html` so paths like `assets/christine-photo.jpg` work.
- Do not commit unrelated personal files from `Downloads`.

## Contact
If you want, I can initialize the git repo and push these files for you once Git is installed and you provide the remote URL.