# Rava. - Belanja Pilihan, Hidup Lebih Rapi

Rava adalah website toko online sederhana (landing page e-commerce) dengan konsep **"Pilih sedikit, pakai lama."** Menampilkan produk harian yang simpel, awet, dan berharga masuk akal. Dibangun dengan HTML dan CSS murni, tanpa framework dan tanpa JavaScript.

## Fitur

- Banner pengumuman gratis ongkir
- Header sticky dengan efek blur dan menu navigasi
- Hero section dengan statistik pesanan dan rating pembeli
- Kategori belanja: Elektronik, Fashion, Rumah, Aksesori
- Koleksi produk pilihan dalam bentuk kartu produk
- Section layanan: pengiriman cepat, pembayaran fleksibel, garansi 7 hari
- Footer dengan tautan bantuan dan informasi toko
- Desain responsif untuk desktop, tablet, dan HP
- Smooth scroll dan animasi hover

## Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| HTML5 | Struktur halaman |
| CSS3 | Styling, grid, flexbox, dan media query |
| Google Fonts | Fraunces (judul) dan Inter (teks) |

## Struktur Proyek

```
rava/
├── index.html
├── style.css
├── README.md
└── images/
    ├── hero.svg
    ├── kategori-elektronik.svg
    ├── kategori-fashion.svg
    ├── kategori-rumah.svg
    ├── kategori-aksesori.svg
    ├── headphone.svg
    ├── tas-harian.svg
    ├── lampu-meja.svg
    └── jam-minimalis.svg
```

## Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/rava.git
   ```
2. Masuk ke folder proyek:
   ```bash
   cd rava
   ```
3. Buka `index.html` langsung di browser, atau jalankan dengan server lokal:
   ```bash
   npx serve .
   ```

## Palet Warna

| Warna | Kode |
|-------|------|
| Hijau | `#2f4a3a` |
| Hijau Tua | `#1f3328` |
| Hijau Muda | `#e3ebe2` |
| Krem | `#f6f1e7` |
| Pasir | `#ebe3d3` |
| Tanah | `#c76a3f` |

## Breakpoint Responsif

- **Desktop**: di atas 960px
- **Tablet**: maksimal 960px (menu disembunyikan, grid produk 3 kolom)
- **HP**: maksimal 700px (grid produk 2 kolom, layout satu kolom)

## Rencana Pengembangan

- [ ] Keranjang belanja
- [ ] Halaman detail produk
- [ ] Pencarian dan filter produk
- [ ] Menu navigasi untuk mobile (hamburger)
- [ ] Integrasi pembayaran

## Lisensi

Proyek ini dirilis di bawah lisensi [MIT](LICENSE).

&copy; 2026 Rava. Semua hak dilindungi.
