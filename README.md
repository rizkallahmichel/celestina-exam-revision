# Celestina AD Exam Revision Website

This is a static HTML project containing the full methodology for the Celestina Active Directory exam.

## Files

- `index.html` — main website
- `style.css` — design and responsive layout

## Run locally

```bash
cd celestina_exam_html_project
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deploy on GitHub Pages

```bash
git init
git add .
git commit -m "Celestina exam revision website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/celestina-exam-revision.git
git push -u origin main
```

Then:

GitHub → Settings → Pages → Deploy from branch → main → root.
