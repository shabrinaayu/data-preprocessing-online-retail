# Data Preprocessing Online Retail

## Deskripsi
Proyek ini merupakan tugas mata kuliah Data Mining yang berfokus pada proses preprocessing dataset Online Retail menggunakan Python di Google Colab.

## Sumber Dataset
Dataset diperoleh dari UCI Machine Learning Repository, yaitu [Online Retail]
Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.

## Tahapan Preprocessing
1. Mengidentifikasi struktur dan ukuran dataset.
2. Memeriksa kualitas data, termasuk missing values dan duplikat.
3. Menghapus baris duplikat.
4. Menangani missing values pada kolom `Description`.
5. Mengubah tipe data `InvoiceDate` menjadi datetime.
6. Memeriksa nilai negatif dan nol pada `Quantity` dan `UnitPrice`.
7. Mengevaluasi transaksi khusus dan mengecualikan transaksi dengan `UnitPrice` negatif dari dataset analisis.
8. Membandingkan kondisi data sebelum dan sesudah preprocessing.

## Tools
- Python
- Google Colab
- Pandas
- UCI Machine Learning Repository

## Hasil
Dataset telah melalui proses pembersihan awal, dengan penghapusan duplikat, penanganan missing values pada `Description`, dan transformasi tipe data tanggal. Missing values pada `CustomerID` serta transaksi khusus yang masih relevan dipertahankan sesuai pertimbangan analisis.

Notebook berisi kode dan hasil setiap tahap preprocessing.
