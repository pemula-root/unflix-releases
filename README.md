# UNFLIX

**Everything Worth Watching.**

UNFLIX adalah aplikasi Android native untuk menjelajahi katalog film dan serial televisi. Aplikasi dibangun menggunakan Kotlin, Jetpack Compose, dan Material Design 3, dengan sinkronisasi data akun melalui Firebase.

Repositori ini digunakan khusus untuk distribusi berkas instalasi (APK) dan catatan rilis. Kode sumber tidak dipublikasikan.

---

## Unduh

Versi terbaru tersedia pada halaman [Releases](../../releases/latest). Unduh berkas dengan ekstensi `.apk` yang terlampir pada rilis terbaru.

| Informasi | Keterangan |
|---|---|
| Versi saat ini | 2.9.8 |
| Nama paket | `com.unflix.unltd` |
| Sistem operasi minimum | Android 7.0 (API 24) |
| Ukuran berkas | ± 4 MB |

---

## Fitur

- **Beranda dan penemuan konten.** Carousel utama, tren, film populer, serial populer, penilaian tertinggi, rekomendasi, dan rilis mendatang.
- **Jelajah dan pencarian.** Penyaringan berdasarkan genre dan urutan, pencarian film, serial, dan tokoh, serta riwayat pencarian terakhir.
- **Halaman detail.** Sinopsis, daftar pemeran, musim dan episode, judul serupa, serta rekomendasi.
- **Pustaka pribadi.** Watchlist, favorit, lanjutkan menonton, dan riwayat tontonan.
- **Sinkronisasi akun.** Masuk dengan akun Google untuk menyinkronkan data pustaka dengan versi web UNFLIX.
- **Pengingat rilis.** Notifikasi ketika film pada Watchlist telah dirilis.
- **Pembaruan otomatis.** Aplikasi memberi tahu pengguna ketika tersedia versi yang lebih baru.

---

## Cara Instalasi

1. Unduh berkas APK dari halaman [Releases](../../releases/latest).
2. Buka berkas tersebut dari pengelola berkas atau notifikasi unduhan.
3. Jika diminta, izinkan instalasi dari sumber ini pada pengaturan perangkat.
4. Selesaikan instalasi, lalu buka aplikasi.

Jika sebelumnya terpasang versi dengan tanda tangan yang berbeda, hapus instalasi lama terlebih dahulu sebelum memasang versi ini.

---

## Pembaruan

Pembaruan didistribusikan melalui halaman Releases pada repositori ini. Saat aplikasi dibuka, aplikasi memeriksa versi terbaru secara otomatis. Apabila tersedia versi yang lebih baru, aplikasi menampilkan dialog pembaruan dengan tautan unduhan.

Seluruh versi ditandatangani dengan kunci yang sama sehingga dapat dipasang langsung di atas versi sebelumnya.

---

## Izin Aplikasi

| Izin | Kegunaan |
|---|---|
| Internet dan status jaringan | Memuat katalog, gambar, dan sinkronisasi data |
| Notifikasi | Menampilkan pengingat rilis film (Android 13 ke atas, opsional) |

---

## Privasi dan Data

- Penelusuran sebagai tamu tidak memerlukan akun.
- Apabila pengguna masuk dengan akun Google, data Watchlist, favorit, dan riwayat tontonan disimpan pada layanan Cloud Firestore yang dikelola pengembang dan hanya dapat diakses oleh akun pemilik data.
- Aplikasi tidak menjual atau membagikan data pengguna kepada pihak ketiga.

---

## Atribusi dan Pernyataan

Aplikasi ini menggunakan API TMDB, tetapi tidak didukung atau disertifikasi oleh TMDB.

Data katalog, termasuk judul, sinopsis, poster, dan gambar latar, bersumber dari TMDB. Pemutaran video disediakan oleh layanan pihak ketiga. UNFLIX tidak menyimpan maupun menyediakan berkas video pada server milik sendiri, dan seluruh hak atas konten tetap berada pada pemegang hak masing-masing.

Aplikasi disediakan sebagaimana adanya, tanpa jaminan apa pun.

---

## Catatan Rilis

### 2.9.8

**Baru**
- Pengingat rilis untuk film pada Watchlist.
- Pemeriksaan pembaruan otomatis melalui GitHub Releases.
- Sinkronisasi data akun dengan versi web.

**Perbaikan**
- Pergerakan layar dan carousel pada Beranda lebih halus.
- Tab Jelajah dimuat saat dibuka sehingga aplikasi terbuka lebih cepat.
- Ukuran aplikasi lebih kecil.
- Perbaikan penutupan aplikasi saat dibuka.

---

## Kontak

Untuk pelaporan masalah atau saran, silakan hubungi pengembang melalui halaman Issues pada repositori ini.
