# Survive KRL

Game hyper-casual mobile (portrait) — berdiri di KRL dari Tebet ke Manggarai tanpa nyusruk.

- Satu file `index.html` (HTML + CSS + vanilla JS). Grafis 3D pakai Three.js r128 dari CDN cdnjs (butuh internet).
- Kontrol default: geser jempol kiri/kanan (pindah posisi + nangkep badan pas oleng). Mode lama (tahan kiri/kanan + swipe) bisa dipilih di menu pause.
- Item (Kayu Putih, Kursi Prioritas) dibeli di Store via QRIS **simulasi** — tidak ada transaksi uang sungguhan.

## Main lokal
Buka `index.html` di browser.

## Deploy ke Cloudflare Pages
Connect repo ini di Cloudflare Pages → Framework preset: **None**, build command: kosong, output directory: `/`.
