# JAP Roofing Contractors — homepage concept

An original, responsive static homepage concept prepared by Kashzo Solutions. This preview is not JAP Roofing's live website and does not submit enquiries or collect personal information.

## Run locally

From this folder, start a static file server:

```powershell
python -m http.server 4173
```

Open <http://localhost:4173> in a browser. Stop the server with `Ctrl+C`.

The site uses plain HTML, CSS and JavaScript; no package installation or build step is required.

## Deploy a separate preview

Deploy this folder to a separate Vercel project, not to a JAP Roofing production domain:

1. Push this project to a repository you control, or run the Vercel CLI from this folder with `npx vercel`.
2. If prompted for a framework, select **Other**. Leave the build command and install command empty, and use `.` as the output directory.
3. Deploy to the preview URL provided by Vercel. Keep the concept notice visible until JAP Roofing authorizes a production redesign.

You can also upload this static folder to another static-site host and use its separate preview URL.

## Content and imagery notes

- Business details and listed services are based on the publicly accessible JAP Roofing website: [japroofingltd.info](https://www.japroofingltd.info/).
- BlackTree LLC was supplied as a visual reference. The integrated browser could not reliably render its page, so this concept follows the requested broad construction-site direction without claiming to reproduce unverified visual details.
- Optimized WebP images in `assets/` are concept imagery sourced from Unsplash, not JAP Roofing project photographs. Replace each image in place with approved company photography to retain the current layout and crops:
  - `roofing-worker.webp` — homepage hero
  - `roof-installation.webp` — roofing services
  - `roof-tiles-detail.webp` — materials supply
  - `slate-roofers.webp` and `terracotta-roof.webp` — gallery
- Unsplash photo IDs, in the same order: `1635424824849-1b09bdcc55b1`, `1763665814965-b5c4b3547908`, `1518736346281-76873166a64a`, `1681049400158-0ff6249ac315`, and `1605450099279-533bd3ce379a`.
- Confirm current telephone numbers, address, product availability, prices and service details directly with JAP Roofing before publishing. The enquiry links open the visitor's email application; there is no backend or form submission.
