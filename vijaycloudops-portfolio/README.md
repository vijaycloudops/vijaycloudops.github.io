# Vijay Kumar Kunja — DevOps & Cloud Engineer Portfolio

A responsive, single-page portfolio website built with HTML, CSS and JavaScript. Designed for GitHub Pages.

## Files

- `index.html` — portfolio content and sections
- `style.css` — responsive dark theme and layout
- `script.js` — mobile navigation, project filters and footer year
- `assets/` — place your own profile image and project screenshots here

## Publish at https://vijaycloudops.github.io

1. Create a **public** GitHub repository named exactly `vijaycloudops.github.io`.
2. Upload the contents of this folder to the repository root (not the containing folder).
3. Commit the files to the `main` branch.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait for GitHub Pages to publish the site.

## Before publishing — personalize these details

1. In `index.html`, replace `YOUR_EMAIL@example.com` with your real email address.
2. Replace `YOUR-LINKEDIN-USERNAME` with your LinkedIn profile username, or remove the LinkedIn button.
3. Check every project URL. The cards are prefilled with suggested repository names; change URLs to match the repositories you actually created. Remove projects that are not yet public or complete.
4. Confirm that all skills and certification statements accurately represent your experience. The AZ-900 certification is listed based on the profile details provided.
5. If you want a photo, add it to `assets/` and update the hero section. The current design uses a stylized CSS illustration and does not require a photo.
6. Add real project screenshots to `assets/project-images/` and link them from the relevant project cards if desired.

## Preview locally

Open `index.html` in a browser. For a local development server, use VS Code Live Server or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- No build framework or package installation is required.
- Google Fonts are loaded from Google Fonts; if unavailable, the page falls back to system sans-serif fonts.
- This site is a static portfolio. GitHub Pages hosts the HTML, CSS and JavaScript; it does not run a backend.
