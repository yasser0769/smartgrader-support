# المصحح الذكي — Support and privacy

Static Arabic-first support and privacy pages for the iOS app.

- Support URL: https://yasser0769.github.io/smartgrader-support/support.html
- Privacy Policy URL: https://yasser0769.github.io/smartgrader-support/privacy.html
- Contact: yasser0769@gmail.com

GitHub Pages publishes the `main` branch at `/` (root). `.nojekyll` disables Jekyll. All assets are local; no scripts, forms, analytics, or external font requests.

To update: edit the matching files in `ios/AppStoreWebsite/` in the private app repository, preview with `python3 -m http.server 8765 --directory ios/AppStoreWebsite`, then copy only this directory's contents to the public repository and commit/push. Never copy app sources, student fixtures, diagnostics, or audit evidence. Verify both public URLs after deployment. Keep the policy date and actual app behavior aligned.

The site is a support resource, not an assertion of App Store approval. App Store Connect privacy disclosures must separately match the shipping app.

The bundled IBM Plex Sans Arabic font is distributed under the SIL Open Font License 1.1; see `assets/OFL.txt` (source: https://github.com/IBM/plex/blob/master/LICENSE.txt).
