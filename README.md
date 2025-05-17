

---

# 🌟 Membuat Fitur Favorite & Tema – Pengembangan Aplikasi Android

**Membuat Fitur Favorite menggunakan Database & Pengaturan Tema** adalah pengembangan lanjutan dari aplikasi submission awal. Proyek ini menambahkan dua fitur penting, yaitu **Favorite** dan **Theme Settings**, tanpa menghilangkan atau mengubah fitur utama dari versi sebelumnya.

> 📘 **Catatan:** Proyek ini merupakan *proyek Submissions Dicoding* . Tujuan dari proyek ini adalah untuk mengembangkan keterampilan dalam menggunakan komponen Android seperti database lokal, `SharedPreferences`, dan pengelolaan tema, sambil mempertahankan fungsionalitas dan struktur aplikasi asli.

---

## 📱 Fitur Utama Aplikasi

* ✅ **Fitur Favorite**
  Pengguna dapat menandai data (misalnya: item, artikel, atau pengguna) sebagai favorit. Data favorit ini disimpan secara **lokal menggunakan Room Database** dan dapat diakses kembali melalui menu khusus.

* ✅ **Fitur Pengaturan Tema (Dark/Light Mode)**
  Aplikasi mendukung penggantian tema secara manual melalui menu pengaturan menggunakan **DataStore / SharedPreferences**. Tema yang dipilih akan dipertahankan meskipun aplikasi ditutup.

* ✅ **Seluruh Fitur Submission Awal Tetap Dipertahankan**, antara lain:

  * Halaman utama dengan daftar data
  * Halaman detail item
  * Navigasi antar halaman menggunakan Jetpack Navigation / Intent
  * Penggunaan ViewModel dan LiveData
  * Konsumsi API (jika tersedia)
  * Tampilan UI responsif dan mengikuti prinsip Material Design

---

## 🧩 Teknologi dan Library yang Digunakan

| Komponen           | Teknologi/Library             |
| ------------------ | ----------------------------- |
| Bahasa Pemrograman | Kotlin                        |
| IDE                | Android Studio                |
| Arsitektur         | MVVM                          |
| Database           | Room (SQLite)                 |
| Penyimpanan Tema   | DataStore / SharedPreferences |
| UI & Navigasi      | XML, Material Components      |
| State Management   | ViewModel, LiveData           |

---

## 🎨 Tampilan Antarmuka

| Beranda                                          | Detail                                               | Favorite                                                 | Pengaturan Tema                                    |
| ------------------------------------------------ | ---------------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------- |
| ![home](https://github.com/user/assets/home.png) | ![detail](https://github.com/user/assets/detail.png) | ![favorite](https://github.com/user/assets/favorite.png) | ![theme](https://github.com/user/assets/theme.png) |

*Catatan: Gambar-gambar di atas adalah contoh. Anda dapat menyesuaikannya dengan tangkapan layar aplikasi Anda.*

---

## ⚙️ Cara Menjalankan Aplikasi

1. Clone repositori ini.
2. Buka dengan Android Studio.
3. Jalankan menggunakan emulator atau perangkat fisik.
4. Pastikan konfigurasi minimum SDK sesuai dengan build.gradle (biasanya API 21+).

---

## 🚀 Rencana Pengembangan Lanjutan

* [ ] Menambahkan fitur pencarian item favorit
* [ ] Integrasi login untuk menyimpan data user
* [ ] Backup data favorit ke cloud
* [ ] Implementasi dark mode otomatis berdasarkan waktu

---

## 📧 Kontak Pengembang

* 👤 Nama: **Muhammad Rafli Nurfathan**
* 📧 Email: [nurfathanrafli85@gmail.com](mailto:nurfathanrafli85@gmail.com)
* 🔗 LinkedIn: [linkedin.com/in/mhmmdraflin](https://www.linkedin.com/in/mhmmdraflin)

---


