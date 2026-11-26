# Edward Photography — UTS Pemrograman Web 1

Website statis company profile studio fotografi **Edward Photography** yang dibangun menggunakan HTML5 semantik dan CSS3 murni (tanpa JavaScript) untuk memenuhi Ujian Tengah Semester (UTS) Pemrograman Web 1.

## Identitas

| Keterangan | Detail |
| :--- | :--- |
| **Nama** | Rizaldy Adiyadma |
| **NPM** | 2510010023 |
| **Kelas** | 3A NonReguler Banjarbaru |
| **Mata Kuliah** | Pemrograman Web 1 — Ganjil T.A. 2026/2027 |
| **Dosen** | Dr. Muharir, S.Kom., M.Kom. |
| **Program Studi** | Teknik Informatika, FTI — Universitas Islam Kalimantan Muhammad Arsyad Al Banjari |

## Struktur Folder

```text
uts_web1_2510010023/
├── index.html          # Beranda (Hero, 6 kartu layanan, testimoni)
├── produk.html         # Katalog paket per kategori (sticky subheader)
├── kontak.html         # Formulir reservasi, tabel harga, peta lokasi
├── css/
│   └── style.css       # Stylesheet eksternal tunggal (mobile-first + dark mode)
├── img/                # Aset foto lokal (7 gambar)
└── screenshot/         # Bukti tampilan aplikasi berjalan
```

## Fitur & Ketentuan UTS

- **Multi-halaman & Semantik HTML5:** `index.html`, `produk.html`, dan `kontak.html` saling tertaut dengan `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>` + `<figcaption>`, `<time>`, dan `<footer>`.
- **Navbar Fixed & Hamburger CSS-Only:** Tetap tampak saat scroll (`position: fixed` + kompensasi `padding-top`), berubah menjadi menu hamburger berbasis checkbox (`#menu-toggle`) di mobile.
- **Layout Flexbox & CSS Grid:** Hero flexbox terpusat, 6 kartu layanan dalam CSS Grid (`border-radius`, `box-shadow`, hover `transition` + `transform`), serta subheader `position: sticky`.
- **Form, Tabel & Peta:** Form berlabel lengkap (`<fieldset>`, `<legend>`, `required`, `select`, `textarea`, `submit` & `reset`), tabel 6 baris (`<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `rowspan` & `colspan`), dan embed Google Maps `<iframe>`.
- **Responsif & Dark Mode:** Mobile-first (`@media (min-width: 768px)` & `1024px`), tanpa overflow horizontal di `360px`, palet 4 warna (`#FF4A17`, `#273D4E`, `#F1F4FA`, `#FFFFFF`), Google Fonts (`Raleway` & `Roboto`), serta dark mode otomatis via `@media (prefers-color-scheme: dark)`.

## Cara Menjalankan

1. Clone atau unduh repository ini.
2. Buka langsung `index.html` di browser, atau jalankan lewat **VS Code Live Server**.

## Screenshot

### Beranda (Desktop)
![Tampilan Beranda](screenshot/Screenshot%20Beranda.png)

### Kontak & Daftar Layanan (Desktop)
![Tampilan Kontak](screenshot/Screenshot%20Kontak.png)

### Peta Lokasi & Footer
![Tampilan Peta dan Footer](screenshot/Screenshot%20Peta%20%2B%20Footer.png)

### Responsif Mobile (360px) & Menu Hamburger CSS-Only
| Mobile 360px | Hamburger Terbuka |
| :---: | :---: |
| ![Tampilan Mobile 360px](screenshot/Screenshot%20360px.png) | ![Menu Hamburger CSS-Only](screenshot/Screenshot%20Hamburger.png) |
