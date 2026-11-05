# Syed Tanzim Mubarrat · Research portfolio

A static GitHub Pages site with a homepage, research and project case studies, publications and theses, and teaching and mentoring. The homepage also includes experience, education, CV, portfolio, and contact links.

## Publish

1. Sign in to GitHub as `tanzim99901`. Create a public repository named `tanzim99901.github.io` if you do not already have one.
2. Add the files from this package to the root of the repository's `main` branch. Keep `index.html` and `.nojekyll` at the repository root. The Git commands below preserve the dotfile.
3. In the repository, open **Settings → Pages**. Set **Source** to **Deploy from a branch**, select **main** and **/(root)**, and save.
4. When the deployment completes, use **Settings → Pages → Visit site**. The expected URL is `https://tanzim99901.github.io/`.

For a new, empty repository, run the following in the extracted folder.

```sh
git init -b main
git add .
git commit -m "Add research portfolio site"
git remote add origin https://github.com/tanzim99901/tanzim99901.github.io.git
git push -u origin main
```

If the repository already contains commits, clone it first and copy in the site files, then review and commit the changes in the clone.

[GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart)

## Preview and edit

Run `python3 -m http.server 8000` from the extracted folder, then open `http://localhost:8000/`. The site has no build step or package dependencies.

| Content | File |
| --- | --- |
| Bio, experience, and education | `index.html` |
| Research and project archive | `projects/index.html` |
| Papers, dissertation, and thesis | `publications/index.html` |
| Teaching, mentoring, and proposed courses | `teaching/index.html` |
| Design and images | `assets/` |
| Search engine discovery | `robots.txt` and `sitemap.xml` |

The navigation and contact footer are present in each HTML file. Update the CV or portfolio link across the HTML pages when you replace a document. The existing Google Drive links are external. Check their sharing permissions in a signed-out window before relying on them.

The proposed courses are described on the teaching page. If you want to publish full syllabi later, add the intended public PDFs and link them from that page.

The canonical URLs and sitemap use `tanzim99901.github.io`. Update those values if you deploy under a different domain or account.
