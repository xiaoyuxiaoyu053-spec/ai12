# DeepLine 2.1.5 — WeChat-style UI integration baseline

- Android package: `com.deepline.privateapp`
- Version: `2.1.5` (versionCode 14)
- Project baseline: previous DeepLine 2.0.0 project.
- Includes the existing AI/chat/feed/settings implementation, API configuration, local persistence, and GitHub Actions build workflow.

## Build
Open `android/` in Android Studio with Android SDK installed, or run the included GitHub Actions workflow.

## Verification status
This archive has not been compiled or tested on a device in this environment. The version number is updated, but the full requested UI/function checklist still requires implementation and device verification; do not treat this archive as a fully verified final release.


## App icon
- Added the supplied image as the launcher icon.
- Android 8+ uses an adaptive icon so the launcher applies the device mask (circle, squircle, etc.) automatically; older Android versions use density-specific PNG icons.
- Build status: not compiled in this environment; run the included GitHub Actions workflow or `gradle assembleDebug` in the `android` directory to verify.
