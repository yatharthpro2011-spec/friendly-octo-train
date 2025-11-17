HotwordLauncher - Foreground hotword listener (Kotlin)

This project listens for "alexa" and "hey google" using Android SpeechRecognizer while the app runs in foreground.

Build locally:
1. Open Android Studio.
2. Create new project or replace files.
3. Run on device with RECORD_AUDIO permission.

If you want an APK via GitHub Actions, upload this repository to GitHub and use a workflow that runs `./gradlew assembleDebug`.
Note: You may need to configure the Android SDK on the Actions runner.
