# DSC 106 Project 2

Final report: **NYPD pepper-spray allegations were usually ruled permissible.**

## Files to publish

```text
index.html
assets/
  overall.svg
  recent-outcomes.svg
  substantiation-trend.svg
.nojekyll
README.md
.gitignore
```

The report uses the provided course template. All three charts are programmatic SVGs. No build step, package installation, or external JavaScript is required.

## Before submitting

1. Review the scored design decisions and three-paragraph reflection with the team.
2. After review, remove the yellow `Team review draft` paragraph and any remaining wording that says the ratings are subject to review from `index.html`.
3. Publish the root folder using GitHub Pages.
4. Open the public URL and confirm both figures and all three charts display correctly.

## GitHub Pages

This folder was not a Git repository when organized. If using the GitHub website, upload the files listed above and the entire `assets` folder. **Do not upload `_archive`.** A browser upload does not apply `.gitignore` rules.

If using Git locally, `.gitignore` excludes `_archive`, raw data contained there, and local metadata. Review the staged file list before committing.

In the GitHub repository: **Settings → Pages → Build and deployment → Deploy from a branch**. Select the branch containing these files (usually `main`) and **`/ (root)`**, then Save. A repository named `Project2` normally serves at `https://YOUR-USERNAME.github.io/Project2/`.

## Preserved local work

All previous analyses, PDFs, generators, data, and previews were moved intact to `_archive/`. They were not deleted. File hashes are recorded in `_archive/preserved_files_manifest.json`.

- Chosen template version: `_archive/pepper_spray_project/final_report_template/`
- Custom report: `_archive/pepper_spray_project/final_report/`
- Latest comparison PDF: `_archive/pepper_spray_project/charts/pepper_spray_checkpoint_direct_comparison.pdf`
- Analysis and generators: `_archive/pepper_spray_project/analysis/`
- Original dataset: `_archive/CCRB-Complaint-Data_202007271729/`

The root `index.html` and `assets/` are now the publication files. Editing an archived generator does not automatically update these copies.

## Team

- Natalie Wu — nswu@ucsd.edu
- Rishika Sahu — rsahu@ucsd.edu
- Marcus De Ramos — mderamos@ucsd.edu

## Source

[ProPublica / NYC Civilian Complaint Review Board, July 2020](https://www.propublica.org/datastore/dataset/civilian-complaints-against-new-york-city-police-officers)
