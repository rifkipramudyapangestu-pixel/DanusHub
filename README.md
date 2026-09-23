# DanusHub
DanusHub adalah platform digital terpusat untuk pemasaran Dana Usaha (Danus) kemahasiswaan. Repositori ini berisi kode untuk Web Dashboard guna memudahkan penjual (Ormawa/UKM) mengelola e-katalog dan merekap pesanan secara otomatis.

## Fitur Utama Web Dashboard Penjual

Berikut adalah rincian kebutuhan fungsional (fitur) untuk antarmuka penjual (panitia Danus) yang telah disesuaikan dengan batasan ruang lingkup (*In Scope*) proyek.

| Modul / Kategori | Nama Fitur | Deskripsi & Cara Kerja |
| :--- | :--- | :--- |
| **1. Manajemen Akun** | Pendaftaran & Login penjual | Formulir akses masuk khusus untuk panitia Danus dari Organisasi Mahasiswa/UKM. |
| | Profil penjual | Pengelolaan identitas panitia, nama Ormawa/UKM, serta nomor kontak WhatsApp penanggung jawab. |
| **2. E-Katalog Produk (CRUD)** | Tambah Produk | Formulir untuk mengunggah poster/foto, nama produk, harga, deskripsi, dan kategori. |
| | Edit & Hapus Produk | Fitur untuk memperbarui informasi produk atau menghapus menu yang sudah tidak dijual. |
| | Status Penjualan (Ready/PO) | Opsi menetapkan produk sebagai Ready Stock atau Pre-Order (PO), lengkap dengan jadwal Close PO dan Ready Date. |
| | Manajemen Lokasi Gedung COD | Penjual dapat mendaftarkan titik kumpul pengambilan barang (contoh: Gedung A, Gedung Kuliah Terpadu). |
| **3. Manajemen Stok (E-Inventory)** | Input Kuota Produk | Kolom untuk menentukan batas jumlah porsi atau ketersediaan barang jualan. |
| | Update Stok Otomatis | Kuota produk akan berkurang secara *real-time* ketika pembeli menyelesaikan pemesanan, mencegah pesanan berlebih. |
| **4. Rekapitulasi Pesanan** | Tabel Pesanan Masuk (*Real-Time*) | Sub-menu operasional yang menampilkan pesanan masuk secara langsung tanpa perlu *refresh* halaman (berisi nama, kontak, rincian pesanan). |
| | Filter Lokasi Gedung | Fitur untuk menyaring daftar pesanan berdasarkan titik gedung kampus guna memudahkan panitia membagi tugas distribusi. |
| | Ubah Status Pesanan | Penjual dapat mengubah tahapan transaksi secara interaktif (misal: Menunggu Konfirmasi -> Sedang Diproses -> Selesai). |
| | Rekap Kebutuhan Porsi | Sistem menjumlahkan total keseluruhan item yang harus disiapkan panitia pada hari H pembagian/pengantaran. |
| **5. Laporan Penjualan** | Filter Harian & Bulanan | Sub-menu laporan yang memungkinkan penjual melihat metrik penjualan berdasarkan rentang waktu harian (tanggal spesifik) atau bulanan. |
| | Ringkasan Omzet | Dasbor metrik yang menghitung akumulasi total pendapatan masuk dari transaksi yang telah selesai. |
| | Ekspor Data Laporan | Tombol unduh laporan riwayat transaksi dan total omzet (format Excel/CSV/PDF) untuk keperluan Laporan Pertanggungjawaban (LPJ) organisasi. |
| **6. Transaksi & Pembayaran**| Validasi Lunas Manual / COD | Sistem untuk mengonfirmasi penerimaan pembayaran tunai di tempat (COD) atau memverifikasi bukti transfer secara manual. |
