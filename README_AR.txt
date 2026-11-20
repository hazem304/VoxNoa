مشروع أندرويد جاهز لتطبيق VoxNova AI Studio
==============================================

محتويات الحزمة:
- كود التطبيق الكامل داخل: app/src/main/assets/www/index.html
- كود Android WebView الجاهز مع صلاحيات الميكروفون ورفع الملفات: MainActivity.java + AndroidManifest.xml
- ملف بناء تلقائي عبر GitHub Actions: .github/workflows/build-apk.yml

طريقتان سريعتان لاستخراج ملف الـ APK:

الطريقة 1 (عبر Android Studio على الكمبيوتر):
1. فك الضغط عن الملف وافتح مجلد voxnova_android في Android Studio.
2. انتظر مزامنة Gradle، ثم اضغط: Build -> Build Bundle(s) / APK(s) -> Build APK(s).
3. ستجد ملف app-debug.apk جاهزاً للتثبيت على هاتفك.

الطريقة 2 (أونلاين بدون تثبيت Android Studio عبر GitHub Actions):
1. أنشئ مستودعاً (Repository) جديداً على GitHub وارفع محتويات مجلد voxnova_android بداخله.
2. افتح تبويب Actions في GitHub، وسيقوم ببناء ملف VoxNova-AI-Studio-APK تلقائياً لتنزيله على هاتفك مباشرة.
