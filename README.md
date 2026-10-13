# Otuncares — Render website and care demo

Powered by Otuntech™ on every page.

This package hosts the website and browser care demo on a Render Static Site. It does not host native iOS/Android or Windows applications, publish them in app stores, or provide a shared clinical backend.

## Deploy

Upload the contents of this folder into the root of a separate GitHub repository named `Otuncares`. The repository must contain `render.yaml`, `README.md` and `dist/` at its root. Do not upload only the ZIP.

Render configuration:

- Service type: Static Site
- Name: otuncares
- Branch: main
- Build Command: `echo 'Otuncares static assets ready'`
- Publish Directory: `dist`

Alternatively use the included `render.yaml` with a Render Blueprint.

No dependencies, secrets, database or paid compute instance are needed for this demo. Render Static Sites have a free tier subject to workspace bandwidth/build allowances.

When Render marks deployment Live, open the URL returned by Render. The website is at `/`, and the care workspace is at `/app.html`. Do not assume a particular onrender.com hostname before Render assigns it.

## Data and access

The deployed Render site is publicly accessible by link. Records are fictional and persist only in each browser's local storage. Records do not sync between browsers or devices. No staff login or access permissions are provided by this demo. Never use it for real patient or service-user data. The browser demo already displays these limitations.

Deploying to Render does not migrate browser-local records from another domain, or change the existing private ChatGPT Site.
