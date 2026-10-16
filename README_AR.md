# موقع عيد ميلاد Mohammed / حمودي ❤️

## الملفات
- `index.html`: الموقع كاملًا (التصميم والتفاعل والنصوص في ملف واحد).

## تجربة الموقع على الموبايل
1. فكّي ضغط ملف ZIP.
2. افتحي مجلد `mohammed_birthday_website`.
3. افتحي `index.html` في المتصفح لمعاينة الموقع.

## إضافة صوركم بحيث تظهر عنده في الرابط
اختيار الصور من داخل الموقع يعرضها محليًا على جهازك فقط. لن تظهر تلقائيًا عند حبيبك. لإضافتها بشكل دائم:
1. داخل مجلد الموقع، أنشئي مجلدًا اسمه `images`.
2. ضعي الصور بداخله بأسماء بسيطة مثل `memory1.jpg` و`memory2.jpg` و`memory3.jpg`.
3. افتحي `index.html` في محرر نصوص، واستبدلي عناصر الصورة/المكان المؤقت لكل بطاقة بصورة مثل:
   `<img src="images/memory1.jpg" alt="Our memory 1" style="display:block;width:100%;height:100%;object-fit:cover">`
   واحذفي أو أخفي عنصر `.photo-placeholder` الخاص بالبطاقة. كرري ذلك للصور الثلاث.
4. لا ترفعي صورًا خاصة لا ترغبين في أن يتمكن أي شخص لديه الرابط من رؤيتها؛ رابط GitHub Pages عام.

## نشر الموقع مجانًا باستخدام GitHub Pages
1. سجّلي الدخول إلى https://github.com/ أو أنشئي حسابًا.
2. اضغطي **New repository** وأنشئي مستودعًا باسم مثل `hamoudi-birthday` واجعليه **Public**.
3. ارفعي `index.html` (ومجلد `images` إذا أضفتِ صورًا) إلى المستودع عبر **Add file → Upload files** ثم **Commit changes**.
4. افتحي **Settings → Pages**.
5. تحت **Build and deployment** اختاري **Deploy from a branch**.
6. اختاري الفرع `main` والمجلد `/(root)` ثم اضغطي **Save**.
7. انتظري حتى يكتمل النشر. سيظهر رابط شبيه بـ `https://USERNAME.github.io/hamoudi-birthday/` في صفحة Pages. استخدمي الرابط الذي يظهره GitHub فعلًا، لأن اسم المستخدم قد يغيّر الرابط.
8. افتحي الرابط من موبايلك للتجربة، ثم ابعتيه له على واتساب.

الدليل الرسمي: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## تعديل الكلام
افتحي `index.html` بمحرر نصوص وابحثي عن الجملة التي تريدين تعديلها، ثم احفظي الملف وأعيدي رفعه إلى المستودع.
