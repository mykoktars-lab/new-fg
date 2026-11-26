# Finish Good Analysis — Paket Repository Baru

Paket ini berisi aplikasi web/PWA Finish Good Analysis yang siap diunggah ke repository GitHub baru.

## Isi
- `index.html` — aplikasi utama
- `manifest.webmanifest` — konfigurasi instalasi PWA
- `service-worker.js` — cache/offline shell dengan nama cache baru
- `assets/` — ikon aplikasi

## Upload ke repository baru
1. Buat repository GitHub baru.
2. Ekstrak ZIP ini.
3. Buka folder hasil ekstrak.
4. Unggah **semua isi folder** (bukan folder pembungkusnya) ke halaman utama repository.
5. Commit perubahan.
6. Buka **Settings → Pages**.
7. Pada Build and deployment, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
8. Tunggu deployment selesai dan buka URL GitHub Pages yang ditampilkan GitHub.

## Fitur
- Input foto jadwal produksi.
- OCR berbasis Tesseract.js.
- Pemetaan flavour berdasarkan posisi horizontal per baris Line ke tiga shift.
- Editor manual untuk koreksi hasil OCR.
- Buku digital tiga shift.
- Pengaturan judul dan jumlah kolom.
- Simpan data lokal pada browser.
- Ekspor gambar, cetak/PDF, dan berbagi melalui menu Android.
- Tampilan hitam–emas; tanpa logo perusahaan dan tanpa video.

## Catatan penting
- OCR perlu diuji dengan foto jadwal asli. Sudut foto, kualitas cetak, dan kemiringan tabel dapat memengaruhi hasil. Selalu cocokkan hasil dengan foto sumber.
- Jangan mengunggah foto jadwal internal perusahaan ke repository publik. Paket ini tidak menyertakan foto contoh jadwal.
- Aplikasi ini alat bantu pencatatan, bukan sistem resmi perusahaan.
