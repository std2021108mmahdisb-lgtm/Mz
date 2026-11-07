# توزيع الطحين

خطوات البناء على GitHub:
1. أنشئ مستودعاً جديداً وارفع كل ملفات هذا المجلد في الجذر.
2. تأكد أن الملف `.github/workflows/android.yml` موجود. إذا لم يظهر بعد الرفع، اضغط Add file ثم Create new file، واكتب المسار `.github/workflows/android.yml` والصق محتوى `workflow-android.yml.txt`.
3. افتح تبويب Actions ثم Build APK ثم Run workflow.
4. بعد انتهاء البناء نزّل `app-apk` من أسفل صفحة التشغيل، وفك الضغط لتجد `app-debug.apk`.
