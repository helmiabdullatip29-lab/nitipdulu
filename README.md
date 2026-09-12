# 📦 NITIPDULU v2.1 - Sistem Distribusi Konsinyasi Kerupuk

Aplikasi web modern berbasis **Offline-First SPA** yang dirancang khusus untuk operasional kemitraan titip-jual (konsinyasi) kerupuk.  
Bebas hambatan **Google Apps Script** (*buka instan < 0.3 detik, tidak ada loading macet, dan 100% gratis selamanya*).

---

## 🌟 Apa yang Baru di Versi 2.1?

### 1. 🔒 Keamanan Ketat & Pemisahan Akses (Aman Dibuka Warung)
* **Tampilan Publik Khusus Warung:**
  - Pemilik warung mitra saat membuka link HANYA melihat katalog belanja, slider promo kerupuk, keranjang belanja, dan tombol CS WhatsApp.
  - Tombol internal "Kurir" dan "Bos" **ditiadakan dari menu atas**, sehingga warung tidak tahu ada dashboard rahasia.
* **Akses Staf Tersembunyi:**
  - Terletak di footer bawah: `🔐 Akses Khusus Tim / Staf Lapangan`.
  - Membuka pop-up otentikasi login PIN untuk Kurir dan Master PIN untuk Owner (Bos).
  - Tidak ada petunjuk PIN di layar demi keamanan.
  - Tombol **"Keluar (Logout)"** di bar atas untuk mengunci kembali dashboard saat selesai bertugas.

---

### 2. 🖼️ Slider / Carousel Banner Foto Warung
* Banner geser otomatis di Portal Warung yang menampilkan foto asli:
  - **Slide 1:** Logo Resmi NitipDulu kemitraan konsinyasi (Garansi retur jika melempem).
  - **Slide 2:** Kerupuk Mie Kuning Asli Gurih (Best seller warung makan).
  - **Slide 3:** Kurir Siap Antar Rutin (Foto muatan motor kurir di jalan).
  - **Slide 4:** Varian Pedas Nampol (Jengkol Pedas & Mawar Pedas).

---

### 3. 📍 Kurir Tambah Warung Baru + Auto GPS Google Maps
* Kurir di lapangan yang mendapatkan warung mitra baru bisa langsung mendaftarkannya dari HP:
  - Buka menu: **"➕ Daftarkan Warung Baru"**.
  - Isi nama warung, pemilik, nomor WhatsApp, dan alamat.
  - Tekan tombol **"📍 Kunci GPS Sekarang"**:
    - Mengambil titik koordinat GPS perangkat saat kurir berdiri di depan toko.
    - Otomatis membuat link rute Google Maps (`https://maps.google.com/?q=lat,lng`).
  - Begitu disimpan, warung langsung masuk ke rute kurir dan form kunjungan pertama langsung terbuka!

---

### 4. 📦 Master Produk, Foto & Varian Rasa (Kontrol Penuh Bos)
* Di Dashboard Bos -> Tab **"Master Produk & Stok"**:
  - **➕ Tambah Produk Baru:** Masukkan nama kerupuk, pilih varian rasa, harga konsumen, modal HPP, stok gudang, dan **upload foto produk sendiri (dari galeri HP/kamera)**.
  - **✏️ Edit Produk:** Ubah harga, nama, jumlah stok, dan ganti foto produk kapan saja.
  - **🏷️ Kelola Varian Rasa:** Bos bisa menambah varian rasa baru (misal: *Balado*, *Daun Jeruk*, dll.) yang otomatis masuk ke form produk dan filter belanja warung.
  - **🖼️ Ganti Logo Usaha:** Di tab Pengaturan Bos, bisa upload logo baru untuk mengganti logo default.

---

### 5. ⚠️ Peringatan Kuota Pemesanan (> 10 Bungkus)
* Jika warung memesan lebih dari 10 bungkus, sistem memunculkan peringatan:
  > *"Peringatan Kuota Restok (> 10 Bungkus): Pastikan rak display di warung Anda mencukupi dan tidak ditumpuk terlalu padat agar kerupuk tetap renyah dan kemasan tidak remuk."*

---

### 6. 💬 Floating Customer Service WhatsApp
* Tombol hijau melayang di pojok kanan bawah dengan ikon WhatsApp berdenyut (*pulse*) bertuliskan **"Chat CS Admin"** untuk respon cepat jika warung butuh bantuan.

---

## 🚀 Cara Menjalankan & Membuka Aplikasi

### Buka di Komputer / Laptop Anda (Instan):
1. Buka folder: `C:\Users\HYPE\.gemini\antigravity\scratch\nitipdulu\`
2. Klik ganda file `index.html`.
3. File akan langsung terbuka di browser (Chrome / Edge) secara instan tanpa loading!

### Upload Gratis Agar Bisa Dibuka di HP (10 Detik):
* Seret / drag & drop folder `nitipdulu` ke [Vercel](https://vercel.com) atau [Netlify Drop](https://app.netlify.com/drop).
* Anda langsung mendapatkan link resmi (misal: `nitipdulu.vercel.app`) yang bisa dibagikan ke seluruh warung dan kurir!
