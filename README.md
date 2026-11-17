# ONESERVE POINT Android app project

This Android Studio project wraps the supplied mobile-responsive HTML page in an Android WebView and uses the ONESERVE POINT logo extracted from the HTML as the launcher icon.

## Build APK
1. Install Android Studio (with Android SDK Platform 35 and Android Gradle Plugin-compatible JDK).
2. Open this folder in Android Studio and allow Gradle sync.
3. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. The debug APK will be at `app/build/outputs/apk/debug/app-debug.apk`.

The app loads the HTML locally from `app/src/main/assets/index.html`. Network permission is enabled for Firebase or other remote services used by the page.
