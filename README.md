# tejas-goyal.github.io

Personal landing page. Static HTML/CSS, no build step.

- `index.html` — page content
- `style.css` — styling (Newsreader + Inter, slate accent, cream background)
- `Tejas_Goyal_CV.pdf` — linked from the CV button

## Local preview

Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new GitHub repo named exactly `tejas-goyal.github.io` (public).
2. From this folder:

   ```bash
   git init
   git add .
   git commit -m "Initial landing page"
   git branch -M main
   git remote add origin https://github.com/tejas-goyal/tejas-goyal.github.io.git
   git push -u origin main
   ```

3. In the repo: Settings → Pages → Source = `main` branch, `/ (root)`.
4. The site goes live at https://tejas-goyal.github.io within a minute or two.

To update the CV, replace `Tejas_Goyal_CV.pdf` and push again.
