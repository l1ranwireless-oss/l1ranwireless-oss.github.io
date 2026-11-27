# L1ran Wireless OSS

Homepage resmi L1ran Wireless OSS dengan halaman Tools Finder berbasis HTML, CSS, dan JavaScript tanpa dependensi build.

## Menjalankan secara lokal

```bash
python3 -m http.server 8080
```

Buka `http://localhost:8080` di browser. Tools Finder tersedia di `http://localhost:8080/tools-finder.html`.

## Fitur Tools Finder

- Pilih folder secara eksplisit di browser yang mendukung File System Access API.
- Cari beberapa nama file dengan mode mengandung, wildcard (`*` dan `?`), atau persis.
- Ekspor hasil ke CSV dan salin lokasi hasil.
- Pencarian dilakukan lokal di browser; file dan hasil pencarian tidak diunggah ke situs.

GitHub Pages menyajikan situs dari repository ini. Navigasi **My Works** mengarah ke `https://l1ranwireless-oss.github.io/POT-Compile`.

> Catatan: akses folder memerlukan persetujuan pengguna dan dukungan browser. Browser tidak memberikan path absolut. Fitur login/autentikasi aman tidak dapat dibuat hanya dengan frontend statis; jangan simpan password atau secret di kode frontend.
