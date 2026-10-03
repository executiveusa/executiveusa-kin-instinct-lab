# Deployment

## Canonical source
This GitHub repository is the source of truth.

## Static production
The root `index.html` is a zero-build static application. `vercel.json` serves it directly and adds basic browser security headers.

No database, analytics, API keys, or private deployment data are required for the public prototype.

The existing Higgsfield deployment can remain temporarily as fallback while the GitHub-backed production target is established.

**Netlify is not part of this deployment path.**
