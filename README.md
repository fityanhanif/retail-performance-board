#  Retail Performance Analytics Board

## 📌 Deskripsi Proyek
Proyek ini adalah dasbor analitik interaktif berbasis web yang dirancang untuk memonitor dan menganalisis performa penjualan ritel produk FMCG (Fast-Moving Consumer Goods). Dasbor ini memberikan wawasan langsung kepada level eksekutif mengenai metrik utama seperti *Revenue*, *Profit Margin*, tren transaksi, dan performa produk.

** Live Demo:** [Klik di sini untuk melihat Dashboard]([https://link-vercel-anda-di-sini.vercel.app](https://retail-performanc.vercel.app/))

##  Objektif Bisnis
* **Evaluasi Performa:** Mengidentifikasi gap antara *Gross Revenue* dan *Net Profit* dari waktu ke waktu.
* **Product Insights:** Menentukan produk dan kategori dengan perputaran tercepat (*fastest-moving*) berdasarkan volume unit yang terjual.
* **Transaction Behavior:** Menganalisis preferensi metode pembayaran pelanggan (Cash vs Card).

##  Tech Stack & Tools
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **UI/UX:** Bootstrap 5 Grid System, Custom CSS (Luxury Dark Mode - Crimson & Peach Gradient).
* **Data Visualization:** Plotly.js (Interactive Charts, Hover Tooltips).
* **Data Processing:** PapaParse (Client-side CSV Parsing & Filtering).
* **Deployment:** Vercel CI/CD.

##  Fitur Utama
1. **Dynamic Metrics Calculation:** Perhitungan otomatis untuk Total Revenue, Profit, Transaksi, dan Unit Terjual dari data mentah CSV.
2. **Interactive Filtering:** Pengguna dapat menyaring seluruh visualisasi data berdasarkan kategori produk dan lokasi provinsi.
3. **Executive Tooltips:** Keterangan detail (*hover tooltips*) yang dilengkapi format angka ringkas (Miliar & Juta) untuk kemudahan pembacaan cepat.

## 📂 Struktur Data
Data yang digunakan merupakan rekaman transaksi ritel dari Januari 2023 hingga Desember 2024, yang telah melalui proses *data cleansing* (pembersihan nilai kosong dan standardisasi format) sebelum divisualisasikan.
