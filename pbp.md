# Analisis Komparatif Platform Aplikasi

## 1. Perbandingan Platform Web, Desktop, dan Mobile

| Aspek           | Web                                                                                                                                                  | Desktop                                                                                                                      | Mobile                                                                                                                         |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Bahasa utama    | HTML untuk struktur halaman, CSS untuk tampilan, serta JavaScript untuk mengatur interaksi pengguna                                                  | C#, Java, C++, atau Python sesuai kebutuhan dan lingkungan pengembangan aplikasi                                             | Kotlin untuk Android, Swift untuk iOS, serta Dart jika menggunakan Flutter                                                     |
| Arsitektur      | Pengguna mengakses antarmuka melalui browser, sedangkan proses dan penyimpanan data dapat ditangani oleh server                                      | Program dipasang pada komputer dan dapat berinteraksi langsung dengan sistem operasi serta sumber daya lokal                 | Aplikasi berjalan di perangkat genggam dan memanfaatkan layanan sistem operasi serta fitur bawaan perangkat                    |
| Cara distribusi | Pengembang menempatkan aplikasi di server sehingga pengguna dapat membukanya melalui alamat web                                                      | Pengguna mengunduh paket instalasi atau memasang aplikasi melalui toko aplikasi desktop                                      | Pengguna memasang aplikasi melalui toko aplikasi resmi atau distribusi khusus                                                  |
| Keunggulan      | Cocok untuk layanan yang digunakan banyak orang karena pengguna tidak perlu memasang aplikasi secara terpisah dan pembaruan dapat dilakukan terpusat | Cocok untuk pekerjaan yang membutuhkan pengolahan data besar, penggunaan periferal, atau integrasi dengan perangkat komputer | Mendukung aktivitas yang membutuhkan akses cepat saat bepergian, termasuk pemanfaatan kamera, GPS, sensor, dan notifikasi      |
| Keterbatasan    | Pengalaman penggunaan dapat dipengaruhi kualitas jaringan, kemampuan browser, dan keterbatasan akses ke perangkat tertentu                           | Pengembang perlu mempertimbangkan kompatibilitas sistem operasi, proses instalasi, serta distribusi pembaruan                | Pengembangan dan pengujian perlu memperhatikan ukuran layar, konsumsi baterai, kapasitas perangkat, dan variasi sistem operasi |
| Contoh aplikasi | Sistem akademik kampus melalui browser, Google Docs versi web, dan Trello versi web                                                                  | Aplikasi kasir yang dipasang di komputer, Visual Studio Code, dan Adobe Photoshop Desktop                                    | Aplikasi pemesanan transportasi, Google Maps, dan aplikasi mobile perbankan                                                    |

## 2. Analisis dan Perbandingan

Ketiga platform memiliki tujuan penggunaan yang berbeda. Web lebih sesuai ketika aplikasi perlu dijangkau melalui berbagai perangkat tanpa proses instalasi khusus. Sebagai contoh, sistem informasi akademik kampus dapat dibuka mahasiswa dan dosen melalui browser dari perangkat masing-masing.

Platform desktop lebih tepat ketika aplikasi membutuhkan kemampuan komputer secara intensif atau harus bekerja dengan perangkat lokal. Contohnya, aplikasi pengolahan video membutuhkan sumber daya komputer yang memadai agar proses penyuntingan berjalan lancar.

Sementara itu, platform mobile lebih sesuai untuk layanan yang digunakan secara langsung dalam kegiatan sehari-hari. Aplikasi pemesanan transportasi, misalnya, memerlukan GPS untuk mengetahui posisi pengguna dan notifikasi untuk memberikan informasi perjalanan.

Menurut analisis saya, pemilihan platform tidak cukup hanya berdasarkan teknologi yang sedang populer. Pengembang perlu mempertimbangkan siapa penggunanya, di mana aplikasi digunakan, seberapa besar kebutuhan pemrosesan data, serta apakah aplikasi harus tetap berfungsi ketika koneksi internet tidak tersedia.

## 3. Kesimpulan

Platform web, desktop, dan mobile mempunyai kelebihan serta batasan masing-masing. Web unggul dalam kemudahan akses dan pembaruan terpusat, desktop unggul dalam pemanfaatan sumber daya komputer, sedangkan mobile unggul dalam mobilitas dan penggunaan fitur perangkat.

Apabila sebuah kampus ingin mengembangkan sistem informasi akademik yang dapat diakses mahasiswa dan dosen dari berbagai lokasi, platform web dapat menjadi pilihan awal yang efektif. Namun, jika sistem membutuhkan fungsi khusus pada perangkat atau penggunaan tanpa internet, pengembang perlu mempertimbangkan desktop atau mobile, bahkan menggabungkan beberapa platform jika memang dibutuhkan.

## 4. Daftar Referensi

1. MDN Web Docs. _Getting started with the web_.  
   https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started

2. Microsoft Learn. _Desktop Guide for .NET_.  
   https://learn.microsoft.com/en-us/dotnet/desktop/

3. Android Developers. _Application fundamentals_.  
   https://developer.android.com/guide/components/fundamentals

4. Apple Developer. _App development_.  
   https://developer.apple.com/develop/

## 5. Refleksi Pembelajaran

### 1. Platform yang Paling Menarik untuk Dipelajari

Menurut saya, platform web merupakan platform yang paling menarik untuk dipelajari. Hal ini karena aplikasi web dapat diakses melalui browser tanpa harus memasang aplikasi khusus di setiap perangkat. Selain itu, pengembangan web memungkinkan saya mempelajari HTML, CSS, dan JavaScript secara bertahap. Saya juga tertarik karena aplikasi web dapat digunakan untuk berbagai kebutuhan, seperti sistem informasi akademik, toko online, dan layanan administrasi. Pengetahuan tersebut dapat menjadi bekal untuk mengembangkan aplikasi yang bermanfaat bagi masyarakat.

### 2. Tantangan Terbesar Saat Setup Environment

Tantangan terbesar yang saya alami saat menyiapkan environment adalah memahami penggunaan Git dan menghubungkannya dengan repository GitHub. Saya sempat mengalami kendala ketika menambahkan file karena nama file yang digunakan tidak sesuai dengan nama file yang tersedia. Selain itu, proses commit mengalami kegagalan karena identitas nama dan email Git belum dikonfigurasi. Saya juga perlu memahami perbedaan antara menyimpan perubahan secara lokal dan mengirimkannya ke GitHub.

### 3. Rencana Mengatasi Tantangan

Untuk mengatasi tantangan tersebut, saya akan mempelajari kembali perintah dasar Git, seperti git status, git add, git commit, dan git push. Saya juga akan membiasakan diri memeriksa nama file dan lokasi folder sebelum menjalankan perintah. Jika mengalami kesalahan, saya akan membaca pesan error dengan teliti dan mencari solusinya melalui dokumentasi resmi atau bertanya kepada dosen dan teman. Dengan latihan secara rutin, saya berharap lebih memahami alur kerja pengembangan aplikasi dan dapat bekerja sama dalam proyek kelompok dengan lebih baik.
