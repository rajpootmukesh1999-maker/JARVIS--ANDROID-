# J.A.R.V.I.S. Android starter project

## Build
1. Install Android Studio.
2. Open this `JARVIS_Android` folder in Android Studio.
3. Allow Gradle sync to finish (internet is needed for the first dependency download).
4. Connect an Android phone with USB debugging enabled, or start an emulator.
5. Press Run.

The app requests microphone permission when you tap **TAP TO SPEAK**. Speech recognition uses Android's installed speech-recognition service; availability and language support depend on the device.

## Current capabilities
- Futuristic blue HUD interface with animated glowing core
- Text chat
- Speech-to-text input
- Text-to-speech replies
- Basic local responses for time, date, greetings, identity and help

## Important
This is a starter app project, not a signed APK. It does not yet connect to a cloud AI model, control phone settings, or run continuously in the background. Add an AI backend securely before using open-ended AI features; never put private API keys directly in the Android app.
