# Clubhouse Digital website

Static site (HTML, CSS, a little JavaScript). Hosted on GitHub Pages at https://clubhousedigital.au/

## Update the site
- **Text or layout:** edit `index.html` (pencil icon on GitHub), then Commit. The live site refreshes in about a minute.
- **Swap a hero clip:** replace the matching files in `media/` (same names): `<sport>-hero.mp4`, `.webm`, `-sm.mp4`, `-sm.webm`, `<sport>-poster.jpg`.
- **Add another sport:** add one `<li data-label=...>` to the `#hero-clips` list in `index.html`.
- **Connect the enquiry form:** set `data-endpoint` on the `<form id="cf">` to the form service URL. The form never says "sent" unless the service confirms.

Domain and email are managed at VentraIP. `CNAME` must keep the domain name inside it.
