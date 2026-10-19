# Cuicani website

A buildless, responsive marketing site for Cuicani. HTML and CSS only, with local assets and no website analytics, cookies, fonts, or JavaScript dependencies.

- Home: https://migueldeicaza.github.io/cuicaniweb/
- Privacy policy: https://migueldeicaza.github.io/cuicaniweb/privacy-policy/
- Support: https://forms.gle/TQvoaCWBzqMaaciXA

## Preview

From this directory, run `python3 -m http.server 8000`, then open http://localhost:8000/.

## Publishing

GitHub Pages uses GitHub Actions. `.github/workflows/pages.yml` publishes the public HTML, CSS, and assets on every push to `main`, or on a manual workflow run. Repository settings → Pages → Source must be set to **GitHub Actions**. No package installation or build step is needed. Relative internal links support GitHub Pages project paths.

## Content

The screenshots and bird artwork come from the Cuicani app repository. The privacy policy follows the general topics covered by [Xogot’s policy](https://xogot.com/privacy-policy/), with original wording specific to Cuicani’s current Firebase Analytics, Crashlytics, catalog, local music, and microphone behavior. Keep it aligned with the shipping app and provider configuration; the website does not change the app’s in-app privacy text or App Store privacy disclosures.

The app was in release preparation when this site was created. Add an App Store download link once the listing is publicly available.
