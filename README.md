# Noah Mills — Web Strategist · 2026 Pitch

A single-page, password-gated slide deck for the TDC Marketing re-pitch.

**Live:** https://noahmills-ux.github.io/tdc-repitch-2026/
**Everything lives in one file:** `index.html` (HTML + CSS + JS, no build step). Images are in `assets/`.

## How deploying works
This repo auto-publishes with **GitHub Pages**. Any commit to the **`main`** branch
goes live at the URL above in ~60 seconds. There's nothing to build or run — just commit to `main`.

## Edit + publish from your phone (quick copy/number tweaks)
1. Open the **GitHub mobile app** (or github.com in your phone browser) and go to this repo.
2. Tap **`index.html`** → the **pencil** (edit) icon.
3. Use the in-file search to jump to the text you want (each slide is labeled with an HTML
   comment like `<!-- 6 · PROJECTS -->`).
4. Make your change → **Commit changes** → commit to **`main`**.
5. Wait ~60s, then hard-refresh the live URL.

Great for: copy fixes, numbers, links, swapping an image filename.
Harder on a phone: layout/animation changes — those are easier on a computer.

## Slide order (15)
1 Cover · 2 Addressing · 3 CliftonStrengths (press Next once to reveal blind spots) ·
4 Revenue · 5 Leadership (Regan & Sara) · 6 Their web revenue · 7 Project highlights (carousel) ·
8 One-off / unique skill · 9–11 Web strategy (Compendium, Plugin, Lifecycle) · 12 Five years out ·
13 Compensation (payscale) · 14 Role & growth · 15 Thank you

## Adding the placeholder images later
- Mike's HED quote screenshots are already on slide 8.
- Web build lifecycle image: `assets/web-build-lifecycle.png` (already in).
- To swap any image, drop a file into `assets/` and update the `src="assets/..."` in `index.html`.

## Notes
- Navigation: arrow keys / on-screen arrows (mobile) / the slide counter (top-right) / the side dots.
- The password is checked client-side; its SHA-256 hash sits near the top of the `<script>` block
  (`GATE_HASH`). To change it, replace that hash.
