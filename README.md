# Shajahan Shaik | Portfolio

Personal portfolio for a Production & Application Support Engineer. Pure HTML, CSS and JavaScript with no build step, so it deploys to GitHub Pages as-is.

## Deploy to GitHub Pages (about 3 minutes)

1. Create a new repository on GitHub. For a clean URL, name it `<your-username>.github.io`.
2. Upload everything in this folder (or push it):

   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Add portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. On GitHub open **Settings, Pages**. Under **Build and deployment** set Source to **Deploy from a branch**, Branch to `main` and folder to `/ (root)`, then Save.
4. After about a minute your site is live at `https://<your-username>.github.io/` (or `https://<your-username>.github.io/<repo-name>/` for other repo names).

## Customize

| What | Where |
| --- | --- |
| Text, experience, projects | `index.html` |
| Colors, fonts, spacing | `:root` variables at the top of `css/style.css` |
| Behavior (theme, animations) | `js/main.js` |
| Browser tab icon | `favicon.svg` |

## Optional: add a downloadable resume

Put your PDF in the repo (for example `assets/Shajahan_Shaik_Resume.pdf`) and add this inside the hero buttons in `index.html`:

```html
<a href="assets/Shajahan_Shaik_Resume.pdf" class="btn btn--ghost" download>Download resume</a>
```

## Features

- Light and dark theme (follows system preference, remembers your choice)
- Fully responsive with a mobile menu
- Scroll animations, count-up stats and active-section highlighting
- Respects reduced-motion settings; print-friendly
- SEO and social-share meta tags
