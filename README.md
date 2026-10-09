# Omar Ibne Shahid — personal website

A single-page academic portfolio. Plain HTML, no build step, ready for GitHub Pages.

```
index.html                      the whole site (content, styles and scripts)
assets/Omar_Ibne_Shahid_CV.pdf  linked from the "CV (PDF)" button
assets/profile.jpg              your photo (add this yourself, see below)
```

## Put it online with GitHub Pages
1. Sign in to GitHub and create a new **public** repository named exactly
   `YOUR-USERNAME.github.io` (for example `omarshahid232.github.io`).
   Using that name makes the site live at `https://YOUR-USERNAME.github.io`.
   Any other repository name also works; the site is then at
   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME`.
2. In the new repository, click **Add file → Upload files**, drag in `index.html`,
   `README.md` and the whole `assets` folder, then click **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to
   **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and click **Save**.
4. Wait a minute or two, then open the address from step 1.
   Every later commit republishes the site automatically.

## Common edits

All edits happen in `index.html`. You can edit it directly on GitHub
(open the file, click the pencil icon, then **Commit changes**).

- **Add your photo:** save a square photo (at least 400 × 400 px) as
  `assets/profile.jpg` and upload it. Until then the page shows your initials.
- **Add GitHub or ORCID:** search for `<a href="">GitHub</a>` and
  `<a href="">ORCID</a>` and paste your profile URL between the quotes.
  Buttons with an empty link stay hidden, so nothing broken ever shows.
- **Post news:** find the `NEWS` section, copy one `<li class="entry">…</li>` block
  to the top of the list, and change the date and text.
- **Add a publication:** copy an existing `<li class="entry pub">…</li>` block under
  the right heading (journal, conference, book chapter) and edit it.
  Wrap your own name in `<strong>…</strong>` so it is highlighted.
- **Update your CV:** replace `assets/Omar_Ibne_Shahid_CV.pdf` with a file of the same name.
- **Footer date:** change "Last updated September 2026" at the bottom when you edit.

## Optional: your own domain

To use a domain such as `omarshahid.com`, buy it from any registrar, then in
**Settings → Pages → Custom domain** enter the domain and follow GitHub's DNS
instructions. Tick **Enforce HTTPS** once it becomes available.

## Features

- Light and dark themes (follows the visitor's system setting, with a toggle in the top bar)
- Works on phones, tablets and desktops
- Sticky section navigation that highlights where you are on the page
- Search-engine metadata (description, Open Graph, schema.org Person) so Google
  can connect the site with your Scholar and LinkedIn profiles
- Prints cleanly as a one-document CV-style page
