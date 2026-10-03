# Evolution Studio WebView

An Android WebView application for the Evolution Studio project.

## Requirements

- Android Studio
- Android SDK
- JDK version supported by the project's Gradle configuration

## Installation

```bash
git clone https://github.com/ryoaonetsuki/evolution-studio-webview.git
cd evolution-studio-webview
```

Open the project in Android Studio and allow Gradle to sync.

## Run

Connect an Android device or start an emulator, then run the application from Android Studio.

For a command-line debug build:

```bash
./gradlew assembleDebug
```

On Windows:

```bat
gradlew.bat assembleDebug
```

## Development

The application wraps the Evolution Studio web experience in an Android WebView. Update the Android source and WebView configuration, then rebuild and test on a device.

## Notes

Use HTTPS for production web content and do not hard-code private credentials in the Android source.
