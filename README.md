# Responsive Blog — Bootstrap Project

A minimal, static responsive blog layout built with Bootstrap 5. This repo is intended as a starter/template for a simple blog or news site and is ready to be customized and expanded.

Main entry: `index.html` — a responsive landing page showing a navbar (with an offcanvas mobile menu), hero/slider area, lists of articles, a categories sidebar, and a footer.

## Project contents

- `index.html` — main demo page.
- `search.html`, `article.html` — placeholder pages for search and article views (if present).
- `assets/`
  - `vendor/bootstrap/` — local Bootstrap CSS & JS used by the template.
  - `style/style.css` — project custom styles.
  - `images/` — image assets (logo, thumbnails).

## Technologies

- Bootstrap 5 (local files)
- Font Awesome (CDN)
- Google Fonts (Montserrat via CDN)
- Plain HTML & CSS (no build step required)

## Preview locally

Open `index.html` directly in a browser, or run a simple static server for a better dev experience:

Python 3:

```bash
# from the project root
python3 -m http.server 8000
# open http://localhost:8000
```

Node (http-server):

```bash
# install once (if needed)
npm install -g http-server
# from the project root
http-server -c-1
# open the printed URL (e.g. http://localhost:8080)
```

## Customization notes

- The page uses placeholder content and visual blocks for images (CSS class `card-color`). Replace these with real content and proper `<img>` elements.
- Update navigation links and offcanvas content to reflect your site's structure.
- The search input in the template is not wired to a search implementation — you can implement client-side filtering or submit to `search.html`.
- Font Awesome and Google Fonts are loaded via CDN; host locally if you need offline availability or tighter control.

## Contributing

This project is a simple template. If you'd like to contribute improvements (fixes, accessibility, or small features), feel free to open a PR. For major changes consider opening an issue first to discuss the approach.

## License

This repo is provided for learning and demonstration purposes.
