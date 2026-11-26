SOHEL SOUND PRO — Android Studio Project (প্রথম APK source)

এই ZIP হলো Android Studio project source; এটি নিজে থেকে APK নয়।

যা কাজের ভিত্তি হিসেবে যুক্ত:
- আপনার দেওয়া প্রোফাইল ছবি-সহ Purple soundboard UI
- Android audio file picker দিয়ে নিজের অডিও নির্বাচন
- WebView-এ UI চালানো

এখনো যুক্ত/পরীক্ষিত নয়:
- অন্য অ্যাপের ওপর Floating Bubble / Overlay permission ও service
- Free Fire-এর voice chat-এ অ্যাপের শব্দ পাঠানো
- ব্যাকগ্রাউন্ডে দীর্ঘসময় অডিও চালানোর foreground service
- APK build, signed release এবং বাস্তব ফোনে পরীক্ষা

APK বানাতে:
1. Android Studio-তে এই ফোল্ডারটি Open করুন।
2. Gradle Sync শেষ হতে দিন।
3. Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
4. Build সফল হলে Android Studio APK-এর অবস্থান দেখাবে।

নোট: Free Fire voice chat-এ সাউন্ড পাঠানো Android-এ সাধারণভাবে নিশ্চিত নয়। আলাদা device/game test দরকার।
