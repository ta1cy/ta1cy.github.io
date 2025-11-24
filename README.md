# ta1cy.github.io Portfolio

This repository hosts the static export of my personal portfolio site, built with Next.js and Tailwind CSS.

## Workflow

1. **Develop and Update**
   - All development is done in the `my-portfolio` project (Next.js + Tailwind CSS).
   - Make changes and verify locally with:
     ```bash
     npm run build && npm run export
     npm run preview # (if using a preview server)
     ```

2. **Export and Copy**
   - After verifying, copy the exported static files from `my-portfolio/out/` into this repository (replace existing files as needed).

3. **Deploy**
   - Commit and push changes to the `main` branch of `ta1cy.github.io`.
   - GitHub Pages will serve the updated static site.

## Notes
- This repo contains only the static files. All source code and development should be managed in the `my-portfolio` project.
- For any updates, repeat the process: update in `my-portfolio`, export, copy, and push here.

---

Built and maintained by Joseph Zhang.
