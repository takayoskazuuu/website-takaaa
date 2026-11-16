# Zakafi — Website Donasi QRIS & Media Sosial Resmi (oleh Takaaa)

Website modern responsif dengan dua mode tema (**Swiss Light** & **Aurora Dark**), bar navigasi **Liquid Glass** semi-transparan yang bisa digeser-geser, pemotong QRIS otomatis (*Smart QR-Only Cropper*), serta QR Code WhatsApp Admin (`0881026467671`) yang dapat langsung dipindai.

---

## 1. Struktur Folder di Laptop

Ekstrak file `zakafi-website.zip` ke dalam satu folder di laptop kamu (misalnya di `Documents/zakafi-website/`). Susunan filenya seperti ini:

```text
zakafi-website/
├── index.html          # Kode lengkap website Zakafi (HTML + CSS + JavaScript)
├── README.md           # Panduan pemasangan & publikasi GitHub
├── .nojekyll           # Agar GitHub Pages memuat website statis dengan cepat
└── assets/             # Folder untuk menyimpan gambar QRIS & Logo milikmu
    ├── qris.png        # (Taruh gambar QRIS yang sudah dipotong di sini)
    └── logo.png        # (Taruh foto profil / logo Takaaa di sini)
```

---

## 2. Cara Memasang Gambar QRIS & Logo agar Muncul untuk Semua Pengunjung

1. Buka file **`index.html`** di browser laptop kamu (klik dua kali file `index.html`).
2. **Untuk QRIS (Potong Otomatis Sisakan QR Saja):**
   - Klik tombol **"Unggah & Potong QRIS Otomatis (Sisakan QR Saja)"** di bawah kotak QRIS.
   - Pilih gambar poster **GoPay Merchant (`TAKAAA STORE, TOKO HOBI & MAINAN`)** dari laptop kamu.
   - Website otomatis memotong bagian atas, nama merchant, segitiga merah, dan footer sehingga hanya menyisakan kotak QR bersih.
   - Klik **"Atur QRIS & Logo"** → klik **"Simpan Potongan sebagai assets/qris.png"**, lalu pindahkan file `qris.png` yang terunduh ke dalam folder **`assets/`**.
3. **Untuk Logo / Foto Profil:**
   - Salin foto profil kamu ke dalam folder **`assets/`** dan beri nama **`logo.png`** (atau **`logo.jpg`**).
   - Website sudah diprogram otomatis mendeteksi `./assets/qris.png` dan `./assets/logo.png` begitu diunggah ke GitHub!

---

## 3. Cara Publikasi ke GitHub Pages (Gratis & Online 24 Jam)

### Langkah A: Buat Repositori Baru di GitHub
1. Buka **[github.com](https://github.com)** lalu login (atau daftar akun gratis jika belum punya).
2. Klik ikon **`+`** di pojok kanan atas → pilih **New repository**.
3. Isi **Repository name**, misalnya: `zakafi`
4. Pastikan visibilitas dipilih **Public**.
5. Klik tombol hijau **Create repository**.

### Langkah B: Unggah Semua File dari Laptop ke GitHub
1. Di halaman repositori baru kamu, klik link **uploading an existing file**.
2. Buka folder `zakafi-website` di laptop kamu, pilih **semua isi di dalamnya** (`index.html`, `README.md`, `.nojekyll`, dan folder `assets` yang sudah berisi `qris.png` & `logo.png`), lalu seret (*drag & drop*) ke halaman GitHub.
3. Tunggu proses unggah selesai, lalu klik tombol hijau **Commit changes**.

### Langkah C: Aktifkan GitHub Pages
1. Masuk ke tab **Settings** (ikon roda gigi) di bagian atas repositori `zakafi`.
2. Pada menu sebelah kiri, klik **Pages**.
3. Di bagian **Build and deployment → Source**, pilih **Deploy from a branch**.
4. Di bagian **Branch**, pilih **`main`** dan folder **`/ (root)`**, lalu klik **Save**.
5. Tunggu sekitar 1–2 menit lalu refresh halaman tersebut. Link website kamu akan muncul di bagian atas:
   ```text
   https://username-kamu.github.io/zakafi/
   ```

---

Dibuat dengan **Zakafi** oleh **Takaaa**.
