# Personal Research Website

A simple, static personal/academic homepage — plain HTML/CSS, no build step,
based on the widely-used academic homepage template originally by
[Jon Barron](https://jonbarron.info/).

## Structure

```
index.html          The whole site (single page)
stylesheet.css       Styling (fonts, colors, layout helpers)
images/              Profile photo, favicon, publication thumbnails
data/                CV PDF and BibTeX files for publications
```

## Customizing

1. Open `index.html` and replace every `[bracketed placeholder]` with your
   own content: name, bio, advisor/lab links, research statement, email,
   social links.
2. Add your photo as `images/profile.jpg` and a favicon as
   `images/icons/favicon.ico` (see `images/README.txt`).
3. Add your CV as `data/CV.pdf`.
4. For each publication, duplicate the example `<tr>...</tr>` block in the
   "Selected Publications" section, then update the thumbnail, title,
   authors, venue, links, and description. Add a matching `.bib` file in
   `data/`.
5. Update the Teaching / Industry Experience lists, or delete those
   sections entirely if not applicable.

## Deploying to GitHub Pages

This repo is meant to be pushed to a repo named `<your-username>.github.io`
so it's served at `https://<your-username>.github.io/`.

```
git remote add origin https://github.com/praveen01299/praveen01299.github.io.git
git push -u origin main
```

Then enable GitHub Pages in the repo's Settings → Pages (source: `main`
branch, `/` root) if it isn't enabled automatically. The site will be live
at `https://praveen01299.github.io/` within a few minutes.

## Credit

Website template originally by [Jon Barron](https://jonbarron.info/),
structure referenced from [jericlew.github.io](https://jericlew.github.io/).
