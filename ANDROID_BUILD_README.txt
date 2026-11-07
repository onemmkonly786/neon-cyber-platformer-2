NEON CYBER PLATFORMER - ANDROID APK BUILD

This package contains the 50-level Neon Cyber Platformer web game plus a GitHub Actions workflow that builds an Android APK in GitHub's cloud. You do not need Android Studio or a modern local computer; Windows 7 can be used to upload the files in a browser.

UPLOAD ALL CONTENTS OF THIS ZIP TO THE ROOT OF YOUR EXISTING GitHub repository, preserving the .github/workflows/build-apk.yml folder path. Replace the existing index.html, style.css, game.js, audio.js and particles.js when asked.

Then:
1. Open your repository on GitHub.
2. Click the Actions tab.
3. If prompted, enable GitHub Actions for the repository.
4. Select "Build Neon Cyber Android APK" from the left side.
5. Click "Run workflow" and then the green "Run workflow" button.
6. Wait for the run to finish successfully.
7. Open the completed workflow run and find Artifacts.
8. Download "Neon-Cyber-Platformer-APK.zip" and extract it. The APK inside is app-debug.apk.
9. Transfer the APK to your Android phone and install it. You may need to allow installation from your browser or file manager when Android asks.

The game is bundled locally in the app. The APK does not need GitHub Pages or an internet connection to play after installation. Internet is needed to build/download the APK. This is a debug APK for personal testing, not a Play Store release-signed APK.
