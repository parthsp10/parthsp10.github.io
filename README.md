# Parth Patel | Portfolio

Personal portfolio for Parth Patel, a CS graduate student at SIUE seeking a Summer 2027 internship in Data Science and AI/ML Engineering.

**Live site:** https://parthsp10.github.io/

## Tech

- Vanilla HTML, CSS and JavaScript
- Hosted on GitHub Pages
- No framework, no bundler, no build step

## Design and accessibility decisions

- **Mobile navigation:** a toggle button with `aria-expanded`, closes on link click, on Escape, and when the viewport grows to desktop width.
- **Reduced motion:** scroll-reveal animations are skipped when `prefers-reduced-motion` is set, and content stays visible if JavaScript is unavailable.
- **Contrast:** light text on a dark background, with secondary text colors chosen to stay readable.
- **Semantic HTML:** landmarks (`nav`, `main`, `footer`), a skip link, one `h1`, lists for grouped content, and descriptive alt text.
- **Optimized assets:** a small WebP profile image with a JPEG fallback, explicit image dimensions, an SVG favicon, and Open Graph metadata for link previews.

## Run locally

```
python -m http.server
```

Then open http://localhost:8000/.
