# 5K Sub-20 Tracker

Aplikasi web progres latihan 5K sub-20, responsif untuk iPhone.

## Fitur
- Dashboard: PB, total jarak, jumlah sesi, rata-rata pace, target mingguan.
- Program 12 minggu mulai 2 November 2026.
- Catat lari: tanggal, jenis, jarak, durasi, HR, RPE, catatan.
- Catat hasil tes 5K dan grafik progres.
- Riwayat, ekspor CSV, backup/impor JSON.
- PWA/offline setelah pertama kali dibuka melalui HTTPS.

## Deploy agar bisa diakses di iPhone
1. Ekstrak ZIP.
2. Upload seluruh isi folder ke layanan hosting statis HTTPS seperti GitHub Pages atau Netlify.
3. Buka URL HTTPS hasil deploy di Safari pada iPhone.
4. Tekan Share > Add to Home Screen > Add.

## Catatan
- Data disimpan lokal di browser/perangkat (localStorage), bukan tersinkron otomatis antarperangkat.
- Ekspor backup JSON/CSV secara berkala.
- PB awal 22:00 dan target mingguan 40 km merupakan nilai awal yang dapat disesuaikan.
- Jadwal latihan adalah kerangka awal, perlu disesuaikan dengan volume aktual, kebugaran, dan pemulihan.
