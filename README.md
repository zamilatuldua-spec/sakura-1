# Sakura Auto Drama AI - Versi 1 (Dashboard + Import Video)

## Cara membuat APK tanpa Android Studio (dari HP/browser)
1. Buat akun GitHub, buat repository baru (private tidak apa-apa).
2. Unggah seluruh isi folder ini (termasuk folder `.github`).
3. Buka tab **Actions** -> workflow **Build APK** -> tunggu hijau (3-6 menit).
4. Buka run tersebut -> bagian **Artifacts** -> unduh `SakuraAutoDrama-debug-apk` (ZIP, ekstrak, ambil `app-debug.apk`).
5. Di HP: izinkan "Install dari sumber tidak dikenal", lalu pasang APK.

## Cara build dengan Android Studio (di PC)
Open project -> Build > Build APK(s). Hasil: `app/build/outputs/apk/debug/app-debug.apk`.

## Daftar uji Versi 1
- [ ] Aplikasi terbuka tanpa crash di Android 10+
- [ ] Pilih tema / bahasa / durasi, status ikut berubah
- [ ] Impor video dari galeri atau file manager, preview bisa diputar
- [ ] Tombol START/PAUSE/STOP tampil nonaktif (sengaja, aktif di versi berikutnya)
