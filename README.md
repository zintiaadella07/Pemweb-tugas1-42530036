# Portofolio Pengembang Perangkat Lunak

Tugas 1 Pemrograman Web: Rancang Bangun Responsive Landing Page
Tema pilihan: **Tema C (Portofolio Profesional Pengembang Perangkat Lunak)**

## Live Preview

https://[zintiaadella07-github].github.io/pemweb-tugas1-[42530036]/

## Deskripsi

Landing page satu halaman yang menampilkan biografi teknis, tech stack, proyek unggulan, sertifikasi, dan tautan jejaring profesional. Dibangun dari nol tanpa framework CSS eksternal. Tema visual: "Hutan Teh" (hijau daun teh gelap dengan aksen matcha dan oranye hojicha).

## Fitur

- Struktur HTML5 semantik (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- Hierarki heading runtut (`h1` > `h2` > `h3`)
- Navigasi anchor link dengan `aria-label="Navigasi Utama"` dan tautan "lewati ke konten"
- Tata letak Flexbox (navigasi, tombol, kontak) dan CSS Grid (makro-layout, kartu proyek, tech stack)
- Desain mobile-first dengan breakpoint `min-width: 768px` dan `min-width: 1024px`
- Variabel CSS pada `:root` untuk palet warna dan font
- Animasi CSS murni (tanpa JavaScript): urutan masuk hero, cahaya latar melayang, garis bawah menu, kartu terangkat saat disorot, dan titik status berdenyut
- Animasi dimatikan otomatis untuk pengguna dengan pengaturan `prefers-reduced-motion`
- Tanpa horizontal overflow pada lebar 320px sampai 1920px

## Teknologi

HTML5, CSS3 (Flexbox, Grid, Custom Properties, Media Queries, Keyframes), Git, GitHub Pages

## Struktur Direktori

```
pemweb-tugas1-[NIM]/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

## Cara Menjalankan

Buka `index.html` langsung di peramban, atau gunakan ekstensi Live Server di VS Code.

## Pengembang

Nama Lengkap: [Zintia Adella]
NIM: [42530036]