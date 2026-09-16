# Tair Mobile - تطبيق موبايل

تطبيق React Native متقدم يعمل على **Android** و **iOS**

## 📱 المميزات

- ✅ يعمل على Android و iOS
- ✅ واجهة مستخدم حديثة
- ✅ أداء عالي
- ✅ سهل التطوير والصيانة

---

## 🚀 البدء السريع

### المتطلبات
- Node.js (v14 أو أحدث)
- npm أو yarn
- Android Studio (لـ Android)
- Xcode (لـ iOS)

### التثبيت

```bash
git clone https://github.com/toop9472-lang/Tair-mobile.git
cd Tair-mobile
npm install
```

### التشغيل

**على Android:**
```bash
npm run android
```

**على iOS:**
```bash
npm run ios
```

**Metro Bundler:**
```bash
npm start
```

---

## 📁 هيكل المشروع

```
Tair-mobile/
├── src/              # الأكواد المصدرية
├── android/          # أكواد Android
├── ios/              # أكواس iOS
├── App.js            # التطبيق الرئيسي
├── index.js          # نقطة الدخول
├── app.json          # الإعدادات
└── package.json      # المكتبات
```

---

## 🐛 حل المشاكل الشائعة

### خطأ في `node_modules`
```bash
rm -rf node_modules package-lock.json
npm install
```

### خطأ في Metro Bundler
```bash
npm start -- --reset-cache
```

### خطأ في Pods (iOS)
```bash
cd ios
rm -rf Pods Podfile.lock
pod install
cd ..
```

---

## 📝 ملاحظات

⚠️ **تذكر:**
- لا ترفع `node_modules/` على GitHub
- لا ترفع ملفات `.env` السرية
- اختبر على أجهزة حقيقية قبل الإطلاق

---

## 📄 الترخيص

MIT License

---

**المطور:** toop9472-lang
