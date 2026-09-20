# DELCO Social Hub — presentation

Two views of the same deck, on one site:

- `index.html` — scrolling version. Reads well on a phone, works anywhere.
- `slides.html` — classic 16:9 slides for presenting on a laptop or screen.

Each page has a link to the other at the bottom, so anyone can switch.
Both files carry their own artwork; there are no other assets.

## Deploy on Netlify

**Drag and drop:** put all three files in one folder and drop it on
app.netlify.com/drop.

**From a repo:** Add new site → Import an existing project. No build command;
publish directory `.` (already set in `netlify.toml`).

The link you share is the site root — it opens the scrolling version, which is
the safer default on an unknown device.
