# Ryan Heejoon Byun academic homepage

Astro-based academic homepage for GitHub Pages.

## Local setup on Windows

Install Node.js LTS first. Then open PowerShell in this folder and run:

```powershell
npm install
npm run dev
```

Open the local URL shown by Astro, usually `http://localhost:4321`.

## Deploy on GitHub Pages

1. Put these files in the root of your `ryanb61901.github.io` repository.
2. Commit and push to `main`.
3. In GitHub, go to `Settings > Pages`.
4. Under `Build and deployment`, choose `GitHub Actions` as the source.
5. Pushes to `main` will build and deploy automatically.

The included `astro.config.mjs` assumes your final URL is:

```text
https://ryanb61901.github.io
```

If you are deploying as a project site instead, edit `astro.config.mjs` and set `base` as described in the comments.

## Update CV

Replace this file and keep the same filename:

```text
public/assets/Ryan_Heejoon_Byun_CV.pdf
```

Then commit and push.
