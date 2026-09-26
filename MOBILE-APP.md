# Cosmic Quiz Android app

This repository contains a full copy of the Cosmic Quiz Master website and a small Android WebView app that opens the existing mobile experience at the live Cosmic site.

## Phone features

- Cosmic Quiz mobile pages and quiz libraries
- Back-button navigation through quiz pages
- HTML, JSON, PDF, and image file picker for import and study tools
- Loading indicator and a tap-to-retry network error screen
- External links open in the phone browser

The app needs an internet connection because quiz content is hosted on the Cosmic website.

## Get the installable APK

1. Open the repository's Actions tab.
2. Open the latest Build Cosmic Quiz Android app run.
3. Under Artifacts, download the cosmic-quiz-android-debug-signed artifact and unzip it.
4. Open app-debug.apk on an Android phone to install it. Android may ask you to allow installs from that browser or file manager.

Each successful workflow run signs the APK with Android's automatically generated debug certificate. This is suitable for direct testing and phone installation. It is not a Play Store release signature; publishing to Google Play needs a separately managed private release/upload key, which must stay private and be backed up.

## Source project

The Android Studio project is under android/. The APK build workflow is .github/workflows/android-apk.yml.
