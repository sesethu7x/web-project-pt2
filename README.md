# Artisan Bakery — Landing Page

Simple static landing page for "Artisan Bakery" (hero, about, menu, order CTA, footer).

## Files
- [index2.html](index2.html) — main HTML (includes embedded images and layout).
- [style.css](style.css) — global styles and variables.
- [.vscode/launch.json](.vscode/launch.json) — VS Code Chrome debug config (Launch Chrome against localhost).

## Preview / Run
1. Open the file directly: open [index2.html](index2.html) in your browser.
2. Or serve on localhost (recommended for Font/Asset loading):
   - Python 3: `python -m http.server 8080`
   - Then open http://localhost:8080 and use the VS Code debug config "Launch Chrome against localhost" in [.vscode/launch.json](.vscode/launch.json).

## Notes
- Uses Google Fonts and Font Awesome (CDN links in head of [index2.html](index2.html)).
- Large inline base64 images are embedded in [index2.html](index2.html) — consider moving them to separate image files for performance.
- Styles in [style.css](style.css) provide theme variables and responsive layout.

## License
Add a license if you plan to publish this project.
