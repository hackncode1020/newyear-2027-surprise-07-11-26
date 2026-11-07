# Forever With You – A Magical New Year 2027

A luxury, cinematic New Year love surprise built with plain HTML, CSS and JavaScript (no framework, no external images, no network fonts).

**Live:** https://newyear-2027-hackncode.sites.tab.bot/

## Journey
Night-sky opening, then a name prompt (the visitor's own typed name personalises every message), a real countdown to 1 January 2027 00:00 in the visitor's local time zone (shows "Welcome, 2027!" if it has already begun), canvas fireworks with a "Celebrate With Me" show, a rooftop couple scene (inline SVG), an animated love letter, the forever promise, a 3D CSS gift box with a rose bouquet and love card, and a grand final screen.

## Files
- `index.html`, `styles.css` - structure and styling (local serif fonts in `fonts/`, serif fallback)
- `app.js` - flow, countdown, personalisation
- `fx.js` - canvas fireworks and particles
- `art.js` - SVG scenes (moon, roses, couple, bouquet)
- `audio.js` - WebAudio synthesised piano and SFX; starts only after a user tap, with play/pause and mute buttons

Open `index.html` through any static server (`python3 -m http.server`).
