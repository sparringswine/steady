# Steady

Home maintenance assistant (prototype). Single self-contained `index.html`, no build step.

This prototype uses in-memory demo data. State does not persist or sync between devices yet. That comes in the next version (shared storage, accounts, push).

## Deploy the normal way (repo to Vercel)

1. Create a new empty repo on GitHub (no README, no license), for example `steady`.
2. From this folder, run:

   ```
   git remote add origin https://github.com/<your-username>/steady.git
   git branch -M main
   git push -u origin main
   ```

3. On vercel.com, click Add New, Project, import the `steady` repo, and Deploy. Framework preset: Other. No build command, output directory is the root.

Vercel pulls the file from GitHub, so there is no upload size limit to worry about.

## Even faster (no repo)

Drag `index.html` straight into vercel.com (Add New, Project, deploy without Git), or run `vercel` from this folder if you have the CLI. Same for Netlify: drag the folder onto app.netlify.com/drop.

## Install on both phones

Open the live URL in Safari or Chrome, then Add to Home Screen. It behaves like an app for you and Isa.
