# serena-lee-website

One-page portfolio site for Serena Lee, a freelance wedding and portrait photographer.

It is plain HTML and CSS with no build step, so Vercel serves it as-is.

## Files

- `index.html` is the whole site: hero, portfolio grid, about and contact.
- `wedding-01.jpg` is the first portfolio photo.
- `vercel.json` sets clean URLs and basic security headers.

## Deploy on Vercel

1. In Vercel, choose **Add New > Project** and import this repository.
2. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
3. Deploy. Every push to `main` redeploys the site.

To deploy from the command line instead, run `npx vercel` in this folder, then `npx vercel --prod`.

## Edit the site

- **Photos:** each placeholder in the portfolio grid is a `<div class="photo">`. Replace it with `<img class="photo" src="your-photo.jpg" alt="..." width="..." height="...">` and add the image file next to `index.html`. See the first grid item for the pattern.
- **Email:** the contact address in `index.html` is a placeholder (`hello@serenalee.photo`). Replace it with her real address in both the link and the visible text.
- **Copy:** the about text and photo captions are sample wording.
