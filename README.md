# PerancanganWeb-DesainGrafis-BisDig

file:///C:/xampp/htdocs/xampp/fegi%204html.html

# PerancanganWeb-DesainGrafis-BisDig

Repository ini berisi contoh implementasi interaktivitas sederhana pada halaman web menggunakan JavaScript. Proyek ini menampilkan bagaimana tombol "Tampilkan Komentar" dapat dibuat untuk menyembunyikan dan menampilkan bagian komentar secara dinamis tanpa me-reload halaman.

## Tujuan Proyek

Tujuan dari proyek ini adalah untuk mendemonstrasikan:
1.  Penggunaan dasar JavaScript untuk menambahkan interaktivitas pada elemen HTML.
2.  Konsep manipulasi DOM (Document Object Model) untuk mengubah gaya dan konten elemen.
3.  Bagaimana peristiwa (events) seperti klik dapat ditangani dengan JavaScript.

## Bagaimana JavaScript Menciptakan Interaktivitas Ini

JavaScript adalah bahasa scripting yang memungkinkan halaman web menjadi dinamis dan responsif terhadap interaksi pengguna. Untuk fitur "Tampilkan Komentar" ini, JavaScript bekerja sebagai berikut:

1.  **Event Listening**: JavaScript "mendengarkan" peristiwa `click` pada tombol "Tampilkan Komentar".
2.  **DOM Manipulation**: Saat tombol diklik, JavaScript mendapatkan referensi ke elemen HTML yang berisi komentar (`commentsSection`) dan elemen tombol itu sendiri (`toggleCommentsBtn`).
3.  **Mengubah Properti CSS**: Dengan mengakses properti `style.display` dari elemen komentar, JavaScript dapat mengubah visibilitasnya. Jika `display` adalah `none` (tersembunyi), JavaScript mengubahnya menjadi `block` (terlihat), dan sebaliknya.
4.  **Logika Kondisional**: JavaScript menggunakan pernyataan `if/else` untuk memeriksa status tampilan komentar saat ini dan memutuskan apakah akan menampilkannya atau menyembunyikannya, serta mengubah teks tombol sesuai dengan aksi yang akan dilakukan.

## Struktur Proyek
