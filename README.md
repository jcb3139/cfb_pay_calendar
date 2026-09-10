# Four Founders Biweekly Payroll Calendar

Interactive payroll calendar covering August 31 through December 31, 2026. Pay-period days are visually grouped, and each payday identifies the earlier pay period it covers.

## Publish with GitHub Pages

1. Create an empty GitHub repository.
2. From this directory, initialize and push the repository:

   ```bash
   git init -b main
   git add .
   git commit -m "Publish payroll calendar"
   git remote add origin git@github.com:YOUR-ACCOUNT/YOUR-REPOSITORY.git
   git push -u origin main
   ```

3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **GitHub Actions**.
5. Open the **Actions** tab and confirm that **Deploy to GitHub Pages** completes successfully.

The deployment URL will appear in the workflow summary and under **Settings → Pages**.

## Local preview

Open `index.html` in a browser. The site is self-contained and has no build step or external runtime dependencies.

## Updating the calendar

Replace `index.html`, commit the change, and push to `main`. The included workflow republishes the site automatically.
