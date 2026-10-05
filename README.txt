PORTFOLIO SAYT (React, statik)

1) Ishlarni qo'shish
   - Rasmlarni "works" papkasiga tashlang (masalan logo1.jpg).
   - works.json faylida har bir ish uchun bitta qator yozing:
     { "sec": "graphic" yoki "web", "cat": "Logotip", "t": "Nomi", "url": "works/logo1.jpg" }
   - Graphic Design turlari: Logotip, Visitka, Instagram post, Banner, Brend
   - Web-Design turlari: Landing page, Onlayn do'kon, UI/UX, Admin panel
   - works.json dagi ikkita qator namuna. Rasmlari yo'q bo'lsa o'chirib tashlang.
     Fayl bo'sh ([]) bo'lsa demo kartalar ko'rinadi.

2) Ma'lumotlarni o'zgartirish: index.html ichidagi "SHU YERNI O'ZGARTIRING"
   qismida NAME, TG (telegram), PHONE bor.

3) Ishga tushirish
   - index.html ni ikki marta bosib ochsangiz works.json yuklanmaydi.
     VS Code'da "Live Server" bilan yoki hostingda (Vercel, Netlify, GitHub Pages) oching.
   - Internet kerak: React kutubxonasi cdnjs.cloudflare.com dan yuklanadi.

Eslatma: bu versiyada admin "+" paneli yo'q (u backend talab qiladi).
