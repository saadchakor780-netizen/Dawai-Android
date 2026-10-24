# دوائي | Dawaï — Android wrapper

This Android project opens the existing Dawaï medication reminder website in an Android WebView.

Website: https://dawa-reminder.hatchable.site

## Build APK

GitHub Actions builds a debug APK after files are pushed to `main`. Open the **Actions** tab, select **Build Dawai APK**, open a successful run, and download the `Dawai-Android-APK` artifact.

Important: this initial build wraps the website. Browser-based notifications may not fire reliably when the app is closed; native Android alarm scheduling is not included in this initial version. This app is a reminder aid and does not replace instructions from a doctor or pharmacist.
