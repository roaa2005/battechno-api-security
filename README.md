# battechno-api-security
E-Commerce API - Security Implementation
مشروع متجر إلكتروني يعتمد على Node.js و Express، تم تطبيق معايير أمنية شاملة عليه لحماية البيانات والتحكم في الصلاحيات.

المتطلبات الأساسية
Node.js (v18 أو أحدث)
قاعدة بيانات PostgreSQL (تم استخدام Neon)

تثبيت الحزم:


npm install
إعداد متغيرات البيئة:
انسخ ملف .env.example وسمّه .env.
ضع إعدادات قاعدة البيانات (DATABASE_URL) ومفتاح الـ JWT (JWT_SECRET) في ملف .env.
تشغيل المشروع:


npm run dev
سيتم تشغيل السيرفر على المنفذ 3000.
التحسينات الأمنية المطبقة
حماية متغيرات البيئة باستخدام .env و .gitignore.
التحقق من المدخلات (Input Validation) باستخدام Zod.
منع ثغرات SQL Injection باستخدام Parameterized Queries.
تشفير كلمات المرور باستخدام Bcrypt.
المصادقة (Authentication) باستخدام JWT.
التفويض (Authorization) لفصل صلاحيات الأدمن عن الزبون.
منع ثغرات IDOR (الوصول الأفقي غير المصرح به).
إعداد Security Headers باستخدام Helmet.
ضبط CORS لتحديد المصادر المسموح بها.
تحديد معدل الطلبات (Rate Limiting) لمنع هجمات Brute Force.
معالجة أخطاء مركزية تخفي تفاصيل النظام (Stack Trace).

### الملف الثالث: `Web_Security_Testing_Report.pdf`
