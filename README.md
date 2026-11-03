# Nonogram

Free single-file HTML5 nonogram (picross) puzzle game. Fill cells using the
row and column number clues to reveal the hidden picture. Every puzzle is
procedurally generated and verified by a constraint-propagation solver to
have exactly one solution.

## Play

Open `index.html` in any modern browser — no build, no dependencies, no
external assets. All graphics are drawn on canvas at runtime and all sounds
are synthesized with WebAudio.

- 3 sizes: 5×5 (Easy), 10×10 (Medium), 15×15 (Hard)
- Guaranteed-unique solutions (row/column line-solving + row-branching search)
- Mouse + touch input, drag filling, mark (×) mode, undo
- Error check (2 uses per puzzle), over-count warning on rows/columns
- Timer with best times per size (localStorage)
- Washi paper-and-ink visual style, color reveal animation on completion
- Works offline once loaded. No ads, no tracking, no external links.

### Controls

- Tap or left-click: fill cell (drag to paint several)
- Right-click or Mark mode button (M): draw ×
- U: undo · M: mark mode · H: check errors · Esc: menu

## Deploy

Static file — serve it anywhere (GitHub Pages, itch.io, CrazyGames,
GameDistribution, any static host). Platform SDKs load conditionally by
domain and are absent when self-hosted.

## License

MIT
