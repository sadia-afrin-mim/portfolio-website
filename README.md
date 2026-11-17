# Sadia Afrin Mim — Personal Website

A single-file academic website with tabs for Home, Research, Publications, Experience, Teaching, Talks & Awards, and Contact.

## Publish on GitHub Pages

1. Create a new public repo on GitHub named exactly **`sadia-afrin-mim.github.io`**.
2. Upload these files to the repo root:
   - `index.html`
   - `cv.pdf` (your CV, renamed to `cv.pdf`, so the "Download CV" button works)
   - `photo.jpg` (your profile picture)
3. In the repo, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, branch **main**, folder **/ (root)**, and save.
4. After a minute or two, the site is live at **https://sadia-afrin-mim.github.io**.

## Customize

- **Photo:** add `photo.jpg` to the repo, then in `index.html` find `<div class="avatar" aria-hidden="true">SM</div>` and replace `SM` with
  `<img src="photo.jpg" alt="Sadia Afrin Mim">`.
- **Paper links:** each publication is a `<div class="pub">` block. To link a PDF or DOI, wrap the title text in `<a href="...">...</a>`.
- **News:** edit the "Latest news" table on the Home tab.
- **Tabs:** each tab is a `<section class="view" id="view-NAME">`. Its link in the nav is `#NAME`, and NAME must also be in the `views` list in the script at the bottom.
