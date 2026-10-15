# DevSpace - Jasa Pembuatan Website Profesional

DevSpace adalah landing page untuk sebuah creative tech agency yang melayani jasa pembuatan website. Tampilan antarmuka ini dirancang untuk menunjukkan kesan profesional, premium, dan modern, cocok untuk menarik minat klien mulai dari UMKM hingga perusahaan tingkat enterprise.

## Fitur Utama

- **Desain Modern & Clean:** Menggunakan tema gelap (dark mode) dengan elemen glassmorphism (efek kaca) dan pendaran cahaya (glow effects).
- **Responsive Penuh:** Tampilan menyesuaikan secara otomatis untuk perangkat mobile, tablet, maupun desktop.
- **Efek Scroll Reveal:** Animasi konten masuk saat pengunjung melakukan scroll untuk memberikan kesan interaktif.
- **Navigasi Dinamis:** Navigasi dengan efek blur saat di-scroll dan menu mobile interaktif (hamburger menu).
- **Warna & Typography Kustom:** Menggunakan font dari Google Fonts (Inter & Poppins) dan palet warna gradients untuk menonjolkan bagian-bagian penting.

## Struktur Direktori

Kode telah dirapikan agar lebih mudah dikelola:

```text
web-bisnis/
│
├── index.html           # Struktur utama HTML aplikasi.
│
├── css/
│   └── style.css        # Berisi custom CSS untuk styling (glassmorphism, animations, scrollbar, dsb).
│
├── js/
│   ├── script.js        # Logika JavaScript untuk navigasi, menu mobile, dan animasi on-scroll.
│   └── tailwind-config.js # Konfigurasi custom untuk Tailwind CSS (warna, font, dan keyframes animasi).
│
└── README.md            # Dokumentasi project.
```

## Teknologi yang Digunakan

1. **HTML5:** Struktur semantik dasar website.
2. **Tailwind CSS (via CDN):** Framework utility-first untuk desain responsif dengan cepat.
3. **Vanilla JavaScript:** Mengatur logika sederhana seperti navbar scroll efek, dropdown menu mobile, dan *IntersectionObserver* untuk animasi saat diatur turun.
4. **Lucide Icons (via CDN):** Digunakan untuk ikon-ikon yang bersih dan konsisten pada website.
5. **Google Fonts:** Menggunakan *Inter* untuk teks body dan *Poppins* untuk heading guna meningkatkan keterbacaan dan estetika.

## Cara Menggunakan

1. Kamu bisa membuka file `index.html` ini secara langsung pada web browser apapun dengan klik ganda.
2. Untuk proses development agar lebih maksimal dan melihat perubahan secara *real-time*, kamu disarankan menggunakan fitur ekstensi seperti **Live Server** di VS Code.

## Modifikasi / Kustomisasi

- **Konfigurasi Tema Tailwind:** Buka lokasi `js/tailwind-config.js` untuk mengganti setting warna utama (primary colors), font kustom, atau jenis-jenis custom animation seperti efek floating.
- **Pengaturan Custom CSS:** Untuk mengatur dan menyesuaikan background scrollbar, custom gradient text, atau glassmorphism, silahkan ubah pada file `css/style.css`.
- **Konten HTML:** Edit `index.html` jika ingin mengubah isi layanan, daftar portofolio, logo, atau teks copywriting hero.
- **Link WhatsApp:** Ubah *href* menuju kontak di tag CTA WhatsApp sesuai nomor tujuan yang aktif, contohnya: `https://wa.me/628XXXXXXXXXX`.

---
*Dibuat untuk kebutuhan operasional Jasa Pembuatan Website DevSpace.*
