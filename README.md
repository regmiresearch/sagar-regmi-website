# Sagar Regmi, PhD: Personal Academic Website

Static site (HTML and CSS only), ready for GitHub Pages.

## Folder layout

```
personal-website/
├── index.html          Main page (Research, Publications, Teaching, People, CV, Contact)
├── css/
│   └── style.css       Styles
├── assets/
│   ├── sagar-regmi.jpg Photo of Sagar Regmi (add this file)
│   ├── jaxon-lay.jpg   Photo of Jaxon Lay (add this file)
│   └── cv.pdf          Current CV (add this file)
└── README.md
```

## Preview locally in VS Code

1. Open the `personal-website` folder in VS Code.
2. Install the "Live Server" extension (by Ritwick Dey).
3. Right-click `index.html` and choose **Open with Live Server**.

## Publish on GitHub Pages

1. Create a new public repository on GitHub, for example `sagar-regmi-website`.
2. In VS Code's terminal, run:
   ```
   git init
   git add .
   git commit -m "Initial website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/sagar-regmi-website.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then save.
4. The site will be available at `https://<your-username>.github.io/sagar-regmi-website/`.

## Updating

Edit `index.html` or `css/style.css`, commit, and push. GitHub Pages updates within a few minutes.
