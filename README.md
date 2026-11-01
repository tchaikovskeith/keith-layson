# TLN Training Quest 2026 — GitHub Pages Edition

This edition runs as a static website on GitHub Pages. It retains the training worlds, schedule, player roster, Game Masters, and local checklist.

## Publish
1. Create or open a GitHub repository, for example `tln-training-quest-2026`.
2. Upload `index.html` and `README.md` to the repository root (not the ZIP file itself).
3. Go to **Settings → Pages**.
4. Set **Source** to **Deploy from a branch**, **Branch** to `main`, folder `/(root)`, then **Save**.
5. Visit the site link shown under **Settings → Pages** after deployment completes.

## Changes from Apps Script
- Renamed `Index.html` to `index.html` for GitHub Pages.
- Removed the Apps Script template condition around the optional official calendar URL. The default no-link message remains.
- `Code.gs` is not needed: GitHub Pages cannot run `doGet()` or SpreadsheetApp visit logging.
- Checklist progress remains in browser localStorage (`tlnQuestChecks`); it is not synced across browsers or users.

## Privacy and updates
- GitHub Pages is a public website. Review roster names, Facebook links, and event details before publication.
- Edit `index.html` in GitHub and commit changes to update the published site.
- No Google Sheets logging, accounts, or backend storage is configured.
