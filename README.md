# BLOVY AI — Android project

This is the source project for packaging the BLOVY AI Basic web app as an Android APK.

## Build APK from a phone using GitHub Actions

1. Create a GitHub repository and upload all files in this folder, including the hidden `.github` folder.
2. Open the repository's **Actions** tab.
3. Select **Build BLOVY AI APK**.
4. Tap **Run workflow** and wait for the workflow to finish.
5. Open the completed workflow run, find **Artifacts**, and download `BLOVY-AI-debug-APK`.
6. Extract the downloaded artifact ZIP to obtain `app-debug.apk`, then install it on your Android phone if Android permits installation from that source.

## Important

- This is a debug APK for personal testing, not a Play Store release.
- The Basic app currently uses simple local replies; it is not connected to a real AI model.
- Never put a private AI API key in `www/index.html` or other client-side files.
- App package ID: `com.blovy.ai`
