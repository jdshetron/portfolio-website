# John Shetron — Portfolio Website

A static, resume-driven personal portfolio site plus a mobile-first links page.

## Structure

- `index.html` — main portfolio (hero, about, education, skills, experience, projects, resume, contact)
- `links.html` — Linktree-style mobile links page
- `styles.css` — shared design system (light/dark aware)
- `script.js` — mobile nav toggle, scroll-reveal animations
- `assets/` — resume files (PDF + docx)

No build step — plain HTML/CSS/JS.

## Editing

All content is sourced from `2026 Resume.docx`. To update the site after a resume change:

1. Replace `assets/John_Shetron_Resume.pdf` and `assets/John_Shetron_Resume.docx`.
2. Update the corresponding text in `index.html` and `links.html`.

Placeholders for LinkedIn/GitHub/portfolio links are commented out in both HTML files (search for `Add more links` / `Add LinkedIn`) — uncomment and fill in once those exist.

## Deploying to GitHub Pages

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

Then in the GitHub repo: **Settings → Pages → Source: Deploy from branch → main / (root)**.
The site will be live at `https://<username>.github.io/<repo-name>/`.
