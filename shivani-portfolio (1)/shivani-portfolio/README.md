# Shivani Sethi: Portfolio Website

A static site (HTML, CSS and JavaScript only). No build tools needed. Works on GitHub Pages.

## Publish on GitHub Pages
1. On GitHub, create a **public** repository. Naming it `shivanisethi251530-gif.github.io` gives the cleanest address.
2. Open the repository, click **Add file > Upload files**, and drag in **everything inside this folder** (`index.html`, `README.md` and the whole `assets` folder). Keep the folder structure exactly as it is, then click **Commit changes**.
   - If the browser won't upload folders, use GitHub Desktop, or `git add . && git commit && git push`.
3. Go to **Settings > Pages**. Under *Build and deployment* choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
4. After 1 to 2 minutes your site is live at `https://shivanisethi251530-gif.github.io` (or `.../<repository-name>/` for another repository name).
5. To preview locally first, double-click `index.html`.

## Details to add from your resume
Parts without verified details are hidden rather than shown empty. Fill the matching list in the `DATA` block of `index.html` and they appear automatically.

| Item | How to add it |
|---|---|
| **Resume buttons** | Save your PDF as `assets/resume/Shivani_Sethi_Resume.pdf`, then set `resume:"assets/resume/Shivani_Sethi_Resume.pdf"`. Both Download Resume buttons appear. |
| **Role titles and dates** | `exp` list (`r` = role, `w` = dates). |
| **Internship projects section** | Give each entry in the `ip` list a title (`t`). The section and its menu link appear once at least one has a title. |
| **Project screenshots** | Save images in `assets/projects/` using the names in `assets/projects/README.txt`. Until then each card shows its tools in a neutral panel. |
| **Project findings** | `f` field of each project. Only the Streaming project has a verified finding so far. |
| **More leadership and volunteering** | Add entries to the `lead` list. |
| **Academic scores** | Add to the `edu` list once verified. |

## Updating certificates
Each certificate is its own PDF in `assets/certificates/`. To add one, put the PDF there and add a line to the `CERTS` list in `index.html` (`t` title, `i` issuer, `d` date, `c` category, `f` file path).

## Folder structure
```
index.html
assets/images/profile-photo.jpg
assets/certificates/   (33 certificate PDFs + Rotaract membership certificate)
assets/resume/
assets/projects/
```
