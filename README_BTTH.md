# DonghuaBox - BTTH Edition (动画盒)

Aplikasi klien proxy Android kustom bertema **Battle Through the Heavens (Doupo Cangqiong)** berbasis repositori NekoBoxForAndroid (`hanzani19-alt/DonghuaBox`).

## Struktur File Kustomisasi
- `app/src/main/res/values/strings.xml` — Identitas nama aplikasi **DonghuaBox** & subjudul BTTH.
- `app/src/main/res/values/colors.xml` — Palet warna khas Xiao Yan (Flame Orange, Flame Gold, Jade Cyan, Void Background).
- `app/src/main/res/values/themes.xml` — Konfigurasi tema gelap Material 3.
- `app/src/main/res/drawable/bg_btth_card.xml` — Latar kartu profil dengan border spiritual.
- `app/src/main/res/drawable/bg_btth_flame_button.xml` — Gradien tombol koneksi *Heavenly Flame*.
- `.github/workflows/build-donghuabox.yml` — Workflow otomatis untuk kompilasi APK via GitHub Actions.

## Cara Pemasangan ke Repositori GitHub
1. Ekstrak seluruh isi file ZIP ini ke root folder repositori `DonghuaBox` milikmu (`hanzani19-alt/DonghuaBox`).
2. Pastikan struktur folder `app/src/main/res/` dan `.github/workflows/` menyatu dengan struktur proyek NekoBox.
3. Commit dan push perubahan ke branch utama (`main` / `master`).
4. Buka tab **Actions** di GitHub, jalankan atau tunggu workflow **Build DonghuaBox BTTH APK**, lalu unduh file APK dari bagian **Artifacts**.
