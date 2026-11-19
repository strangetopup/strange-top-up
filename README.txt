STRANGE TOP UP — Prototipe website

CARA MENJALANKAN
1. Ekstrak strange_top_up.zip.
2. Buka folder strange_top_up.
3. Buka index.html dengan browser modern (Chrome/Firefox).
4. Pilih game, isi User ID/Server bila diperlukan, pilih nominal dan metode, lalu Buat Pesanan.
5. Cek pesanan dengan kode STU-... yang ditampilkan.
6. Admin demo: PIN 1234. Pesanan dapat ditandai selesai.

BATASAN PENTING
- Ini prototipe front-end yang berfungsi secara lokal di browser.
- Harga di dalamnya hanya contoh dan wajib diverifikasi/diganti.
- Pembayaran QRIS/DANA/OVO belum menerima uang sungguhan.
- Pesanan hanya tersimpan di localStorage browser/perangkat yang digunakan; admin dan pelanggan tidak berbagi database.
- Tidak ada pengiriman diamond/UC otomatis.
- Jangan gunakan PIN demo untuk produksi.

AGAR SIAP PRODUKSI
Perlu backend/database, autentikasi admin aman, integrasi payment gateway resmi (mis. penyedia QRIS/e-wallet), webhook verifikasi pembayaran, dan API supplier top-up. Simpan API key hanya di server, jangan di HTML/JavaScript browser.
