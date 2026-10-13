# NEXORA — Modern UI (GitHub Pages Ready)

এই প্রজেক্টটি NEXORA ওয়েবসাইটের জন্য একটি responsive, আধুনিক static front-end demo।

## ফাইলগুলো
- `index.html` — ওয়েবসাইটের কাঠামো ও demo content
- `style.css` — responsive layout, colours, cards ও mobile styling
- `script.js` — menu, search, like demo, share action ও Login/Sign Up dialog
- `README.md` — এই নির্দেশনা

## GitHub-এ আপডেট করার নিয়ম
1. ZIP ফাইলটি download করে Extract করুন।
2. আপনার repository খুলুন: https://github.com/mdm600087-blip/nexora-social
3. **Add file → Upload files** নির্বাচন করুন।
4. `nexora-modern-v2` ফোল্ডারের ভেতর থেকে `index.html`, `style.css`, `script.js` এবং চাইলে `README.md`-ও upload করুন। ফাইলগুলো repository-র root-এ রাখবেন; পুরো folder-টি nested অবস্থায় upload করবেন না।
5. **Commit changes** চাপুন। Pages যে branch/folder থেকে publish হচ্ছে, সেই জায়গাতেই ফাইলগুলো replace করতে হবে।
6. এক-দুই মিনিট অপেক্ষা করে https://mdm600087-blip.github.io/nexora-social/ refresh করুন। পুরোনো version থাকলে hard refresh করুন: Windows/Linux `Ctrl + Shift + R`.

## কী কাজ করে?
- Login ছাড়াই public demo content দেখা যায়
- Mobile navigation menu
- Sample post search
- Like button-এর local visual interaction
- Share button (browser support থাকলে)
- Login / Sign Up modal-এর visual flow

## গুরুত্বপূর্ণ সীমাবদ্ধতা
এটি **front-end demo**। Login/Sign Up form এখনো বাস্তব account তৈরি বা authenticate করে না। Post, comments, stories, profiles, uploads, messages এবং likes স্থায়ীভাবে সংরক্ষণ করতে backend/API ও database দরকার। Production-এ প্রকাশের আগে secure authentication, privacy, validation, moderation এবং database যোগ করুন।

## বাইরের asset
ছবি ও Google Fonts internet থেকে load হয়। নিজের ছবি/branding ব্যবহার করতে চাইলে HTML-এর image URL এবং font imports পরিবর্তন করুন।
