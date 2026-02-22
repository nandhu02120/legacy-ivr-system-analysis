# DAY 12 — DevConf Optimization Demo

How to preview

1. Open `DAY 12/index.html` in a browser, or run a simple local server:

```bash
cd "DAY 12"
python -m http.server 8000
# then open http://localhost:8000
```

What this folder contains
- `index.html` — semantic HTML example with accessible controls and logical heading order.
- `styles.css` — refactored OOCSS using CSS variables and performance-friendly animations.
- `audit-report.md` — summary of the changes and further recommendations.

Quick validation
- Run Lighthouse in Chrome DevTools for performance and accessibility scores.
- Use `axe` or `pa11y` for automated accessibility checks.

If you want, I can:
- Replace placeholders with optimized `srcset` images.
- Integrate a build step (minify CSS, critical CSS extraction).
