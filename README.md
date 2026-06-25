This is the code for Kaitlin's personal/academic website, built on top of the template from [Andy Zeng's website](https://github.com/andyzeng/andyzeng.github.io). It uses [Isotope](https://isotope.metafizzy.co/) to power the "sort by category" filter buttons (Highlights / Publications / Talks / Misc) -- you can customize the `data-filter` and `data-category` fields, plus the Isotope parameters in the JS at the bottom of `index.html`.

## What's here
- `index.html` -- the page content, with bio filled in and Highlights/Publications/Projects/Honors/Misc sections commented out with examples until you have real content to add.
- `style.css` -- styling, unchanged from the original template.
- `images/` -- empty for now. Add your headshot (e.g. `images/profile.jpg`) and any project photos/videos here, then uncomment the relevant lines in `index.html` to use them.

## To-do before publishing
- Add your last name to the `<title>` and `<h1>` in `index.html`.
- Add a headshot to `images/` and uncomment the `<img>` tag in `#intro-image`.
- Fill in social links / email if/when you want them shown.
- Add Highlights, Publications, Talks, and Misc entries as you accumulate them (examples are commented out in each section).

## Deploying to GitHub Pages
1. Push this folder to a repo named `<your-github-username>.github.io`.
2. In the repo's Settings -> Pages, set the source to the `main` branch, root folder.
3. Your site will be live at `https://<your-github-username>.github.io`.
