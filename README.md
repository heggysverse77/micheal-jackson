# micheal-jackson — MOONLIGHT

An interactive, scroll-driven motion-graphics film about Michael Jackson's life, told in light.
One canvas, a real 3D camera, a procedural dancer rendered as halftone light, eight acts:
Jackson 5 · Motown · Off the Wall · Thriller · The Moonwalk · Bad · Dangerous · The Legacy.

## Run it

Double-click `index.html`, or serve the folder locally:

```
python -m http.server 8000
```

then open http://localhost:8000 (on Windows, `serve.bat` does this for you).
Scroll to play. Use the sound toggle (top right) for the generated score.

## Notes

- Plain HTML + Canvas 2D, no dependencies. Fonts load from Google Fonts with system fallbacks.
- The dancer is a faceless, stylised figure; all music is generated in the browser.
