# 🎹 Aplikasi Rental Keyboard - UKK 2026

Dibuat oleh: Selvi Ayu
Project: Aplikasi Manajemen Inventaris Keyboard menggunakan Flutter dan Supabase.

## 🗄️ Dokumentasi Supabase

### Struktur Tabel `alat`
Tabel ini menyimpan data utama aset keyboard:
- **kode_aset**: Kode unik barang.
- **merk**: Nama brand keyboard.
- **spesifikasi**: Fitur dan detail barang.
- **status**: Ketersediaan (Tersedia/Dipinjam).
- **image_url**: Link gambar produk.

### Konfigurasi Keamanan (RLS)
- **Status**: Disabled (Non-aktif).
- **Tujuan**: Memudahkan proses penilaian UKK agar penguji dapat mengakses data tanpa kendala autentikasi.

### Integrasi Flutter
Aplikasi terhubung menggunakan `Supabase.instance.client` dengan URL dan Anon Key yang telah dikonfigurasi pada file `main.dart`.
