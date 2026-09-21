# Imprace — Legal & Support pages

Static site with four pages for the Imprace on-device AI interviewer app:

- `index.html` — landing page linking to the others
- `privacy-policy.html`
- `terms-of-service.html`
- `support.html`
- `style.css` — shared styles

## Before you publish: fill in the placeholders

Anything highlighted in yellow (class `fill`) is a placeholder to replace.
Search the files for these and update them:

- **Your Name / Company** — appears in footers and legal text
- **youremail@example.com** — your support/contact email
- **Last updated / © year** — set the real dates
- **Analytics / crash reporting** — state none, or name the provider
- **Third-party services** — list any SDKs, CDNs, or update services
- **Network access** — describe exactly what the app connects to
- **Children's age** — set the age for your region
- **Governing law** — your country / state / jurisdiction
- **Device requirements, model size, pricing** — on the support page

Once filled in, delete this note if you like, and remove the `.fill`
highlight by not using the class (or leave it; it only affects the words
you already replaced).

> These pages are a starting template, not legal advice. Review them against
> your app's actual behaviour and your app store's requirements.

## Hosting on GitHub Pages

See the steps your assistant gave you, or the short version:

1. Create a GitHub repo and upload these files to the root.
2. Repo **Settings → Pages**.
3. Under **Build and deployment**, set **Source: Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. Wait ~1 minute, then open `https://USERNAME.github.io/REPO-NAME/`.

Your pages will be at:

- `https://USERNAME.github.io/REPO-NAME/privacy-policy.html`
- `https://USERNAME.github.io/REPO-NAME/terms-of-service.html`
- `https://USERNAME.github.io/REPO-NAME/support.html`

Use those URLs in your Play Store / App Store listing.
