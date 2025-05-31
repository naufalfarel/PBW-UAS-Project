Nama : Naufal Farrel Syafilan
Npm : 2308107010058

---

# GudApp – Sistem Informasi Manajemen Pergudangan

GudApp adalah aplikasi web berbasis Laravel yang dirancang untuk membantu manajemen gudang secara efisien dan terstruktur. Aplikasi ini mencakup fitur pengelolaan produk, kategori, pemasok, pelanggan, pengguna sistem, serta pencatatan produk masuk dan keluar. GudApp cocok digunakan oleh instansi atau perusahaan yang ingin mendigitalisasi alur distribusi barang di gudang.

## Fitur Utama

- Dashboard statistik: jumlah user, kategori, produk, pelanggan, pemasok, pembelian, dan barang keluar.
- Manajemen data master:

  - **Kategori Produk**
  - **Produk**
  - **Pelanggan (Customer)**
  - **Pemasok (Supplier)**

- Transaksi:

  - **Produk Masuk (Inbound Products)**
  - **Produk Keluar (Outbound Products)**

- Manajemen **pengguna sistem (admin/operator)**
- Autentikasi login
- UI modern berbasis template AdminLTE
- Pencarian dan filter data
- Proteksi CSRF dan validasi form

---

## 🗂️ Struktur Proyek

Struktur folder mengikuti standar Laravel, beberapa direktori penting:

```
├── app/                  # Logika aplikasi (Models, Controllers)
├── resources/views/      # Blade Templates (UI)
├── routes/web.php        # Route aplikasi web
├── public/               # Aset publik (CSS, JS, gambar)
├── database/migrations/  # Struktur tabel database
```

---

## 🧾 Alur Kerja Aplikasi

1. Admin melakukan login ke sistem.
2. Admin dapat mengakses dashboard utama dan melihat statistik.
3. Admin mengelola data master: kategori, produk, customer, supplier.
4. Admin mencatat transaksi barang masuk dan barang keluar.
5. Seluruh data terekam dan tersimpan di database dengan validasi.

---

## 🖼️ Tampilan Antarmuka

### Halaman Dashboard

![Dashboard](https://github.com/naufalfarel/PBW-UAS-Project-Management-Pergudangan/public/assets/img
/Dashboard.png)

### Sidebar Navigasi

- Dashboard
- Category
- Product
- Customer
- Supplier
- Outbound Products
- Inbound Products
- System Users

---

## Autentikasi dan Keamanan

- Sistem login untuk admin/operator.
- Middleware Laravel digunakan untuk membatasi akses halaman.
- Validasi server-side dan proteksi CSRF aktif di semua form.

---

## Cara Instalasi

1. **Install dependency**

```bash
composer install
npm install
```

3. **migrate database**

```bash
php artisan migrate
```

4. **seed database**

```bash
php artisan db:seed
```

6. **Jalankan server**

```bash
php artisan serve
```

---

## Admin Login (contoh)

| Email                                     | Password |
| ----------------------------------------- | -------- |
| [admin@gmail.com](mailto:admin@gmail.com) | admin123 |

---

## Teknologi yang Digunakan

- Laravel 10
- MySQL
- AdminLTE Template
- Bootstrap
- jQuery
- Font Awesome

---
