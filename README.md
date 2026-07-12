# 📱 DainikState Mobile App

**DainikState** का official Android app — राज्य की आवाज़, अब आपके मोबाइल पर।

## 🚀 कैसे APK बनाएं (3 मिनट में)

### Step 1: GitHub पर push करें
```bash
git init
git add .
git commit -m "DainikState app"
git branch -M main
git remote add origin https://github.com/samirrmt44-eng/dainikstate-app.git
git push -u origin main
```

### Step 2: GitHub Actions automatic APK बनाएगा
- Repo के **Actions** tab पर जाएं
- "Build DainikState APK" workflow अपने आप चलेगा
- 5-7 minute wait करें
- पूरा होने पर **Artifacts** section में "DainikState-APK" दिखेगा
- Download करें → `app-debug.apk` यह है आपका APK

### Step 3: Mobile में install करें
1. APK file अपने फोन में भेजें (WhatsApp/USB/Drive)
2. "Install from unknown sources" allow करें
3. APK पर tap करें → Install

## ✨ Features
- 🏠 **Direct site load** - DainikState site app में खुलती है
- ⚡ **Splash screen** - DainikState logo के साथ
- 📡 **Offline detection** - नेट नहीं तो friendly error
- 🔙 **Back button support** - Android back button काम करता है
- 🎤 **Mic/Camera** - Voice comments के लिए permission पहले से
- 💾 **localStorage** - Login session save रहता है
- 🌐 **Full PWA** - सारे features काम करते हैं

## 🛠 Tech
- Capacitor 6 (Android WebView wrapper)
- No native code - पूरा web app है
- APK ~ 5-7 MB
- Android 5.0+ supported
