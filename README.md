# irunkel.github.io

Source for my personal lecture-notes page, served by GitHub Pages at
https://irunkel.github.io

Only compiled PDFs are kept here, not the LaTeX source.

## Structure

```
index.html      the whole site (single page, no build step)
pdfs/           one PDF per course
```

## Adding a new set of notes

1. Copy the finished PDF into `pdfs/`, e.g. `pdfs/lie-algebras-ws2627.pdf`.
2. Open `index.html` and add a new `<li>` entry under the relevant `<h2>`
   section (there are commented-out examples in the file showing the
   pattern to copy).
3. Commit and push:

   ```
   git add .
   git commit -m "Add Lie Algebras notes"
   git push
   ```

4. GitHub Pages rebuilds automatically after the push; the new page is
   live at https://irunkel.github.io within a minute or two.
