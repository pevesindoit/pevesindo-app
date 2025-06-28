# 📄 Aplikasi CV & Manajemen Pengantaran – Berbasis Next.js & Supabase

Aplikasi ini dibuat untuk mempermudah proses pengantaran barang antar cabang dan mempermudah monitoring stok serta mutasi oleh berbagai bagian seperti driver, kepala gudang, sales, dan HRD. Aplikasi menggunakan **Next.js**, **Tailwind CSS**, **Supabase**, serta integrasi dengan **API Accurate Online**.

---

## 📋 Daftar Isi

- [Fitur Utama](#fitur-utama)
- [Teknologi yang Digunakan](#teknologi-yang-digunakan)
- [Instalasi](#instalasi)
- [Struktur Role & Fungsinya](#struktur-role--fungsinya)
- [Daftar API](#daftar-api)
- [Screenshots](#screenshots)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

---

## ✅ Fitur Utama

### 🚚 Driver

- Klik tombol mulai loading → selesai loading → mulai pengantaran → selesai pengantaran
- Mengisi status produk (sesuai / tidak sesuai)

### 🏭 Kepala Gudang

- Mengatur urutan pengantaran (drag & drop)
- Melihat lokasi driver dan tracking pengantaran
- Menyelesaikan pengantaran jika statusnya "ambil sendiri"
- Melihat mutasi barang dan assign driver untuk pengantarannya

### 🧾 Sales

- Input link Google Maps untuk lokasi pengantaran
- Melihat stok di seluruh cabang

### 👥 HRD

- Melihat riwayat keluar-masuk barang untuk setiap motif
- Filter berdasarkan tanggal dan rentang waktu

---

## 🛠 Teknologi yang Digunakan

- **Next.js** – Framework React untuk SSR dan routing
- **Tailwind CSS** – Styling modern berbasis utility
- **Supabase** – Autentikasi dan database berbasis PostgreSQL
- **Axios** – Library HTTP Client untuk request API
- **Accurate Online API** – Sinkronisasi data inventori

---

📡 Daftar API
GET
/api/get-driver – Mendapatkan daftar driver aktif

POST
/api/get-stock – Mendapatkan stok dari Accurate

/api/search-stock – Cari stok berdasarkan kata kunci

/api/stock-detail – Detail stok per barang

/api/sync-database – Sinkronisasi database Accurate dengan Supabase

/api/sync-mutasi – Sinkronisasi data mutasi pengantaran

🖼 Screenshots

## 🧾 Login

![Login](https://res.cloudinary.com/unm/image/upload/v1750996187/aplikasi%20pengantaran/1_tawegk.png)

---

## 🏷️ Halaman Kepala Gudang

![Kepala Gudang 1](https://res.cloudinary.com/unm/image/upload/v1750996188/aplikasi%20pengantaran/3_o5ifci.png)
![Kepala Gudang 2](https://res.cloudinary.com/unm/image/upload/v1750996188/aplikasi%20pengantaran/2_wlop1d.png)
![Kepala Gudang 3](https://res.cloudinary.com/unm/image/upload/v1750996188/aplikasi%20pengantaran/4_seiu9b.png)
![Kepala Gudang 4](https://res.cloudinary.com/unm/image/upload/v1750996189/aplikasi%20pengantaran/5_odtndp.png)

---

## 💼 Halaman Sales

![Sales 1](https://res.cloudinary.com/unm/image/upload/v1750996188/aplikasi%20pengantaran/6_ywzwbk.png)
![Sales 2](https://res.cloudinary.com/unm/image/upload/v1750996187/aplikasi%20pengantaran/7_w9i1lc.png)
![Sales 3](https://res.cloudinary.com/unm/image/upload/v1750996187/aplikasi%20pengantaran/8_zzltga.png)

---

## 🧑‍💼 Halaman HRD

![HRD](https://res.cloudinary.com/unm/image/upload/v1750996188/aplikasi%20pengantaran/9_rzvgqc.png)

---

## 🚚 Halaman Pengantaran

![Pengantaran 1](https://res.cloudinary.com/unm/image/upload/v1750996187/aplikasi%20pengantaran/10_pjgvrf.png)
![Pengantaran 2](https://res.cloudinary.com/unm/image/upload/v1750996187/aplikasi%20pengantaran/11_yhge7h.png)

## 💻 Instalasi

```bash
# 1. Clone repo ini
git clone https://github.com/guntekhunter/cv-app.git

# 2. Masuk ke folder proyek
cd cv-app

# 3. Install dependencies
npm install

# 4. Jalankan project secara lokal
npm run dev

```

## 💻 Instalasi

👥 Struktur Role & Fungsinya
Role Fitur
Driver Mulai/sudah loading, mulai/sudah antar, input status produk
Kepala Gudang Atur pengantaran, mutasi, tracking lokasi driver, ubah status ambil sendiri
Sales Tambah link Google Maps, lihat stok semua cabang
HRD Lihat riwayat stok keluar-masuk berdasarkan tanggal dan cabang

```

```
# pevesindo-app
