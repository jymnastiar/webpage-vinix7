# Tri-Ace Booking - Login Page

Halaman login responsif untuk aplikasi booking Tri-Ace yang dibangun dengan HTML, CSS (Tailwind).

## 📋 Daftar Isi

- [Fitur](#fitur)
- [Teknologi](#teknologi)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Struktur Project](#struktur-project)
- [Responsive Design](#responsive-design)
- [Lisensi](#lisensi)

## 🛠️ Teknologi

Proyek ini menggunakan:

- **HTML5** - Struktur semantic
- **Tailwind CSS** - Utility-first CSS framework

## 📦 Instalasi

### Prerequisites

- Node.js dan npm (untuk build Tailwind CSS)

### Langkah-Langkah

1. **Clone atau download project**

   ```bash
   cd vinix_webpage_modul6
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Build Tailwind CSS**

   ```bash
   npm run build
   ```

4. **Buka di browser**
   - Buka file `src/index.html` langsung di browser, atau
   - Gunakan live server extension di VS Code

## 🚀 Penggunaan

### Development

Untuk development dengan watch mode:

```bash
npm run watch
```

### Build

Untuk production build:

```bash
npm run build
```

## 📁 Struktur Project

```
vinix_webpage_modul6/
├── package.json          # Dependencies dan scripts
├── tailwind.config.js    # Konfigurasi Tailwind CSS
├── README.md             # File dokumentasi ini
└── src/
    ├── index.html        # Halaman utama login
    ├── input.css         # CSS custom dan Tailwind imports
    ├── output.css        # Output CSS yang sudah di-build
    └── img/
        ├── logo.svg      # Logo Tri-Ace
        ├── background-img.png  # Background image
        ├── icon-google.svg     # Google login icon
        └── icon-apple.svg      # Apple login icon
```

## 📱 Responsive Design

Halaman ini menggunakan Tailwind CSS responsive breakpoints:

- **Mobile** - Layout single column dengan image di atas
- **Tablet** - Transisi ke layout yang lebih lebar
- **Desktop** - Layout dual column dengan image di sebelah kiri dan form di kanan

```html
<!-- Responsive container -->
<div class="max-w-360 flex flex-col md:flex-row">
  <!-- Mobile: flex-col, Desktop: flex-row -->
</div>
```

## 🎨 Warna & Styling

Project menggunakan custom color palette di Tailwind config:

- `color-button-primary` - Warna tombol utama
- `color-button-secondary` - Warna input fields
- `color-text-title` - Warna judul
- `color-text-body` - Warna teks biasa

## 🐛 Support

Jika menemukan issue atau punya saran, silakan buat issue atau contact developer.

## 📄 Lisensi

Project ini dibuat untuk keperluan Tugas Modul 6 Vinix.

---

**Made with ❤️ by Kelompok 15**
