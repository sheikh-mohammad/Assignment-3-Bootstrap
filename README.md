## Assignment 3 — Bootstrap Responsive Recipe UI

Modern, responsive landing page built with Bootstrap 5 for a recipe/food theme. It showcases hero sections, featured recipes, dishes, and a clean footer, using a custom `PT Sans` typeface and a tidy component structure.

— by [sheikh-mohammad](https://github.com/sheikh-mohammad)

### Live Demo

View the site on GitHub Pages: [sheikh-mohammad.github.io/Assignment-3-Bootstrap](https://sheikh-mohammad.github.io/Assignment-3-Bootstrap/)

Repository: [`sheikh-mohammad/Assignment-3-Bootstrap`](https://github.com/sheikh-mohammad/Assignment-3-Bootstrap)

### Features

- **Responsive layout**: Mobile-first design using Bootstrap’s grid, utilities, and components.
- **Semantic HTML**: Clear sections for hero, featured, recipes, and footer.
- **Custom typography**: Bundled `PT Sans` Regular and Bold fonts.
- **Asset organization**: Structured images for dishes, hero, featured, and recipes.
- **Lightweight**: Pure HTML/CSS with Bootstrap; no build step required.

### Tech Stack

- **HTML5** for structure
- **CSS3** with a custom `style.css`
- **Bootstrap 5** utilities and components

### Project Structure

```
assets/
  fonts/
    PTSans-Bold.ttf
    PTSans-Regular.ttf
  images/
    dishes/
      dish-1.png ... dish-5.png
    featured recipe/
      image-1.png, image-2.png
    footer/
      logo.png
    hero recipe/
      col-1-image-1.png, col-1-image-2.png
      col-2-image-1.png
      col-3-image-1.png, col-3-image-2.png
    logos/
      yummy-logo.png
    recipes/
      col-1-image-1.png
      col-2-image-1.png ... col-2-image-4.png
index.html
style.css
```

### Getting Started (Local)

1. **Clone** the repo
   ```bash
   git clone https://github.com/sheikh-mohammad/Assignment-3-Bootstrap.git
   cd Assignment-3-Bootstrap
   ```
2. **Open** `index.html` directly in your browser, or use an HTTP server (recommended):
   - With VS Code Live Server: Right-click `index.html` → “Open with Live Server”.
   - Or with Python:
     ```bash
     # Python 3
     python -m http.server 5500
     # Then visit http://localhost:5500
     ```

### How It’s Organized

- Global styles and overrides live in `style.css`.
- Bootstrap classes provide layout, spacing, and responsiveness.
- Image assets are split by feature area for clarity and easy maintenance.
- Custom fonts are pre-bundled to avoid external calls and ensure consistent rendering.

### Customization Tips

- Replace images in `assets/images/*` with your own while keeping file names to avoid HTML updates.
- Update color scheme and spacing in `style.css` using CSS variables or utility overrides.
- Swap typefaces by placing new font files in `assets/fonts/` and updating `@font-face` rules.

### Contributing

Contributions are welcome! For small changes, feel free to open a pull request.

1. Fork the repo
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push and open a PR

### Credits

- Repository and implementation by **@sheikh-mohammad**
- Images and fonts included locally for educational/demo purposes

### Links

- GitHub Repository: [`https://github.com/sheikh-mohammad/Assignment-3-Bootstrap`](https://github.com/sheikh-mohammad/Assignment-3-Bootstrap)
- Live Demo: [`https://sheikh-mohammad.github.io/Assignment-3-Bootstrap/`](https://sheikh-mohammad.github.io/Assignment-3-Bootstrap/)


