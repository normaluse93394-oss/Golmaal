# Golmaal — APK Build Ready

This package contains the Golmaal Flutter source and a GitHub Actions workflow.

## Build an APK from an Android phone

1. Create/sign in to a GitHub account.
2. Create a new repository, e.g. `golmaal`.
3. Upload all files from this ZIP to the repository.
4. Open the repository's **Actions** tab.
5. Select **Build Golmaal APK**.
6. Tap **Run workflow**.
7. Wait for the workflow to finish.
8. Open the completed workflow run and download the `golmaal-apk` artifact.
9. Extract it on your phone. The APK inside can then be installed.

## Important

This is the demo/offline version. It has the Golmaal chat UI and local demo messages.
Real accounts, cloud messaging, media uploads and push notifications still require
Firebase configuration.
