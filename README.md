# The Arabians — Series Treatment

A self-contained interactive slide deck (24 slides + 2 video reels).

## Structure

```
index.html                    ← the whole deck (fonts, styles, scripts, map data all inlined)
assets/
  Imagic-Showreel.mp4         ← "Imagic in Motion" production reel
  Arabian-Sizzle.mp4          ← "The Arabians — A First Look" sizzle reel
```

Everything except the two videos is bundled inside `index.html`. The videos are kept
as separate files (full original quality) and loaded from `./assets/`.

## View it

- **Locally:** open `index.html` in any modern browser. Keep the `assets/` folder next to it.
- **GitHub Pages:** push this folder to a repo, enable Pages (Settings → Pages → deploy
  from the default branch, root). The deck is served at the root URL automatically because
  it is named `index.html`.

## Notes

- Navigate with arrow keys / on-screen arrows, or click the thumbnail rail.
- The two video slides lock navigation while a reel is playing.
- No build step and no external network requests are required to view the deck.
