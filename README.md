# Levay Static Site

Static homepage export for `levay.info`.

## Files

- `index.html`: homepage markup
- `styles.css`: all styles for the site
- `assets/images/`: local image assets copied from the current WordPress homepage

## Local preview

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deployment

Upload the contents of this folder to the document root for `levay.info` on SiteGround, or to a subdirectory first for review.

## Notes

- The page is intentionally static and has no build step.
- Metadata was tightened up for clearer search and link previews.
- Content stays close to the current homepage, with minor copy edits for clarity.
