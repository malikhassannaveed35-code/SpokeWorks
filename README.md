# Spokeworks - 5-page website (HTML5 + Tailwind CSS)

Pages: index.html, about.html, contact.html, signin.html, signup.html

## Run locally
Open `index.html` in a browser (needs internet for the Tailwind CDN and Google Fonts), or use the VS Code Live Server extension.

## Contact form (required setup)
1. Create a free form at https://formspree.io
2. Copy your form ID (e.g. `xyzabcde`)
3. In `contact.html`, replace `YOUR_FORM_ID` in the form `action` URL.

## Deploy
Push to GitHub, then enable GitHub Pages (Settings > Pages > main branch / root), or drag the folder onto Netlify.

## Structure
```
spokeworks/
  index.html  about.html  contact.html  signin.html  signup.html
  assets/
    css/custom.css
    img/favicon.svg  hero-bike.svg
  README.md
```
