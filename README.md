# Daily Expense Tracker — updates

This repository holds nothing but the built web layer of the app, so that
installed copies can fetch an update. The source lives in a private repo.

- `update.json` — the version on offer, the bundle URL and its SHA-256
- `bundle-<version>.zip` — the bundle itself

The app refuses a bundle whose SHA-256 does not match, and will only
download from this repository.
