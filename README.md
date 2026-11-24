# serena-lee-website

One-page portfolio site for Serena Lee, wedding and portrait photographer.

Plain HTML and CSS, no build step and no dependencies. Fonts (Cormorant Garamond, Pinyon Script, Jost) load from Google Fonts.

## Structure

```
index.html        the whole site
images/           portfolio photographs
vercel.json       Vercel config (static site, security and cache headers)
```

## Preview locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy to Vercel

1. Import this repository at https://vercel.com/new.
2. Leave the framework preset as **Other**. No build command or output directory is needed; `vercel.json` already sets them.
3. Click **Deploy**. Every push to `main` redeploys the site.

Or from the command line: `npx vercel --prod`.

## Editing

- **Photos:** add files to `images/` and replace each `Photograph 0X` placeholder in `index.html` with
  `<img src="images/your-photo.jpg" alt="…" style="display:block;width:100%;aspect-ratio:4 / 5;object-fit:cover">`.
- **Email:** search for `hello@serenalee.com` in `index.html` and replace it (it appears in the link and its text).
- **Copy and colors:** edit directly in `index.html`.
