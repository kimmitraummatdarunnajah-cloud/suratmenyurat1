# 📋 SiSuRAT PKP
### Sistem Surat Masuk & Keluar
**Bidang Perumahan dan Kawasan Permukiman**  
Dinas Perumahan, Permukiman, Pertanahan dan Lingkungan Hidup  
Kabupaten Kapuas Hulu — Provinsi Kalimantan Barat

---

## 🌐 Akses Aplikasi Online

🔗 **[Buka Aplikasi](https://USERNAME.github.io/surat-pkp)**

> Ganti `USERNAME` dengan username GitHub Anda setelah deploy.

---

## ✨ Fitur Aplikasi

| Fitur | Keterangan |
|-------|-----------|
| 📊 Dashboard | Ringkasan statistik surat & aktivitas terkini |
| 📥 Surat Masuk | Input, cari, filter, dan kelola surat masuk |
| 📤 Surat Keluar | Input, cari, filter, dan kelola surat keluar |
| 📎 File Lampiran | Upload, preview, dan unduh file lampiran |
| 📋 Rekap & Laporan | Grafik bulanan + tabel rekapitulasi |
| 🗄️ Arsip Surat | Arsip lengkap surat masuk & keluar |
| ⬇️ Export CSV | Export data ke file CSV |

---

## 🚀 Cara Deploy ke GitHub Pages

### Langkah 1 — Buat Repository GitHub

1. Login ke [github.com](https://github.com)
2. Klik tombol **"New"** atau buka [github.com/new](https://github.com/new)
3. Isi nama repository: **`surat-pkp`**
4. Pilih **Public** (wajib agar GitHub Pages bisa aktif)
5. Klik **"Create repository"**

---

### Langkah 2 — Upload File ke Repository

**Cara A — Upload Langsung (Mudah, tanpa Git)**

1. Buka repository yang baru dibuat
2. Klik **"uploading an existing file"** atau **"Add file → Upload files"**
3. Seret & lepas **semua file** dari folder ini ke halaman upload:
   - `index.html`
   - `README.md`
   - `.nojekyll`
4. Tulis pesan commit: `"Upload aplikasi SiSuRAT PKP"`
5. Klik **"Commit changes"**

**Cara B — Via Git (jika sudah install Git)**

```bash
# Clone repository kosong yang sudah dibuat
git clone https://github.com/USERNAME/surat-pkp.git
cd surat-pkp

# Salin semua file ke folder ini
# Lalu commit dan push
git add .
git commit -m "Upload aplikasi SiSuRAT PKP"
git push origin main
```

---

### Langkah 3 — Aktifkan GitHub Pages

1. Di halaman repository, klik tab **"Settings"**
2. Di menu kiri, scroll ke bawah dan klik **"Pages"**
3. Di bagian **"Source"**, pilih:
   - Branch: **`main`**
   - Folder: **`/ (root)`**
4. Klik **"Save"**
5. Tunggu 1–3 menit
6. Akan muncul notifikasi hijau:  
   **"Your site is live at https://USERNAME.github.io/surat-pkp"**

---

## 💾 Penyimpanan Data

Aplikasi menggunakan **localStorage** browser — data tersimpan di browser pengguna masing-masing. Data **tidak hilang** saat refresh halaman, namun:

- Data berbeda antar browser / perangkat
- Hapus cache browser = data hilang
- Untuk backup: gunakan fitur **Export CSV** secara berkala

---

## 📱 Kompatibilitas

| Platform | Status |
|----------|--------|
| Chrome (Desktop) | ✅ Penuh |
| Edge (Desktop) | ✅ Penuh |
| Firefox (Desktop) | ✅ Penuh |
| Safari (Desktop) | ✅ Penuh |
| Chrome (Android) | ✅ Responsif |
| Safari (iOS) | ✅ Responsif |

---

## 🛠️ Teknologi

- **HTML5** + **CSS3** + **JavaScript** (Vanilla, tanpa framework)
- **Font:** DM Sans, DM Serif Display, JetBrains Mono (Google Fonts)
- **Penyimpanan:** localStorage Browser
- **Hosting:** GitHub Pages (gratis)

---

## 📞 Informasi Instansi

**Bidang Perumahan dan Kawasan Permukiman**  
Dinas Perumahan, Permukiman, Pertanahan dan Lingkungan Hidup (PerkimTanLH)  
Kabupaten Kapuas Hulu, Provinsi Kalimantan Barat

---

*Dibuat dengan ❤️ untuk pelayanan administrasi surat yang lebih baik*
