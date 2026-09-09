# Flume — release binaries

Public download host for the [Flume](https://idiaz.io/flume/) desktop app.

**This repository contains release binaries only — no source code.**
Flume's source is private; this repo exists purely so installers are
downloadable without a GitHub account.

Downloads: https://idiaz.io/flume/download.html

Each release holds:
- `Flume-<version>-win-setup.exe` — Windows installer (x64)
- `Flume-<version>-mac.dmg` — macOS disk image

Assets here are published automatically by CI and are referenced by the
app's updater and the public download endpoint, both of which fetch them
anonymously. **Do not make this repository private** — that breaks every
download and every auto-update.
