# Opilan — Coming Soon

A static "coming soon" landing page for **Opilan**, an Amsterdam-based leather goods
brand (bags, pouches, cardholders, and more). Built with plain HTML/CSS/JS so it can
be hosted directly on GitHub Pages.

## Structure

- `index.html` - landing page markup
- `css/styles.css` - styling
- `js/main.js` - footer year + notify form interaction
- `opilan_logo.svg` - brand logo

## Local preview

Open `index.html` directly in a browser, or serve the folder with any static
server, e.g. `npx serve .`.

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, open **Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then save.
5. The site will be published at `https://<username>.github.io/<repo>/`.

## Notes

- The notify form currently only shows a confirmation message client-side.
  Wire `js/main.js` up to a real signup service (Mailchimp, Formspree, etc.)
  before launch.
- Update the Instagram/email links in `index.html` with the brand's real
  accounts.
