# Carly Ravitz Tutoring

Simple static one-pager for Carly's tutoring services. No build step.

## Setup
1. Drop the photo as `carly.jpg` in this folder (next to `index.html`).
2. Open `index.html` in a browser to preview.

## Deploy

### GitHub
```
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<you>/carly-tutoring.git
git push -u origin main
```

### Vercel
- Import the repo at https://vercel.com/new → Framework Preset: **Other** → Deploy.
- No build command, no output dir overrides needed (it's static).

## Customize
- Email link: edit the `mailto:` in `index.html` under the Contact section.
- Colors: tweak the `--accent` variables at the top of `styles.css`.
