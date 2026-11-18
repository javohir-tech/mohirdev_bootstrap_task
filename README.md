# DashboardKit — Bootstrap amaliy ish

HTML, CSS va Bootstrap 5 yordamida tayyorlangan to'rt sahifali o'quv loyihasi: asosiy Dashboard va topshiriqdagi uchta komponent sahifasi.

## Ochish

ZIP arxivni to'liq oching va `index.html` faylini brauzerda ishga tushiring.
Internet, terminal, npm yoki server kerak emas. VS Code Live Server bilan ham ochish mumkin.

## Sahifalar

- `index.html`: Dashboard sale. Statistika kartochkalari, savdo grafigi, mijozlar fikri diagrammasi, mahsulotlar jadvali va xabarlar.
- `buttons.html`: Elements → Basic → Buttons. Ranglar, outline, disabled, o'lchamlar, dropdown va button group misollari.
- `form-elements.html`: Forms → Form elements. Input, select, textarea, rang, datalist, checkbox, radio, switch, range va input group misollari.
- `tables.html`: Table → Bootstrap table. Oddiy, qoramtir, hover, striped va rangli jadvallar.

## Fayllar

- `css/bootstrap.min.css`: tayyor Bootstrap 5.3.9 kutubxonasi. Bu faylni tahrirlash shart emas.
- `css/style.css`: loyiha uchun yozilgan stillar. Menyu, ranglar, kartochkalar va mobil ko'rinish shu yerda.
- `images/`: lokal logotip va avatar.
- `images/icons/`: oddiy SVG ikonlar.
- `images/charts/`: JavaScriptsiz ko'rsatiladigan lokal SVG grafiklar.
- `fonts/`: lokal Inter shriftlari.
- `licenses/`: Bootstrap va Inter litsenziyalari.

## Kod qanday ishlaydi?

- `row`, `col-md-6`, `col-lg-6` klasslari Bootstrap grid tizimi orqali ustunlarni moslashtiradi.
- `card`, `btn`, `form-control`, `form-select`, `input-group` va `table` klasslari Bootstrap komponentlaridir.
- Menyuda oddiy HTML havolalar ishlatilgan. Hozirgi sahifada `active` klassi va `aria-current="page"` bor.
- Dashboard bosh sahifa hisoblanadi. Basic bo'limidan Buttons, Forms Elements bo'limidan Form Basic ochiladi.
- Dashboard raqamlari demo ma'lumotlaridir. Grafiklar statik SVG: zoom va jonli yangilanish yo'q. Oylik grafik tagidagi `View chart data` bo'limi haqiqiy HTML jadvalini ochadi.
- Ochiladigan bo'limlar `details` va `summary` bilan ishlaydi.
- Telefon menyusini checkbox va CSS `:checked` selektori ochadi.
- JavaScript ishlatilmagan. Formalarning `required`, `type="email"` va `minlength` tekshiruvlarini brauzer bajaradi.
- Forma namunalarida shaxsiy ma'lumot maydonlarining `name` atributi yo'q: kiritilgan ism, email va parol URLga yuborilmaydi. Bu saqlash, ro'yxatdan o'tish yoki login tizimi emas.
- Formani to'g'ri to'ldirib yuborganda sahifa ichidagi namuna xabari ko'rinadi. Jadval saralash va serverga saqlash funksiyalari yo'q.
- Tugmalar sahifasidagi oddiy tugmalar dizayn namunasi. Dropdown havolalari lokal sahifa yoki shu sahifadagi bo'limga o'tadi.

## Manba

Dizayn uchun berilgan DashboardKit demosi namuna sifatida ishlatildi:
https://www.mgtechnologies.co.in/demo/dashboardkit-free-bootstrap-5-admin-template

Logotip, avatar, mahsulot rasmlari va grafiklar uchun namuna qiymatlar shu demo saytdan olingan. Grafiklar lokal SVG sifatida qayta chizilgan. Loyiha o'quv mashqi uchun qayta yozilgan; original DashboardKit bilan rasmiy aloqasi yo'q.

Bootstrap: https://getbootstrap.com/
Inter: https://rsms.me/inter/

HTML va CSS ichidagi bo'lim izohlari kodni o'rganish va o'zgartirishni osonlashtiradi.
