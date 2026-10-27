# DAMI TRAVELING — Website

A responsive black-and-gold travel vlog website made with plain HTML, CSS and JavaScript. Works with GitHub Pages.

## Files
- `index.html` — homepage
- `videos.html` — filterable video gallery
- `style.css` — responsive layout, theme and animations
- `script.js` — mobile menu, reveal animations, current year and video filters

## Before publishing
1. Open `index.html` and `videos.html`.
2. Replace placeholder `https://www.youtube.com/` links with your actual YouTube channel or video URLs.
3. Replace demo thumbnails and titles with your own video details. In `videos.html`, a YouTube video ID can be embedded with:
   `<iframe src="https://www.youtube-nocookie.com/embed/VIDEO_ID" title="Travel video" loading="lazy" allowfullscreen></iframe>`
4. Update the About text and social links if needed.

The photos currently load from Unsplash over the internet, and Google Fonts load online. For best control, download licensed images you want to use and place them in `assets/`, then update the image paths.

## Publish free with GitHub Pages
1. Sign in at https://github.com/ and create a new public repository, e.g. `dami-traveling`.
2. Extract this ZIP and upload `index.html`, `videos.html`, `style.css`, `script.js`, and the `assets` folder to the repository root.
3. Click **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then click **Save**.
6. Wait a few minutes. Your site will appear at `https://YOUR-USERNAME.github.io/dami-traveling/`.

No paid hosting is required. Replace `YOUR-USERNAME` with your GitHub username.
