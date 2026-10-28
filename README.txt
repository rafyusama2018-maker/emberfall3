HOW TO GET YOUR APK (about 10 minutes, no coding)

1. Make a free account at github.com and click New repository.
   Name it "emberfall", keep it Public, click Create repository.

2. Unzip this kit. On the new repo page click "uploading an existing file".
   Drag in: main.py, buildozer.spec, and the whole ".github" folder
   (if your computer hides folders starting with a dot, see step 2b).
   Click Commit changes.

   2b. Alternative for the workflow file: Add file > Create new file,
       type  .github/workflows/build.yml  as the name, paste in the
       contents of build.yml from this kit, and commit.

3. Click the Actions tab. A build called "Build APK" starts by itself.
   First build takes 20-40 minutes.

4. When it shows a green check, open it, scroll to Artifacts, download
   "emberfall-apk" (a zip). Unzip it to get the .apk.

5. Send the .apk to your phone, tap it, and allow "install unknown apps"
   when asked.

If the build shows a red X, open it, copy the last ~40 lines of the log,
and paste them back to Claude to get a fix.
