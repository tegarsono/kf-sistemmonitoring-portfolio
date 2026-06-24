# Kimia Farma GA System - Static Version

Versi statis dari sistem General Affair Kimia Farma Apotek yang dapat di-deploy ke Vercel.

## 📋 Struktur Folder

```
static-site/
├── index.html              # Hub/Dashboard utama
├── auth/
│   └── login.html          # Halaman login
├── ga/
│   ├── home.html           # Dashboard GA
│   ├── kendaraan/
│   │   └── index.html      # Manajemen Kendaraan
│   ├── tanah_bangunan/
│   │   └── index.html      # Manajemen Tanah & Bangunan
│   ├── atk/
│   │   └── index.html      # Alat Tulis Kantor
│   ├── biaya/
│   │   └── index.html      # Biaya Umum
│   └── dir/
│       └── index.html      # Data Induk Rumah
├── driver/
│   ├── home.html           # Dashboard Driver
│   ├── jadwal/
│   │   └── index.html      # Jadwal Tugas
│   ├── mobil/
│   │   └── index.html      # Data Mobil
│   └── supir/
│       └── index.html      # Data Supir
├── ac-monitoring/
│   └── index.html          # Monitoring Maintenance AC
├── profile/
│   └── index.html          # Profil Saya
├── settings/
│   └── index.html          # Pengaturan Gambar
├── img/
│   ├── kf.png              # Logo Kimia Farma
│   └── banner-container.jpeg  # Background hero
└── vercel.json             # Konfigurasi Vercel
```

## 🚀 Deployment ke Vercel

### Metode 1: Via Vercel CLI

1. **Install Vercel CLI** (jika belum ada):
   ```bash
   npm i -g vercel
   ```

2. **Masuk ke folder static-site**:
   ```bash
   cd static-site
   ```

3. **Deploy ke Vercel**:
   ```bash
   vercel
   ```

4. **Follow prompt**:
   - Setuju dengan konfigurasi? (Y)
   - Project name? (Enter untuk default)
   - Deploy? (Y)

### Metode 2: Via Vercel Dashboard (Git)

1. **Push ke GitHub/GitLab/Bitbucket**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. **Import di Vercel**:
   - Buka [vercel.com](https://vercel.com)
   - Klik "Add New Project"
   - Import repository Anda
   - Vercel akan otomatis detect sebagai static site
   - Klik "Deploy"

### Metode 3: Drag & Drop

1. **Buka** [vercel.com/new](https://vercel.com/new)
2. **Drag folder `static-site`** ke area upload
3. **Tunggu deploy selesai**

## ✨ Fitur

- ✅ **Tampilan identik** dengan versi Laravel
- ✅ **Semua halaman** dapat diakses
- ✅ **Gambar tampil** dengan benar
- ✅ **Responsive** untuk mobile & desktop
- ✅ **Sidebar navigation** dengan collapse/expand
- ✅ **Interactive elements** (tables, modals, alerts)
- ✅ **Chart.js** untuk grafik (GA Dashboard)
- ✅ **SweetAlert2** untuk dialog/interaksi
- ✅ **Bootstrap 5** untuk styling

## 📱 Halaman yang Tersedia

1. **Hub Utama** (`index.html`) - Dashboard dengan 3 card sistem
2. **Login** (`auth/login.html`) - Halaman autentikasi
3. **GA Dashboard** (`ga/home.html`) - Dashboard dengan charts
4. **Manajemen Kendaraan** (`ga/kendaraan/index.html`)
5. **Tanah & Bangunan** (`ga/tanah_bangunan/index.html`)
6. **ATK** (`ga/atk/index.html`)
7. **Biaya Umum** (`ga/biaya/index.html`)
8. **DIR** (`ga/dir/index.html`)
9. **Driver Dashboard** (`driver/home.html`)
10. **Jadwal Tugas** (`driver/jadwal/index.html`)
11. **Data Mobil** (`driver/mobil/index.html`)
12. **Data Supir** (`driver/supir/index.html`)
13. **AC Monitoring** (`ac-monitoring/index.html`)
14. **Profil Saya** (`profile/index.html`)
15. **Pengaturan** (`settings/index.html`)

## 🔧 Teknologi yang Digunakan

- **HTML5** - Struktur halaman
- **CSS3** - Styling (embedded dalam setiap halaman)
- **JavaScript (Vanilla)** - Interaksi & functionality
- **Bootstrap 5.3.3** - Framework CSS
- **Font Awesome 6.5.2** - Icons
- **Chart.js** - Grafik & charts
- **SweetAlert2** - Beautiful alerts & modals
- **Google Fonts** - Typography (Inter, Segoe UI, Poppins)

## 📝 Catatan

- Ini adalah versi **static/demo** dari aplikasi Laravel
- Data yang ditampilkan adalah **sample data** (hardcoded)
- Tidak ada backend/database (CRUD operations hanya simulasi)
- Login menggunakan localStorage (simulasi autentikasi)
- Untuk production dengan database, gunakan versi Laravel asli

## 🎨 Tampilan

Tampilan **tidak berubah** dari versi Laravel asli:
- Sidebar navigation yang sama
- Warna dan tema yang konsisten
- Layout dan spacing yang identik
- Semua icons dan elemen visual tetap sama

## 📄 License

PT Kimia Farma Apotek - Internal Use Only