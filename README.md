# Deck releases

Android alpha builds of Deck: APKs and release notes only. The app source is not here.

Install: download the APK from the latest release and open it on your phone. After 1.0-alpha.5, the app offers new versions itself when it opens.

Each release carries `version.json` (`versionCode`, `versionName`, `notes`, `apkUrl`), which the app reads from `releases/latest/download/version.json`. Publish releases as full releases, not pre-releases, or the app will not see them.
