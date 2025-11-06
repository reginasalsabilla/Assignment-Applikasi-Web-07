# Assignment-Applikasi-Web-07
Web Laragon - Registrasi Zoo
Program ini merupakan sebuah halaman registrasi pengguna berbasis PHP dan MySQL yang berfungsi untuk menyimpan data pendaftaran pengguna ke dalam database. Program dibuat menggunakan bahasa pemrograman PHP dengan tampilan sederhana dari HTML dan CSS. Melalui halaman registrasi ini, pengguna dapat mengisi data seperti nama lengkap, alamat email, username, dan password. Data yang dimasukkan kemudian akan disimpan secara otomatis ke dalam tabel bernama pengguna di database db_registrasi.

Aplikasi ini menggunakan fungsi password_hash() untuk mengenkripsi password agar lebih aman. Struktur database terdiri dari kolom id, nama, email, username, password, dan tanggal_daftar. Untuk menjalankan program, server lokal seperti Laragon atau XAMPP harus diaktifkan terlebih dahulu, kemudian folder proyek disimpan di direktori htdocs atau www. Setelah itu, halaman dapat diakses melalui browser dengan alamat (http://week07assignment.test/registrasi.php)

Ketika form registrasi diisi dan tombol Daftar ditekan, data pengguna akan tersimpan di dalam tabel pengguna. Hasil penyimpanan dapat dilihat HSQL pada database db_registrasi. Program ini dibuat sebagai latihan dasar dalam pembuatan form, pengolahan data input, dan koneksi ke database menggunakan PHP.
