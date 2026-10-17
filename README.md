# CardioAtlas feed
Public JSON feed of daily cardiology updates for the CardioAtlas app.

- Latest: https://sreehari295-maker.github.io/cardioatlas-feed/updates.json
- Archive (kept permanently): `archive/YYYY-MM-DD.json`; list of days (newest first): `archive/index.json`
- Format: `updates.schema.json`. v2 adds optional `bullets` (3-5 per item, written after reading the source); `summary` is kept for older app versions.

## Categories
`trial`, `guideline`, `approval`, `research`, `conference`, `safety` (device recalls, FDA/EMA safety alerts, drug warnings; shown by CardioAtlas app v1.11+, older versions skip items whose category they do not know).
