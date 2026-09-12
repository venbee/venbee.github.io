# Venkatesh Beeraka — personal portfolio

An independent static portfolio with a dark green-and-blue theme, seven animated chapters, project dialogs, skills, career history, and a GPU/inference learning direction.

## Start here

1. Extract the ZIP and open `index.html` to preview locally.
2. Create a **new repository** in your own GitHub account. Leave the repository template unset; this package needs no fork or imported repository history.
3. Use a name you prefer. For a personal homepage, use `venbee.github.io` if you do not already have that repository; its Pages address will be `https://venbee.github.io/`. A project repository such as `ai-portfolio` will instead use `https://venbee.github.io/ai-portfolio/`.
4. Make the repository public for GitHub Pages on GitHub Free. Create it with a README if you want GitHub to initialize the default branch for you; replace that README with this one when uploading.
5. Upload the **contents** of the extracted `venkatesh-portfolio` directory to the repository root. Do not upload the ZIP or the enclosing directory. Keep `index.html` beside `assets/`.
6. Include the empty `.nojekyll` file. If your file picker hides it, create a file called `.nojekyll` in the repository root through GitHub's Add file / Create new file interface (a blank line is fine).
7. Commit directly to your own `main` branch for this initial setup if your repository rules allow it. No pull request to another project is needed.
8. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then save. If your default branch has a different name, select that branch.
9. Wait for deployment to finish and use **Visit site** on the Pages settings page.

This package contains no `.github` folder, CODEOWNERS, bot configuration, custom CI workflow, Jekyll configuration, theme source, or Git history. It uses system fonts and has no external font dependency. Existing account/organization policies and installed GitHub Apps can still apply to a new repository. GitHub itself may run the Pages deployment workflow when you enable Pages.

## Your photo

Replace **`assets/img/profile.jpg`** with your latest JPEG, keeping the exact filename. The current file is your original repository photograph. A portrait crop around 800 × 1000 pixels works well; keep your face near the center and upper third. Export other image formats as JPEG rather than merely renaming the extension.

The website adds its monochrome and green/blue treatment in CSS. Adjust `object-position` in `.profile-photo` if you want to change the crop. A VB monogram appears if the image is missing.

## Your résumé

Replace **`assets/docs/venkatesh-beeraka-resume.pdf`** with your preferred public résumé. The supplied file is the masked PDF you uploaded. LinkedIn and GitHub are the website's contact links; the masked email and phone number are not displayed on the webpage.

## Editing guide

| File | Edit here |
| --- | --- |
| `index.html` | Your text, role, location, skills, links, timeline, and project templates |
| `assets/css/portfolio.css` | Colors, typography, layout, responsive rules, and animation |
| `assets/js/portfolio.js` | Section navigation, motion controls, mobile menu, and project dialogs |
| `assets/img/profile.jpg` | Your main profile photograph |
| `assets/docs/venkatesh-beeraka-resume.pdf` | Your downloadable résumé |
| `assets/img/favicon.svg` | Browser-tab icon |

No build step, npm install, API keys, or server-side application is required. Relative asset links support both personal and project Pages addresses. The design uses your résumé's role titles, dates, and project counts. GPU, inference, and AIOps are shown as learning directions rather than established production experience.

## Controls and checks

Scroll normally, use the section links, or use the bottom previous/next buttons. Left/right arrow keys move between chapters outside text inputs. Select View project for details and Escape to close. Pause motion stops decorative animations, and system reduced-motion preferences are respected.

Optional local checks:

```sh
node --check assets/js/portfolio.js
python3 script/check_portfolio.py
```

Syntax and local link checks passed during preparation. Browser visual testing was blocked by the creation environment's local-page policy. Before publishing, review desktop/mobile layouts, photo cropping, chapter navigation, all project dialogs, and résumé download in your browser.

## GitHub documentation

- [Create a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)
- [Create a Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Configure the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
