# The mutilated fates of Gaza

Interactive illustrated cover. A story by Francesca Mannocchi · Drawings by Gianluca Costantini.

## Preview locally

Run `python3 -m http.server 4173` from this directory, then open http://localhost:4173/.
No build step or external dependencies are required.

## Files

- `index.html`: complete page, responsive CSS and scroll/pointer animation.
- `cover_boy.png`: foreground portrait.
- `cover_buildings_smoke_lines.png`: stationary buildings and smoke contours.
- `cover_lines.png`: animated hatching.
- `cover_dust1.png`, `cover_dust2.png`: independently animated dust layers.
- `cover_buildings.png`: earlier composite, retained and used as the white backing mask.
- `cover_explosion.png`: earlier separate explosion artwork, retained as a project asset.
- `emir_of_qatar_text.png`: illustrated introductory caption.
- `emir_of_qatar_web.webp`: Emir and city illustration.

## Behavior

Desktop and mobile have independent framing. Mobile centers the text and portrait; the scenery rises and grows while scrolling. Supporting text fades before the smoke or child's head reaches it. Hatching vibrates subtly; desktop dust responds to pointer movement. Reduced-motion preferences disable the ambient smoke effects.

After the cover, the Emir caption overlaps the upper edge of a pinned comic panel and gently follows desktop pointer movement. Scrolling zooms out from his eyes and nose to reveal the surrounding buildings. The panel is horizontal on desktop and vertical on mobile, expanding to fill the screen. Reduced-motion preferences display the wider framing without the zoom.

## Sharing

This folder can be hosted as a static website. A local tunnel is temporary and depends on the host computer remaining online. Tunnel binaries, connection logs and local session files are not part of the website and are excluded from this export.

No license is granted by this export; obtain permission from the rights holders before reusing the writing or artwork.

The second Qatar caption fades out as the transparent street foreground rises over the previous city illustration. Reverse scrolling replays the sequence at 2.5 times the forward speed.

Includes the Qatar street foreground, captions 1–7, and the Gaza family sequence. Caption artwork uses a shared display scale. The Emir WebP uses a 3000-pixel-wide antialiased image.
