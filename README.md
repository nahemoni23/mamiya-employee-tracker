# Mamiya Employee Tracker — Offline Flutter App

Features:
- Daily attendance: Present / Absent / Leave
- OT tracker: 0–3 hours per day
- Company vehicle: received / not received
- Vehicle fare tracking
- Monthly dashboard
- Monthly reports
- Weekly fare summary
- Edit/Delete daily records
- Local SQLite database; no internet required

## Run
1. Install Flutter.
2. Extract this ZIP.
3. Open the folder in Android Studio or VS Code.
4. Run:
   flutter create --platforms=android .
   flutter pub get
   flutter run

## APK
flutter build apk --release

Then find:
build/app/outputs/flutter-apk/app-release.apk

Important:
Records are stored locally on the phone. Back up important data before uninstalling/resetting the app.
