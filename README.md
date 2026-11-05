# ISC Machine Learning

Project analisis data dan pemodelan Machine Learning untuk transaksi e-commerce.

## Daftar File
- `dataset.csv`: Dataset transaksi e-commerce (5.884 baris × 19 kolom).
- `Analisis_Feature_Target_ISC.xlsx`: File spreadsheet hasil agregasi fitur terhadap target:
  - `Full_Dataset`: Data mentah lengkap.
  - `Analisis_Payment_Method`: Rasio validasi dan pendapatan per metode pembayaran.
  - `Analisis_Category`: Rasio validasi dan performa per kategori produk.
  - `Analisis_Qty_Ordered`: Distribusi kuantitas pesanan terhadap target.
  - `Analisis_Price_Segment`: Segmentasi harga per kuantil terhadap target.
  - `Analisis_Discount`: Pengaruh diskon terhadap validasi pesanan.
  - `Korelasi_Target`: Matriks korelasi linear fitur terhadap target `is_valid` dan `is_net`.
- `ISC_Machine_Learning_Analysis.ipynb`: Notebook analisis eksploratif, visualisasi heatmap matriks korelasi dan per-fitur terhadap target, serta baseline model klasifikasi (Random Forest).
- `requirements.txt`: Daftar library Python pendukung.

## Instalasi
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
