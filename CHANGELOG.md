# Changelog
All notable changes to this project will be documented in this file.

Format mengikuti:
- Added (fitur baru)
- Improved (peningkatan)
- Fixed (bug fix)
- Security (keamanan)

---

## [v1.0.0] – Initial Stable Release
📅 2026-01-17

### Added
- Progressive Web App (PWA), bisa di-install di HP
- Pencatatan uang masuk & keluar harian
- Auto kategori berdasarkan catatan (bisa diedit manual)
- Tab Input, Riwayat, dan Insight
- Insight keuangan keluarga (ringkasan harian/bulanan)
- Export data ke CSV
- Sinkronisasi data realtime untuk 2 perangkat

### Improved
- UI mobile-first dengan warm tone
- Navigasi bottom tab untuk akses cepat
- Urutan input disesuaikan dengan kebiasaan penggunaan harian
- Performa lebih ringan dibanding Google Sheet

### Fixed
- Data tidak tersimpan di tab Riwayat
- Sorting transaksi berdasarkan tanggal
- Edit & delete transaksi tidak sinkron
- Bug kategori `undefined`
- Issue instalasi PWA

### Security
- Data hanya tersimpan di storage milik user
- Tidak ada tracking, analytics, atau third-party script
- Aman untuk penggunaan pribadi & keluarga
