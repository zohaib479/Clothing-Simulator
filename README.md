# Clothing Simulator Android App

Native Android WebView wrapper for:

https://virtu-fit-three.vercel.app/

## Features

- App name: Clothing Simulator
- Custom launcher icon
- Internet access
- JavaScript + DOM storage
- Android gallery/file picker for HTML `<input type="file">`
- Camera permission support for WebView camera requests
- Android back button navigates WebView history
- No browser address bar

## Build locally

Requirements:
- Android Studio / Android SDK
- JDK 17
- Gradle 8.x compatible with Android Gradle Plugin 8.7.3

Open the project in Android Studio and build:

Build > Build Bundle(s) / APK(s) > Build APK(s)

Or, with Gradle installed:

    gradle assembleDebug

APK:
    app/build/outputs/apk/debug/app-debug.apk

## Cloud build

This repository includes `.github/workflows/build-apk.yml`.
Push the project to GitHub, then open:
Actions > Build Clothing Simulator APK > Run workflow.

The APK will be uploaded as a workflow artifact.
