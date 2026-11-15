# DF Dictionary content

Content updates for my personal DF Dictionary Android app.

The app checks `data.json` when it opens. If this file's `version` is newer than the content
built into the app, the app downloads it and shows "New content is ready".

- `data.json`: every glossary term and game review, plus a `version` timestamp.
