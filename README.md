## Babel: Til Tarjima Vositasi

### Kirish
Babel - dasturlash dunyosida mashhur bo'lgan JavaScript transpileri bo'lib, zamonaviy JavaScript kodini eski brauzerlarda ishlatiladigan versiyalarga aylantirish uchun ishlatiladi. Bu jarayon kodni eshlovchi mashinalarga moslab o'zgartiradi va dasturchilarga zamonaviy JavaScript'ning yangi imkoniyatlarini to'liq ishlatishga yordam beradi.

### Babel'ning Asosiy Xususiyatlari
- **Transpilyatsiya**: Babel ES6 yoki undan yangi JavaScript kodini eski ES5 kodiga o'giradi, bu esa eski brauzerlarda ham ishlash imkoniyatini yaratadi.
- **Plaginlar**: Babel turli xil plaginlar yordamida kengaytirilishi mumkin, bu esa faqat kerakli xususiyatlarni qo'llash imkoniyatini beradi.
- **Polyfills**: Babel "polyfill" lar orqali yangi funksiyalarni eski muhitlarga qo'shish imkonini beradi.
  
### Ishlash Tartibi
1. **Kiruvchi Kod**: Siz yozgan zamonaviy JavaScript kodini Babel oladi.
2. **Parsers**: Kodni o'qish va sintaktik daraxtga (AST - Abstract Syntax Tree) aylantirish uchun foydalaniladi.
3. **Plaginlar va Presetlar**: AST ustida o'zgartirishlar qilish uchun ishlatiladi.
4. **Kod Generatsiyasi**: Yangi AST ga asoslangan holda eski kodni generatsiya qiladi.

### O'rnatish va Ishlatish
Babel'ni loyihangizga qo'shish juda oson:
```bash
npm install --save-dev @babel/core @babel/cli @babel/preset-env
