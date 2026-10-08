# Shehab — نسخة البناء من الهاتف

هذه النسخة مصممة لتجنب مشكلة:
`Plugin [id: 'com.android.application'] was not found`

## البناء من الهاتف عبر GitHub
1. ارفع محتويات هذا المجلد إلى Repository جديد على GitHub.
2. تأكد أن الملف:
   `.github/workflows/build-apk.yml`
   موجود في المستودع.
3. افتح Actions.
4. اختر `Build Shehab APK`.
5. اضغط `Run workflow`.
6. بعد نجاح العملية، افتحها وابحث عن `Artifacts`.
7. حمّل `Shehab-debug-apk.zip`.
8. فك الضغط لتحصل على `app-debug.apk`.

لا يحتاج هذا الـworkflow إلى Android Studio أو Gradle Wrapper؛ GitHub Actions يجهز JDK وAndroid SDK وGradle تلقائيًا.
