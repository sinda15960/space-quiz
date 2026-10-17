# Project rules

- Keep the quiz self-contained in `index.html`; do not add servers, build steps, or dependencies unless explicitly requested.
- Keep HTML, CSS, and JavaScript clearly separated and formatted consistently within the file.
- Use descriptive names and small functions with one clear responsibility. Avoid duplicated logic and unnecessary abstractions.
- Keep quiz questions as data, separate from rendering and interaction logic.
- Use semantic HTML, accessible labels and focus states, and respect reduced-motion and color-scheme preferences.
- Insert dynamic text with `textContent` rather than treating user- or data-provided strings as HTML.
- Preserve responsive behavior and existing quiz features when making changes.
- Verify interaction changes in the browser, including keyboard focus, scoring, feedback, and results.
