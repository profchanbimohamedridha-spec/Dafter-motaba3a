# متابعة حصص العلوم الإسلامية – ثالثة ثانوي

تطبيق PWA ثابت (HTML/CSS/JS بلا أدوات بناء ولا خادم). البيانات في localStorage.

## GitHub
```
git init
git add .
git commit -m "class tracker: first commit"
git branch -M main
git remote add origin https://github.com/<USERNAME>/class-tracker.git
git push -u origin main
```
**GitHub Pages:** Settings ▸ Pages ▸ Branch: `main` / root ▸ Save.

## Netlify
- من المستودع: Add new site ▸ Import an existing project ▸ GitHub ▸ `class-tracker`. اترك أمر البناء فارغا، ومجلد النشر `.` (مضبوط في `netlify.toml`).
- أو سريعا: اسحب مجلد المشروع إلى app.netlify.com/drop.

## APK
بعد النشر، أدخل رابط Netlify في pwabuilder.com ▸ Android ▸ Download.

## تحديث الكاش
عند تغيير `index.html`، غيّر رقم `ct-v1` في `sw.js` (مثلا `ct-v2`) ليصل التحديث للأجهزة.
