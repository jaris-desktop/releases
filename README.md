# Jaris — Aplikasi Desktop

Aplikasi manajemen keuangan & tabungan sekolah/yayasan yang berjalan **offline** di
komputer Anda (Windows, macOS, Linux). Data tersimpan lokal dan terenkripsi.

## ⬇️ Unduh

**[Unduh versi terbaru →](https://github.com/jaris-desktop/releases/releases/latest)**

Pilih file sesuai sistem operasi Anda pada bagian **Assets**:

| Sistem | File yang diunduh |
|---|---|
| **Windows** | `Jaris Setup x.y.z.exe` |
| **macOS** (Apple Silicon — M1/M2/M3/M4) | `Jaris-x.y.z-arm64.dmg` |
| **macOS** (Intel) | `Jaris-x.y.z-x64.dmg` |
| **Linux** | `Jaris-x.y.z.AppImage` |

> File `.zip` (macOS) dan `Source code` dibuat otomatis oleh GitHub — **abaikan saja**,
> cukup unduh installer di tabel atas.

## 📦 Cara Instal

### Windows
1. Unduh `Jaris Setup x.y.z.exe`, jalankan.
2. Jika muncul layar biru **"Windows protected your PC"** → klik **More info** → **Run anyway**.
   (Muncul karena aplikasi belum ditandatangani secara digital — bukan virus.)
3. Ikuti wizard instalasi.

### macOS
1. Unduh `.dmg` sesuai tipe chip Anda (arm64 untuk Apple Silicon, x64 untuk Intel).
2. Buka `.dmg`, seret **Jaris** ke folder **Applications**.
3. Saat **pertama kali** membuka: **klik-kanan** ikon Jaris → **Open** → **Open** lagi.
   (Jangan dobel-klik biasa — akan ditolak karena app belum ditandatangani.)
4. Jika muncul pesan **"aplikasi rusak / is damaged"**, buka **Terminal** lalu jalankan:
   ```bash
   xattr -dr com.apple.quarantine /Applications/Jaris.app
   ```
   Setelah itu buka lagi seperti langkah 3.

### Linux
1. Unduh `Jaris-x.y.z.AppImage`.
2. Beri izin jalankan:
   ```bash
   chmod +x Jaris-*.AppImage
   ```
3. Dobel-klik, atau jalankan `./Jaris-*.AppImage`.

## 💻 Kebutuhan Sistem

- **Windows** 10 atau lebih baru (64-bit)
- **macOS** 11 (Big Sur) atau lebih baru
- **Linux** distro modern 64-bit dengan dukungan AppImage

## 🔒 Catatan Keamanan

Aplikasi ini **belum ditandatangani secara digital (unsigned)**, sehingga sistem operasi
menampilkan peringatan "publisher tidak dikenal" saat pertama dijalankan. Ini **normal**
untuk aplikasi yang didistribusikan langsung dan bukan berarti berbahaya. Setiap file
installer disertai **checksum SHA-256** di halaman rilis untuk verifikasi keaslian.

## 🆘 Bantuan

Jika mengalami kendala instalasi, hubungi tim dukungan Anda.
