# China Academic World — Coming Soon

Official Coming Soon page for **chinaacademic.world**

## Contact
- **Name:** SELIM PERVEJ
- **WhatsApp (China):** +86 156 1846 1178
- **WhatsApp:** 01515 629045
- **Location:** Yiwu City, Zhejiang, China

---

## Deploy করবেন যেভাবে চান

### 1. GitHub Pages (সবচেয়ে সহজ ও ফ্রি)

1. GitHub-এ নতুন Repository তৈরি করুন (নাম দিতে পারেন: `chinaacademic-world`)
2. এই ফোল্ডারের সব ফাইল আপলোড করুন (বা Git push করুন)
3. Repository → **Settings** → **Pages**
4. Source: **Deploy from a branch**
5. Branch: `main` → `/ (root)` সিলেক্ট করুন → Save
6. কয়েক মিনিট পর সাইট লাইভ হবে:  
   `https://yourusername.github.io/chinaacademic-world`

> কাস্টম ডোমেইন (`chinaacademic.world`) কানেক্ট করতে চাইলে Pages সেটিংসে Custom domain অপশন ব্যবহার করুন।

---

### 2. Vercel (খুব সহজ + কাস্টম ডোমেইন সাপোর্ট)

1. [vercel.com](https://vercel.com) এ যান → GitHub দিয়ে Login
2. **Add New Project** → আপনার GitHub Repo সিলেক্ট করুন
3. Deploy বাটনে ক্লিক করুন
4. কাস্টম ডোমেইন: Project Settings → Domains → `chinaacademic.world` যোগ করুন

---

### 3. Netlify (ড্র্যাগ & ড্রপও করা যায়)

1. [netlify.com](https://netlify.com) এ যান
2. GitHub Repo কানেক্ট করুন অথবা সরাসরি ফোল্ডার ড্র্যাগ করুন
3. Deploy
4. Domain settings থেকে `chinaacademic.world` কানেক্ট করুন

---

### 4. Railway

1. [railway.app](https://railway.app) এ নতুন Project তৈরি করুন
2. GitHub Repo কানেক্ট করুন
3. Railway স্বয়ংক্রিয়ভাবে `npm start` চালিয়ে সাইট লাইভ করবে

---

## Local এ দেখতে চাইলে

```bash
npm install
npm start
```

ব্রাউজারে `http://localhost:3000` খুলবে।

---

## ফাইল স্ট্রাকচার

```
chinaacademic-world/
├── index.html      ← মূল পেজ
├── package.json    ← Railway / local এর জন্য
└── README.md       ← এই ফাইল
```
