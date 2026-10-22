# Forma Android updates

This repository distributes signed Forma Android APKs and minimal update metadata only. Forma application source code remains private.

- Update feed: https://ribhavjain22.github.io/forma-android-updates/latest.json
- Immutable installers are published under `apks/` with their Android version code and SHA-256 in the filename.
- `latest.json` records the actual APK version, byte size, and SHA-256. Downloads are verified against the installed application's package and signing identity.

In Forma, open **Settings → App updates**. Automatic downloads are optional and off by default. **Check for updates** also downloads an available update. Updates never install silently: choose **Install update**, then confirm Android's installer. If Android requires **Allow from this source**, enable it, return to Forma, and press **Install update** again.

Install only a signed upgrade compatible with your existing Forma installation. Never uninstall or clear application data to resolve a signature mismatch.
