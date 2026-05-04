# Analisis Penjualan E-Commerce Shopee Indonesia (2024–2025)

## 1. Latar Belakang
Analisis eksplorasi data (EDA) terhadap data transaksi penjualan e-commerce Shopee periode 2024–2025. Analisis dilakukan dari perspektif Data Analyst untuk mengidentifikasi pola penjualan dan menghasilkan rekomendasi bisnis yang actionable.

## Tujuan
- Mengidentifikasi produk terlaris dan kategori dengan cancellation rate tinggi
- Memahami tren revenue bulanan dan pola order harian
- Memetakan distribusi geografis pembeli di Indonesia
- Menganalisis perilaku transaksi (metode pembayaran & opsi pengiriman)

## Struktur Project
EDA_Shopee/
├── data/
│   ├── raw/          # File Excel mentah per bulan
│   └── clean/        # Dataset gabungan setelah cleaning
├── notebook/
│   └── EDA_Shopee.ipynb
└── README.md

## Tools yang Digunakan
Berikut adalah tools/library yang digunakan dalam analisis ini:

- **Python 3.11** sebagai bahasa pemrograman utama
- **Jupyter Notebook** sebagai environment development
- **Pandas** untuk manipulasi dan analisis data
- **Seaborn** untuk visualisasi data

## Dataset
- **Sumber:** Kaggle — Indonesia E-Commerce Sales & Shipping 2023–2025
- **Periode:** Desember 2023 – November 2025
- **Total data:** 21.426 transaksi setelah cleaning
- **Fitur:** 16 kolom mencakup produk, waktu, lokasi, pembayaran, dan pengiriman

## Ringkasan Temuan
| Dimensi | Temuan Utama |
|---|---|
| **Produk** | Nampan/Tray terlaris, Rak Serbaguna cancellation rate ~30% |
| **Waktu** | Peak revenue Oktober 2024, jam tersibuk pukul 11.00–13.00 |
| **Lokasi** | Jawa Barat dominan >30% total transaksi |
| **Transaksi** | 52% COD, 60% pilih ongkir termurah, median Rp 23.920 |

## Rekomendasi Bisnis
1. **Fokus stok Nampan/Tray** — demand tinggi dan stabil, prioritaskan menjelang Q3–Q4
2. **Investigasi pembatalan** — telusuri penyebab cancellation rate tinggi di Rak Serbaguna dan Celengan
3. **Optimalkan promosi di peak hour** — jalankan flash sale di pukul 11.00–13.00 dan 19.00–20.00
4. **Eksplorasi pasar luar Jawa** — Sumatera dan Sulawesi masih sangat bisa dikembangkan

## Kesimpulan
Analisis ini berhasil mengidentifikasi produk terlaris (Nampan/Tray), puncak revenue (Oktober 2024), serta perilaku transaksi customer Shopee Indonesia seperti dominasi COD dan preferensi ongkir termurah. Meskipun ditemukan tantangan berupa cancellation rate tinggi pada beberapa produk, tren bisnis secara keseluruhan menunjukkan pertumbuhan yang positif. Rekomendasi yang dihasilkan fokus pada optimasi stok, promosi, dan pengembangan pasar untuk mempertahankan momentum pertumbuhan di tahun mendatang.

## Author
**Wahyu Iqsam**
[LinkedIn](https://www.linkedin.com/in/wahyu-iqsam/)
[GitHub](https://github.com/hyusam)