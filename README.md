# nocta-studio.github.io

Static GitHub Pages site for Nocta Studio. It hosts the public pages required by the Google OAuth consent screen of the private "Nocta Backup" app.

| File | Purpose |
| --- | --- |
| `index.html` | Home page: what Nocta Backup is (private, single-user) |
| `privacy.html` | Privacy policy (OAuth consent screen link) |
| `terms.html` | Terms of service (OAuth consent screen link) |

## Notes
- Plain HTML, no build step. Pushing to the default branch publishes the site.
- Do not rename or remove the pages: the OAuth app branding points at these URLs.
- Do not add a logo or request brand verification in the OAuth console.
