# FE-PBF-KRS

FE-PBF-KRS adalah aplikasi web frontend untuk sistem Kartu Rencana Studi (KRS) yang dibangun menggunakan Laravel. Proyek ini bertujuan untuk memudahkan mahasiswa dalam menyusun KRS secara online dan memberikan admin kemudahan dalam mengelola data mahasiswa dan mata kuliah.

## Fitur

-   Autentikasi pengguna (login & registrasi)
-   Manajemen data mahasiswa
-   Manajemen data mata kuliah
-   Penyusunan KRS online
-   Tampilan dashboard yang responsif
-   Export File Excel dan PDF pada masing-masing tabel

## Teknologi yang Digunakan

-   Laravel
-   PHP
-   MySQL
-   JavaScript
-   HTML & CSS
-   Blade Template dari adminlte

## Instalasi

### 1. Clone repositori

```bash
git clone https://github.com/ndan47/FE-PBF-KRS.git
cd FE-PBF-KRS


### 2. Instal dependensi PHP
composer install

### 3. Instal dependensi JavaScript
npm install


### 4. Salin file .env dan konfigurasi
cp .env.example .env
php artisan key:generate

### Sesuaikan konfigurasi database dan lainnya di file .env.

### 5. Nyalakan Web Server menggunakan Laragon atau XAMPP
### 6. Jalankan server lokal
php artisan serve

### Aplikasi akan berjalan di http://localhost:8000.

## Struktur Direktori
app/ - Berisi logika aplikasi dan model

bootstrap/ - File bootstrap Laravel

config/ - Konfigurasi aplikasi

database/ - Migrasi dan seeder

public/ - Entry point aplikasi

resources/ - View dan aset frontend

routes/ - Definisi rute aplikasi

storage/ - File yang dihasilkan aplikasi
###

# Kontribusi

 Kontribusi sangat terbuka! Silakan fork repositori ini dan ajukan pull request untuk perbaikan atau penambahan fitur.
```
