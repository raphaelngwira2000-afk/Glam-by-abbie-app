# Glam by Abbie Android app starter

This is an Android Studio project for a simple salon app. It includes:
- salon services and contact details
- direct WhatsApp booking
- an in-app appointment form that prepares a WhatsApp booking message

## Build an APK
1. Install Android Studio on a computer.
2. Open this `glam_by_abbie` folder in Android Studio.
3. Allow Gradle sync and install any requested Android SDK (compile SDK 35).
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the APK location, usually `app/build/outputs/apk/debug/app-debug.apk`.

## Important
The form sends the booking request to WhatsApp; it does not save appointments to an online database. Prices are shown as “contact for prices” until actual prices are provided. The app currently uses a simple text-based brand header; a logo and salon photo gallery can be added later.
