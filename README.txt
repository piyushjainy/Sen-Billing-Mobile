Sen Billing Android WebView App
===============================

Website loaded:
https://www.sensible-computers.com/sen-billing/

Features:
- Opens the website inside Android WebView
- Android Back button goes to the previous website page when possible
- Exit confirmation appears when there is no previous page
- Loading progress indicator
- Retry message for main-page loading errors
- Pages on sensible-computers.com remain in the app; external links open in another app/browser

Open the SenBillingAndroid folder in Android Studio.
Use JDK 17 and allow Gradle sync to finish.
Connect an Android phone with USB debugging enabled or use an emulator, then press Run.

To build an APK:
Build > Build Bundle(s) / APK(s) > Build APK(s)

Important:
This is a starter project. Test all Sen Billing flows (login, downloads, uploads, printing,
payment links, pop-ups and any third-party integrations) on real Android devices before release.
The app uses your existing website; website changes and server-side functionality remain on your server.
