# Lewin's Chess Game Website

Official landing page for the Lewin's Chess Game chess companion app.

## Pages

- `index.html` — product landing page
- `privacy.html` — privacy-policy page for App Store review
- `support.html` — support page and future public support destination

## Local Preview

This is a static GitHub Pages site, so you can open `index.html` directly in a browser.

For a preview closer to production, run:

```bash
python3 -m http.server 4173
```

Then visit:

```text
http://localhost:4173/
```

## Before Publishing

Replace the remaining placeholders before submitting the app or publishing the website:

- Add the final App Store URL in `index.html`.
- Replace the hero and screenshot placeholders with approved app screenshots.
- Add the reviewed privacy-policy text, effective date, and contact method in `privacy.html`.
- Add the public support email address and any relevant FAQs in `support.html`.

## GitHub Pages Verification

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings` → `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the branch, usually `main`, and the `/root` folder.
6. Click `Save` and wait for GitHub Pages to publish the site.
7. Open the generated URL, usually:

```text
https://github.com/indiana-lee/lewins-chess-game/
```

For App Store Connect, use the published URLs for:

- Marketing URL: the homepage URL
- Privacy Policy URL: `https://github.com/indiana-lee/lewins-chess-game/privacy.html`
- Support URL: `https://github.com/indiana-lee/lewins-chess-game/support.html`
