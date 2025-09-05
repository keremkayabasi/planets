# Project rules for Claude

## Scope
- Project type: Plain HTML/CSS/JS (no framework).
- Main files: `index.html`, `test.html`
- Optional (if needed): `style.css`, `script.js`

## Do / Don't
- ✅ Keep changes minimal and well-explained.
- ✅ Improve accessibility (alt text, labels, contrast) when relevant.
- ✅ Write clear PR description summarizing *what* and *why*.
- ❌ Do not add frameworks, external trackers, or analytics.
- ❌ Do not touch build/CI or repository settings.

## File access
- **Allowed:** `index.html`, `test.html`, `style.css`, `script.js`
- **Do not touch:** `*.md`, `.github/**`, `LICENSE`

## Git & PR
- Target branch: **master**
- Branch name pattern (example): `auto/fix-<issue-number>`
- Commit message style: `fix: <short summary>`

## How to run
- Open `index.html` locally in a browser (no build needed).

## When triggered
- Work only when explicitly asked in an issue comment
  (e.g., “@claude please create a new branch, apply the fix described above, and open a PR to master.”).
