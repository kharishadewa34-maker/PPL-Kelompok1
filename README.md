# Sistem Informasi Manajemen Kos

Proyek awal aplikasi web kelompok menggunakan Laravel, MySQL, Blade, dan Bootstrap. Fitur aplikasi, termasuk login, belum dibuat.

## Persiapan

- PHP 8.3 atau lebih baru dengan ekstensi `pdo_mysql`, Composer, Node.js dan MySQL.
- Buat database kosong bernama `sim_kos` di MySQL.
- Jalankan perintah di folder proyek:

```bash
composer install
npm install
```

Salin `.env.example` menjadi `.env`. Sesuaikan pengaturan `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME` dan `DB_PASSWORD` dengan MySQL di komputer masing-masing, lalu jalankan:

```bash
php artisan key:generate
php artisan migrate
npm run build
php artisan serve
```

Buka alamat yang ditampilkan oleh `php artisan serve`. Saat mengubah tampilan, jalankan `npm run dev` pada terminal kedua agar aset diperbarui otomatis.

Jangan unggah `.env`, kata sandi, database pribadi, `vendor`, atau `node_modules` ke GitHub. Gunakan branch untuk setiap tugas dan pull request untuk menggabungkan pekerjaan.
