# Research paper website — GitHub Pages

**Paper:** Latent Cluster Separation as a Regularizer for Lifelong Anomaly Detection  
**Authors:** Sabarish Radhakrishnan and Nathalie Japkowicz  
**Status at time of preparation:** Submitted to IEEE BigData 2026, under review.

## Before publishing

- The `manuscript.pdf` is now the newly supplied, ten-page author-identified **ArXivPreprint** file (not the older August 21 working copy, and not the anonymous IEEE submission). It already contains the required IEEE notice within its first page; no extra cover sheet was added. Confirm this exact author-approved version with your coauthor before publication. It is not a publicly indexed arXiv publication yet.
- Check that **all authors** consent to the website, copied empirical figure, and full PDF posting. (The author has indicated Dr. Japkowicz approved the personal website; verify the actual manuscript revision is also approved.)
- Review IEEE's rules for preprints on authors' personal websites: https://conferences.ieeeauthorcenter.ieee.org/get-published/post-your-paper/
- Confirm the site accurately identifies each author's affiliation and the paper's current status. A private address, submission ID, and email are intentionally not displayed on the website.
- Since public GitHub repositories expose version history, do not commit private review correspondence, reviewer comments, submission IDs, passwords, or unreleased research materials.

## Publish via GitHub.com (no software installation)

1. Unzip this archive on your computer. You should see `index.html`, `manuscript.pdf`, `latent-space-diagnostic.png`, `.nojekyll`, and `README.md`.
2. Open https://github.com/new (log in to GitHub first).
3. Repository name: `lifelong-anomaly-paper`; visibility: **Public**. Create the repository.
4. On the empty repository screen, select **uploading an existing file**, or use **Add file > Upload files**.
5. Upload **the individual files from inside the extracted folder**, not the ZIP. `index.html` must be at the repository root.
6. Commit changes.
7. Open **Settings > Pages**. Choose **Deploy from a branch**; select branch **main** and folder **/(root)**, then save.
8. Wait for GitHub to publish. Open the URL shown under Pages, generally: `https://YOUR_GITHUB_USERNAME.github.io/lifelong-anomaly-paper/`.
9. Test the public link in a private/incognito browser window. Confirm the site displays, the manuscript button opens, and every link works.

## Updating status later

Edit the status labels in `index.html` if the conference decision changes. Do not describe the work as peer reviewed until accepted. If the paper is posted to arXiv, add the public arXiv link; if officially accepted/published, follow IEEE's required preprint replacement, DOI/citation, and copyright-notice rules. Make sure every revision reflects the true paper status.

## Files

- `index.html` — fully styled, mobile-friendly research webpage; no frameworks, build tools or external assets required.
- `manuscript.pdf` — public candidate PDF with IEEE notice cover.
- `latent-space-diagnostic.png` — Figure 1 extracted directly from the same newly supplied author-preprint PDF (labels LatentSep-Dist (c), not the older Full (c)).
- `.nojekyll` — tells GitHub Pages to serve these files directly.

This folder can be uploaded as-is to a GitHub repository. GitHub will not automatically publish a website from a ZIP archive alone.

## Important version / policy notes

- The paper remains **submitted and under review**. Do not call it accepted, published in IEEE Xplore, or peer reviewed.
- IEEE's submission notice is shown on the site's first screen, and a corresponding notice appears on the manuscript’s original first page.
- If IEEE accepts the manuscript, its [Post Your Paper guidance](https://conferences.ieeeauthorcenter.ieee.org/get-published/post-your-paper/) requires replacing the posted preprint with the allowed citation or accepted version and adding the appropriate DOI / copyright information. In particular, do not simply leave an outdated PDF online indefinitely after acceptance.
- The arXiv submission's **temporary** submission ID is not a public arXiv article identifier. Do not link it as a public publication.
- Website updates are not transmitted to colleges automatically; colleges may or may not revisit a shared link.

## Provenance / version comparison (October 19, 2026)

- `BigD1013_8761(3).pdf` and `..._Paper(2).pdf` are bit-for-bit identical anonymous conference-submission copies and should **not** be substituted as an author-facing public preprint.
- `ArXivPaper(5).pdf` is an author-named rendering containing a temporary arXiv *submission* watermark; the watermark is **not** a public arXiv article identifier.
- `...__ArXivPreprint(1).pdf` is the author-named document without the temporary submission watermark and with the IEEE posting notice already printed in the PDF. This is the source of both the published-ready `manuscript.pdf` and Figure 1.
- The `index.html` content has been checked against this preprint, but there has been no independent verification of the conference review outcome. Conference link: https://bigdataieee.org/BigData2026/

## Publication safety

- Do not publish until you have reviewed the exact PDF and confirmed coauthor authorization for this version.
- If IEEE accepts the paper, **replace** the online preprint as required by IEEE’s rules; do not only change the status badge and leave the same PDF.
- Do not publish the saved arXiv preview HTML directly: its relative CSS/JS assets and private submission links may break or disclose temporary identifiers.