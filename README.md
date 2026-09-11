# Faith Ukoh — GIS & Remote Sensing Portfolio

A responsive, static personal portfolio website designed for GitHub Pages.

## Files

- `index.html` — all page content and semantic structure
- `styles.css` — visual design, responsive layout and animations/effects
- `script.js` — mobile navigation and dynamic copyright year
- `README.md` — editing and publishing instructions

## Edit the content

Most content is directly in `index.html`.

### Contact details
Find the Contact section near the bottom of `index.html` and replace:
- `YOUR_EMAIL@example.com`
- LinkedIn placeholder
- GitHub placeholder
- CV placeholder

Do not leave the example email on the production site.

### Add project maps

The current project image areas are intentionally placeholders so no unverified/fabricated research output is presented.

For each project, replace the corresponding `.placeholder-media` block with an image, for example:

```html
<div class="project-media">
  <img src="assets/minna-lst-2025.jpg" alt="Land Surface Temperature map of Minna and its environs">
</div>
```

Create an `assets` folder and put your verified maps/screenshots/PDFs there.

Recommended naming:
- `minna-lulc-2005.jpg`
- `minna-lulc-2015.jpg`
- `minna-lulc-2025.jpg`
- `minna-ndvi.jpg`
- `minna-lst.jpg`
- `minna-uhi.jpg`
- `mining-change-detection.jpg`
- `kubwa-drainage.jpg`
- `kubwa-flood-susceptibility.jpg`

Use descriptive `alt` text for accessibility.

## Add a CV

Put your PDF in `assets/faith-ukoh-cv.pdf`, then change the CV link to:

```html
<a class="contact-row" href="assets/faith-ukoh-cv.pdf" download>
```

## Add GitHub repositories / scripts

You can add a `Repository` link inside any project card once the GitHub URL is available. Do not add a URL until you have the real repository.

## GitHub Pages — free publishing

1. Create/sign in to your GitHub account.
2. Create a new repository. A name such as `faith-ukoh-portfolio` works.
3. Upload `index.html`, `styles.css`, `script.js`, `README.md`, and your `assets` folder.
4. Open the repository's **Settings → Pages**.
5. Under the publishing/source option, choose the branch containing your website (normally `main`) and the root folder.
6. Save. GitHub will provide the published Pages address.
7. Test the website on desktop and mobile.
8. When you later connect a custom domain, add it through the same Pages settings and follow GitHub's DNS instructions.

## Before production

Replace all placeholders:
- Email
- LinkedIn
- GitHub
- CV
- Project maps
- Project reports
- Project methodology/results where verified
- Any dates you want displayed for NIHUB or leadership

The site intentionally contains no invented statistics, research results, employers, social URLs or client claims.
