# ReadListen for Android

ReadListen reads books and PDFs aloud. All speech is made on the phone itself:
nothing you read is sent to a server, and it keeps working offline.

This repository only hosts the Android installer. It contains no source code.

## Install

You need a 64-bit Android phone (arm64) running Android 10 or newer, and about
1.5 GB of free space. The download is about 470 MB, because the voices are
built in.

1. On your phone, open the
   [latest release](https://github.com/jobfinderbyivan/readlisten-android/releases/latest)
   and tap the file ending in `.apk` (for example `ReadListen-7.1-arm64.apk`).
2. When the download finishes, open it. Android will say your browser is not
   allowed to install apps. Tap **Settings**, turn on
   **Allow from this source**, then go back and tap **Install**.
3. Open ReadListen.

After that the app updates itself: it checks for a new version about once a
day (or from the menu: **Check for updates**) and asks before downloading
anything.

The `.sha256` file beside each APK is its checksum, if you want to check the
download.

## Had an earlier test build?

The first signed release (7.1) is signed with a new, permanent key, so Android
will not install it over an earlier test build. Do this once:

1. Back up your books in the old build.
2. Uninstall the old build.
3. Install the new APK as above.

Later updates install over the top as usual.

## License

All rights reserved. See [LICENSE](LICENSE).
