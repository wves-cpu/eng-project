# My Dream House

A responsive single-page architectural presentation with an interactive floor explorer and a Three.js concept model.

## Run locally

Serve this folder over HTTP (the page uses ES modules):

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.

## Customize

- Home facts, room data, materials and gallery captions: `content.js`
- Slide structure and image URLs: `index.html`
- Base layout and responsive breakpoints: `site.css`
- Button states, slide controls and entrance animations: `refinements.css`
- Three.js house model and camera: `site.js` (search for “Replace this procedural model group” to find the GLB insertion point)

The current visual concept invents a Scandinavian-modern home in Nordsjælland, Denmark. Images and fonts load from external CDNs.
