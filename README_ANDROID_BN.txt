CIVIL MATERIAL CALCULATOR ANDROID PROJECT — VERSION 2.0
=======================================================

এই ZIP-এ Android Studio project source দেওয়া হয়েছে। এই পরিবেশে Android SDK/Gradle build system নেই, তাই এখানে compiled APK তৈরি করা সম্ভব হয়নি।

APK তৈরি করার নিয়ম:
1. Windows PC-তে Android Studio ইনস্টল করুন।
2. এই ZIP Extract করুন।
3. Android Studio > Open > Extract করা CIVIL_MATERIAL_CALCULATOR_ANDROID ফোল্ডার নির্বাচন করুন।
4. Gradle sync শেষ হতে দিন। প্রয়োজন হলে Android SDK Platform 35 ইনস্টল করুন।
5. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
6. Build সম্পূর্ণ হলে app/build/outputs/apk/debug/app-debug.apk ফাইল পাবেন।
7. APK ফোনে কপি করে ইনস্টল করুন। ফোনে প্রয়োজন হলে এই উৎস থেকে Install unknown apps অনুমতি দিন।

অ্যাপের বৈশিষ্ট্য:
- Offline HTML calculator packaged inside Android app
- Wall, Road, PCC, RCC Slab, Column, Beam, Footing
- WebView JavaScript ও DOM storage enabled
- Browser localStorage-এ হিসাব সংরক্ষণ

নোট:
- APK build করতে Android Studio এবং Android SDK প্রয়োজন।
- এই প্রজেক্টটি Android Studio-তে খোলার উপযোগী source project; এটি নিজে থেকে APK নয়।
- Structural design/BBS-এর বিকল্প নয়। RCC steel quantity অবশ্যই approved drawing অনুযায়ী যাচাই করুন।
