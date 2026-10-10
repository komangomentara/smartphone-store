# Smartphone Store — React + Tailwind CSS

Proyek tugas Evaluasi 1 Pemrograman Web. Aplikasi katalog smartphone dengan halaman dashboard, detail produk, keranjang, dan checkout simulasi.

## Teknologi
- React + Vite
- Tailwind CSS
- React Router
- Context API (`useContext`) dan `useState`
- Lucide React untuk ikon

## Cara menjalankan
Pastikan Node.js dan npm sudah terpasang.

```bash
npm install
npm run dev
```

Buka URL lokal yang ditampilkan di terminal, biasanya `http://localhost:5173`.

Untuk menguji build produksi:
```bash
npm run build
npm run preview
```

## Konsep React yang diterapkan
- **Component:** Navbar, ProductCard, MainLayout, Dashboard, ProductDetail, Cart, Checkout.
- **Passing props:** data produk dikirim dari Dashboard ke ProductCard melalui prop `product`; fungsi tambah keranjang dikirim melalui prop `onAdd`.
- **Conditional rendering:** pesan keranjang kosong, produk tidak ditemukan, detail produk tidak valid, validasi form, dan konfirmasi pesanan.
- **useState:** pencarian, kategori, pengurutan, isi keranjang, kuantitas, data formulir, dan error.
- **useContext:** CartContext membagikan data dan fungsi keranjang ke berbagai komponen.
- **React Router:** rute `/`, `/product/:id`, `/cart`, dan `/checkout`.

## Catatan
Data produk masih dummy. Checkout hanya simulasi; aplikasi belum memakai backend, database, autentikasi, atau pembayaran nyata. Pastikan memeriksa gambar produk dan mengganti gambar yang tidak tampil sebelum pengumpulan.
