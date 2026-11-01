# GitHub Android APK Starter

This is a minimal native Android app project. It is designed to be uploaded to GitHub from a phone and built in the cloud using GitHub Actions.

## Build an APK

1. Create a new GitHub repository.
2. Upload the contents of this ZIP (not the ZIP file itself) to the repository root.
3. Make sure the workflow file is located at `.github/workflows/build-apk.yml`.
4. Open the repository's **Actions** tab.
5. Select **Build Android APK**, then tap **Run workflow** if it has not started automatically.
6. Open the completed workflow run and download the `MyFirstApp-debug-apk` artifact.
7. Extract the downloaded artifact ZIP to get `app-debug.apk`.

## Important

- This is a starter/demo app, not a finished business app.
- The workflow creates a debug APK for testing and installation.
- For a public production release, create and securely use an Android signing key; never upload passwords or keystore files publicly.
- Change the app name, package ID, design and features before publishing.
