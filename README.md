# PocketAI Server — Privacy Policy

A standalone, static privacy-policy page for PocketAI Server, ready to publish with GitHub Pages.

## Files

- `index.html` — privacy policy page
- `assets/pocketai-logo.png` — PocketAI Server logo
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example `pocketai-privacy`.
2. Upload the contents of this folder to the **root** of the repository. Keep the `assets` folder alongside `index.html`.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The page will be available at the URL shown in Settings → Pages.

No build command, framework, package manager, or GitHub Actions workflow is required.

## Custom domain (optional)

If you want to use a subdomain, enter the exact hostname in **Settings → Pages → Custom domain** (for example, a hostname you control). Then add the DNS record GitHub requests in your DNS provider. Do not add a `CNAME` file until you have chosen the exact hostname.

## Updating the policy

Edit `index.html` and commit the changes to the `main` branch. GitHub Pages will publish the update automatically.
