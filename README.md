# task-5-pbi-btpns-roihan-sori-nasution
Final Task  - Project-Based Intern: Fullstack Developer Virtual Internship Experience BTPN Syariah


# Endpoint API

## Endpoint Auth
Endpoint ini bertanggung jawab membuat generate token untuk token ke endpoint pengelolaan.
Method | Path | Keterangan | Auth
------------- | ------------- | ------------- | -------------
***POST*** | *`/api/users/login`* | Untuk masuk ke akun yang telah dibuat .
***POST*** | *`/api/users/register`* | Membuat akun user untuk akses endpoint

## Endpoint User
Endpoint ini bertanggung jawab mengelola user.
Method | Path | Keterangan | Auth
------------- | ------------- | ------------- | -------------
***GET*** | *`/api/users/:id`* | Mengakses data pengguna berdasakan id pengguna | token
***PUT*** | *`/api/users/:id`* | Mengubah data pengguna berdasakan id pengguna | token
***DELETE*** | *`/api/users/:id`* | Menghapus data pengguna berdasakan id pengguna | token

## Endpoint Photo
Endpoint ini bertanggung jawab mengelola photo.
Method | Path | Keterangan | Auth
------------- | ------------- | ------------- | -------------
***GET*** | *`/api/photos`* | Mengakses data foto | token
***GET*** | *`/api/photos/:id`* | Mengakses data pengguna berdasakan id foto | token
***POST*** | *`/api/photos`* | Membuat data foto baru | token
***PUT*** | *`/api/photos/:id`* | Mengubah data foto berdasakan id foto | token
***DELETE*** | *`/api/photos/:id`* | Menghapus data foto berdasakan id foto | token

## Instalasi

Untuk menjalankan proyek ini secara lokal, pastikan Anda telah menginstal GoLang. Berikut langkah-langkah umum instalasi GoLang:

1. **Unduh GoLang**: Unduh dan instal GoLang dari [situs resmi GoLang](https://golang.org/dl/).

2. **Konfigurasi Lingkungan**: Setelah menginstal, pastikan Anda mengatur variabel lingkungan seperti `GOPATH` dan `PATH` sesuai dengan dokumentasi GoLang.

3. **Klon Proyek**: Klon repositori ini ke komputer Anda.
4. **Buka Postgres** Buat database baru kemudian copy file .env_example
5. **Jalankan**: Buka terminal, masuk ke direktori proyek, dan jalankan aplikasi dengan perintah:

   ```bash
   # 1. Buka terminal.

   # 2. Pastikan Anda berada dalam direktori proyek.

   # 3. Jalankan aplikasi dengan perintah berikut:
   go run main.go
   ```
Untuk menjalankan proyek ini menggunakkan docker, pastikan Anda telah menginstal Docker. 

**Jalankan**: Buka terminal, masuk ke direktori proyek, dan jalankan aplikasi dengan perintah:

   ```bash
   # 1. Buka terminal.

   # 2. Pastikan Anda berada dalam direktori proyek.

   # 3. Jalankan aplikasi dengan perintah berikut:
      - docker compose build
      - make migrate-up
   ```
Aplikasi akan berjalan di http://localhost:3000
## Tools 🛠

[![My Skills](https://skillicons.dev/icons?i=go,git,postgres,postman,vscode,docker)](https://skillicons.dev)
