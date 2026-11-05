Madoox Regime - Android project
1. Install Android Studio. Choose File > Open and select this folder.
2. Let Gradle sync, then press Run (emulator or USB phone).
3. Build > Build APK(s) for an installable .apk.
The web app lives in app/src/main/assets/index.html - replace it to update the app.
Note: cloud-only features (shared database, Claude replies, save downloads) are not available
inside the app until you add your own backend. Without a database, any email/password logs in locally.

NO ANDROID STUDIO? Build the APK online for free:
1. Create a GitHub repository and upload everything in this folder (including the hidden .github folder).
2. Open the Actions tab, run "Build APK" (it also runs on every upload).
3. When it finishes, open the run and download the "MadooxRegime-apk" artifact. Unzip it to get app-debug.apk.
4. Copy app-debug.apk to your phone and install it (allow "Install unknown apps").

FIREBASE (real accounts): see FIREBASE-SETUP.txt next to this folder. index.html here already contains the Firebase version.
