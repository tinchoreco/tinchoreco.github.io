# TWC Research Site

Personal academic website for Martín Nicolás Nardelli's research on computational economics.

## Deploying to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. Create a new repository on GitHub named `tinchoreco.github.io`
2. Clone it locally:
   ```bash
   git clone https://github.com/tinchoreco/tinchoreco.github.io.git
   ```
3. Copy all files from this folder into the repository
4. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial site"
   git push origin main
   ```
5. Your site will be live at: `https://tinchoreco.github.io`

### Option 2: Project Site

1. Create a new repository (e.g., `twc-research`)
2. Push the code
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose `main`
5. Site will be at: `https://tinchoreco.github.io/twc-research`

## Structure

```
├── index.html          # Main page
├── css/
│   ├── style.css       # Main styles
│   └── article.css     # Article page styles
├── articles/
│   ├── maxwell-demon.html
│   ├── classical-error.html
│   ├── perpetual-motion.html
│   ├── double-entry.html
│   └── science-computation.html
└── README.md
```

## Adding New Articles

1. Copy `articles/maxwell-demon.html` as a template
2. Update the title, content, and meta information
3. Add a link in `index.html` under the articles section

## Adding New Papers

Edit `index.html` and add a new `<article class="paper">` block in the papers section.

## Customization

- Colors and fonts: Edit CSS variables in `css/style.css`
- Layout: Modify the HTML structure in `index.html`
- Fonts: Currently using Google Fonts (Crimson Pro + JetBrains Mono)

## License

Content © 2026 Martín Nicolás Nardelli
