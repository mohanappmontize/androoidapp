# Crea Starter Android App

This is a tiny native Android app designed to build in the cloud so you do not need Android Studio, Java, Gradle, or the Android SDK installed locally.

## Build APK With Almost No Local Storage

1. Open this repository on GitHub.
2. Go to **Actions**.
3. Select **Build APK**.
4. Click **Run workflow**.
5. When it finishes, open the workflow run and download the `crea-app-debug-apk` artifact.

The APK will be inside that downloaded artifact as:

```text
app-debug.apk
```

## Customize

- App name: `app/src/main/res/values/strings.xml`
- Main screen text: `app/src/main/java/com/example/creaapp/MainActivity.java`
- Package name: `app/build.gradle` and `app/src/main/AndroidManifest.xml`

## Current App

The first screen says **Crea App** and is ready for your real app idea.
