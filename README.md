# Merkabati Legal Pages

الصفحات القانونية والدعم الفني لتطبيق **مركبتي** — جاهزة للنشر على GitHub Pages.

---

## هيكل المشروع

```
Merkabati-Legal-Pages/
├── index.html               # الصفحة الرئيسية (روابط جميع الصفحات)
├── privacy-policy-ar.html   # سياسة الخصوصية — العربية
├── privacy-policy-en.html   # Privacy Policy — English
├── terms-ar.html            # شروط الاستخدام — العربية
├── terms-en.html            # Terms of Use — English
├── support-ar.html          # الدعم الفني — العربية
├── support-en.html          # Support — English
├── style.css                # ملف الأنماط المشترك
└── README.md                # هذا الملف
```

---

## خطوات رفع المشروع إلى GitHub

### 1. أنشئ Repository جديداً

- افتح [github.com](https://github.com) وسجّل دخولك.
- اضغط **New** أو زر **+** في الأعلى.
- سمّ الـ Repository: `merkabati-legal` (أو أي اسم تريده).
- اختر **Public** (مطلوب لـ GitHub Pages المجانية).
- اضغط **Create repository**.

### 2. ارفع الملفات

**الطريقة السهلة (عبر الموقع):**
- في صفحة الـ Repository، اضغط **Add file → Upload files**.
- اسحب جميع ملفات المجلد وأفلتها.
- اكتب في حقل Commit: `Add Merkabati legal pages`.
- اضغط **Commit changes**.

**أو عبر Git (للمطورين):**
```bash
cd Merkabati-Legal-Pages
git init
git add .
git commit -m "Add Merkabati legal pages"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/merkabati-legal.git
git push -u origin main
```

---

## تفعيل GitHub Pages

1. في صفحة الـ Repository، اذهب إلى **Settings**.
2. من القائمة الجانبية، اختر **Pages**.
3. تحت **Branch**، اختر `main` ← `/ (root)`.
4. اضغط **Save**.
5. انتظر دقيقة أو دقيقتين ثم ستظهر رسالة:
   > Your site is live at `https://YOUR_USERNAME.github.io/merkabati-legal/`

---

## المسارات النهائية للروابط

بعد التفعيل، الروابط ستكون بهذا الشكل:

| الصفحة | الرابط |
|--------|--------|
| الرئيسية | `https://YOUR_USERNAME.github.io/merkabati-legal/` |
| سياسة الخصوصية (عربي) | `https://YOUR_USERNAME.github.io/merkabati-legal/privacy-policy-ar.html` |
| Privacy Policy (English) | `https://YOUR_USERNAME.github.io/merkabati-legal/privacy-policy-en.html` |
| شروط الاستخدام (عربي) | `https://YOUR_USERNAME.github.io/merkabati-legal/terms-ar.html` |
| Terms of Use (English) | `https://YOUR_USERNAME.github.io/merkabati-legal/terms-en.html` |
| الدعم الفني (عربي) | `https://YOUR_USERNAME.github.io/merkabati-legal/support-ar.html` |
| Support (English) | `https://YOUR_USERNAME.github.io/merkabati-legal/support-en.html` |

---

## الروابط المطلوبة في المتاجر

### Apple App Store
- **Privacy Policy URL:** `https://YOUR_USERNAME.github.io/merkabati-legal/privacy-policy-en.html`
- **Support URL:** `https://YOUR_USERNAME.github.io/merkabati-legal/support-en.html`
- **Terms of Use:** `https://YOUR_USERNAME.github.io/merkabati-legal/terms-en.html`

### Google Play
- **Privacy Policy:** `https://YOUR_USERNAME.github.io/merkabati-legal/privacy-policy-en.html`
- **Support Email:** `gallayy@gmail.com`

---

## ملاحظات

- جميع الملفات تعمل مباشرةً بدون أي build step أو مكتبات خارجية.
- RTL مضبوط بالكامل في جميع الصفحات العربية.
- يمكن فتح الملفات محلياً مباشرةً في المتصفح للاختبار قبل الرفع.
- الخط المستخدم (IBM Plex Sans Arabic) يُحمَّل من Google Fonts — يحتاج اتصال إنترنت لعرضه بشكل صحيح.

---

**Developer:** Nasser Alhayyan  
**Contact:** gallayy@gmail.com  
**App:** Merkabati © 2026
