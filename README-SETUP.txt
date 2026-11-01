# LEVEL UP — installable offline web app

## What's included
- The existing LEVEL UP dashboard and progress tracking.
- Installable PWA files for supported phones and desktop browsers.
- Offline app-shell caching so the app can reopen without an internet connection.
- Existing progress remains stored locally in the browser on each device.

## Important: cloud sync is not connected yet
This package does **not** yet sync progress between devices. A real private cloud database and sign-in need to be configured first. Do not paste passwords, API secrets, or private keys into chat or publish them in this repository.

## Publish it with GitHub Pages
1. Sign in to GitHub and create a new repository named `level-up`.
2. Upload the contents of this folder (not the ZIP itself) to the repository's root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. Open the HTTPS address it gives you.

## Install it
- **Windows / Chrome or Edge:** open the published HTTPS site, then use the install icon in the address bar or browser menu → **Install app**.
- **iPhone:** open the site in Safari → Share → **Add to Home Screen**.
- **Android:** open the site in Chrome → menu → **Install app** or **Add to Home screen**.

## Next stage: private cloud sync
After the site is published, the next stage is to connect a private backend with user authentication and per-user data rules. The app should only sync the signed-in user's own data. If the chosen provider requires an adult-managed account or permission, follow its age and account rules rather than bypassing them.
