# MCC CourseMaker — GitHub Pages Package

This folder contains the complete static website for:

`https://jghazzagh.github.io/mcc_course_builder/`

No installation, build command, package manager, or server-side application is required.

## Publish on GitHub Pages

1. Create a public GitHub repository named exactly `mcc_course_builder`.
2. Upload **the contents of this folder** to the root of the repository. Do not place them inside an additional folder.
3. Commit the uploaded files to the `main` branch.
4. Open the repository's **Settings**.
5. Select **Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose the `main` branch and `/(root)` folder, then select **Save**.
8. After GitHub finishes publishing, open:

   `https://jghazzagh.github.io/mcc_course_builder/`

## Required files

- `index.html` — CourseMaker website entry page
- `404.html` — GitHub Pages fallback
- `.nojekyll` — prevents Jekyll processing
- `assets/styles.css` — CourseMaker interface styles
- `assets/app.js` — Page Builder, templates, Widget Builder, and support functionality
- `assets/mcc-logo-horizontal.png` — MCC header logo
- `assets/mcc-logo-horizontal-white.png` — MCC footer logo

## Updating the site

Replace the changed file in the repository and commit the update. GitHub Pages will publish the new version automatically.

The `/mcc_course_builder/` path is built into `index.html` and `404.html`. If the repository name changes, update those asset paths before publishing.

## Notes

- All page and widget building happens in the visitor's browser.
- CourseMaker does not send or save the faculty member's entered page content.
- The support page's YouTube and Scribe resources require internet access.
- Do not place passwords, private student information, or API keys in this public repository.

