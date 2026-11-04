UNIVERSAL MENSWEAR CHECKLIST — ANDROID PROJECT

This project wraps the existing editable checklist in a native Android WebView app.
All checklist inputs remain editable. The form stores entries locally on the device
using browser localStorage and works without an internet connection.

BUILD AN APK WITH ANDROID STUDIO
1. Install the latest Android Studio on a Windows, Mac or Linux computer.
2. Extract this ZIP.
3. In Android Studio choose File > Open and select the extracted
   UniversalMenswearChecklist folder (the folder containing settings.gradle).
4. Allow Android Studio to sync Gradle and install any requested Android SDK
   Platform 35 / build tools.
5. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When the build completes, choose 'locate' in the notification.
   The debug APK is normally at:
   app/build/outputs/apk/debug/app-debug.apk
7. Transfer app-debug.apk to the Android phone and open it to install.
   You may need to allow installation from that file manager/browser.

FOR A SIGNED RELEASE APK
Use Build > Generate Signed Bundle / APK in Android Studio, choose APK,
and create/store a signing key securely. Do not share the private key.

APP DETAILS
- App name: UM Checklist
- Package: com.universalmenswear.checklist
- Minimum Android: Android 6.0 (API 23)
- Version: 1.0
- Checklist data is stored locally on the phone. Clearing app storage or
  uninstalling the app may erase saved records; export/print records as needed.

LIMITATION
This environment does not have the Android SDK or Gradle build tool installed,
so it cannot compile and sign the APK here. This ZIP is a complete Android Studio
project ready for building on a computer with Android Studio.
