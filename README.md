# My website

A simple static site. No build tools, nothing to install.

## Files

| File | What it does | Do you edit it? |
|---|---|---|
| `content.js` | All your text and links | **Yes, this is the one** |
| `index.html` | Page structure | Rarely |
| `style.css` | Colors, fonts, spacing | Only to change the look |
| `CV.pdf` | Your CV (add this yourself) | Replace it when you update your CV |

## Publish it (one time)

1. On GitHub, create a new repository named exactly `kwillcott.github.io` (public).
2. Click **Add file → Upload files**, drag in everything from this folder (including your `cv.pdf`), and commit.
3. Go to **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://kwillcott.github.io`.

## Update it later

1. Open the repo on github.com and click `content.js`.
2. Click the pencil icon (Edit), change your text, and click **Commit changes**.
3. Wait a minute and refresh your site.

## Tips

- Add a job or degree: copy one `{ ... }` block inside `experience` or `education`, paste it after a comma, and edit the text.
- Hide a link: set it to `""`.
- Replace your CV: upload a new file named `cv.pdf` (same name) and commit.
- A stray quote or comma is the usual cause if the page goes blank. GitHub's editor will often flag it.
- To preview locally, double-click `index.html`.
