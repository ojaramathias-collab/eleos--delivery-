ELEOS DELIVERY V3 — ANDROID PROJECT
==================================
This is an Android Studio project/source package, not a compiled APK.
It creates an offline-first Android app shell with locally stored browser data.
The app is designed to be built into a debug APK using Android Studio or GitHub Actions.

BUILD WITH GITHUB (easiest from Android phone)
1. Extract this ZIP.
2. Create/sign in to a GitHub account and create a new repository named EleosDelivery.
3. Upload the CONTENTS of the EleosDeliveryAndroid folder to the repository root.
4. Open the repository's Actions tab.
5. Select "Build Eleos Android APK" and tap "Run workflow".
6. When complete, open the workflow run and download the "Eleos-Delivery-APK" artifact.
7. Extract the downloaded artifact ZIP; install app-debug.apk on the phones.
   Android may ask permission to install unknown apps. Only install your own build.

APP ACCESS
- Owner PIN: 2468
- Rider PIN: 1357
These are starter PINs, not secure production authentication. Change them before real business use.
The app stores records on each phone locally. There is NO automatic cloud sync between the two phones in this build.
GPS sharing is a foreground/manual action: rider must allow location permission and tap Start GPS while working.
GPS requires internet for the location-sharing link; local delivery records remain available offline.

IMPORTANT LIMITATIONS
- This is an MVP/test build project, not a production dispatch platform.
- Owner/rider records on separate phones do not synchronize automatically.
- Live background tracking, secure remote accounts, server-side order assignment, push notifications,
  encryption, and production backup hosting still need a backend and additional Android testing.
- Never use starter PINs for sensitive business records.
