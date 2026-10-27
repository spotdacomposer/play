# Spot the Composer — Victory Edition 🎼

Static game for GitHub Pages. Upload `index.html`, `.nojekyll`, and `README.md` to your repository root. Enable GitHub Pages under Settings → Pages → Deploy from a branch → main / (root).

## New: Victory celebration
A correct guess triggers confetti and a dialog with the composer’s name, portrait (when Wikipedia provides one), a share button, and an attempt to play a 20-second excerpt of a freely reusable recording from Wikimedia Commons with a 3-second fade-out. Audio autoplay is best-effort and may be blocked by browsers. If no confidently matched free recording exists, the dialog shows an honest unavailable message rather than playing an unrelated recording. Portrait and audio lookup require internet access.

## Notes
- Composer eras are editorial stylistic classifications.
- Daily puzzles are determined by UTC date and array order.
- Media are fetched at runtime and are not bundled or guaranteed for all 63 composers. Before a public release with complete audio coverage, manually curate and verify one recording and its license for each composer, including composition rights for contemporary works.
