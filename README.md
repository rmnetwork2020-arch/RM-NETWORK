# 🚀 RM-NETWORK ULTIMATE AUTO-SYSTEM

Sistem otomasi berbasis Web (HTML) untuk mengelola layanan **VPN Remote** dan **PPPoE Internet** menggunakan MikroTik. Didesain khusus untuk mempermudah teknisi jaringan dalam manajemen pelanggan, penagihan, dan isolasi otomatis.

## ✨ Fitur Unggulan
* **Otomatisasi Port**: Penentuan port Winbox & Mikhmon otomatis berdasarkan nomor urut pelanggan.
* **Script Generator**: Menghasilkan script Server, Client, dan Scheduler (Expired) sekali klik.
* **Notifikasi Telegram**: Notifikasi otomatis ke bot Telegram saat pelanggan jatuh tempo.
* **Pencatatan Keuangan**: Dilengkapi rekap total omset bulanan dan harga layanan.
* **Manajemen Sisa Waktu**: Menampilkan sisa hari masa aktif pelanggan secara real-time.
* **Integrasi WhatsApp & Kalender**: Kirim detail login ke pelanggan via WA dan pasang pengingat di Google Calendar Admin.

## 🛠️ Cara Penggunaan
1.  **Persiapan Server**: Jalankan perintah dasar VPN & IP Pool di MikroTik Server Anda.
2.  **Konfigurasi Web**: Masukkan IP Server, Token Bot Telegram, dan Chat ID Anda pada kolom yang tersedia.
3.  **Generate Pelanggan**: Masukkan data pelanggan, klik **Simpan & Generate**.
4.  **Eksekusi Script**:
    * Copy **Script Server** ke MikroTik Server.
    * Copy **Script Scheduler** ke MikroTik Server.
    * Kirim **Script Client** ke pelanggan.

## 🔒 Keamanan & Privasi
Sistem ini menggunakan **LocalStorage**. Semua data (Token, IP, Database Pelanggan) hanya tersimpan di memori browser perangkat Anda sendiri. Tidak ada data yang dikirim ke server luar manapun.

---
*Dibuat dengan 🫂 untuk komunitas teknisi jaringan Indonesia oleh **Raninto - RM Network**.*
