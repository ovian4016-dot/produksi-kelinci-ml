
# 🐇 Analisis Faktor-Faktor Produksi Kelinci di Kecamatan Bumiaji, Kota Batu

## 📌 Deskripsi Singkat
Proyek ini bertujuan untuk menganalisis faktor-faktor yang memengaruhi **produksi kelinci** di Kecamatan Bumiaji, Kota Batu, menggunakan pendekatan **regresi linear** dan eksplorasi model lainnya. Proyek ini dikembangkan sepenuhnya menggunakan **Google Colab** dengan keterbatasan perangkat (smartphone Android 7).

## 📂 Dataset
- Jumlah data: **30 observasi**
- Sumber: Data asli dari penelitian skripsi
- Fitur:
  - `Modal`: Dana yang dikeluarkan peternak (dalam ribuan rupiah)
  - `Lahan`: Luas kandang atau lahan ternak (meter persegi)
  - `Keterampilan`: Skor berdasarkan penilaian teknik beternak
  - `Pakan`: Biaya pakan (ribu rupiah)
  - `Produksi`: Jumlah anak kelinci yang dihasilkan

## 🎯 Tujuan Proyek
- Mengetahui fitur mana yang paling berpengaruh terhadap produksi kelinci
- Membangun model regresi yang bisa memprediksi hasil produksi
- Memberikan insight berbasis data untuk meningkatkan produktivitas ternak

## 🧰 Tools & Library
- Python (Google Colab)
- Pandas, NumPy
- Matplotlib & Seaborn
- scikit-learn

## 🔎 Eksperimen yang Dilakukan
- Eksplorasi data awal (EDA)
- Regresi linear baseline
- Eksperimen **StandardScaler**
- Eksperimen model **Decision Tree**
- Penanganan **outlier** dengan metode IQR
- Regresi linear ulang setelah data dibersihkan
- Visualisasi prediksi vs aktual
- Simpan hasil ke `.csv`

## 📊 Hasil Akhir (Model Terbaik)
| Metric | Nilai |
|--------|-------|
| R²     | 0.79  |
| MAE    | 16.12 ekor |
| RMSE   | 18.69 ekor |

📌 **Insight utama**:
- Fitur yang paling berpengaruh: **Keterampilan** dan **Lahan**
- **Modal dan pakan** tidak memiliki pengaruh signifikan

## 📌 Insight Bisnis
Peningkatan produksi kelinci tidak hanya bergantung pada jumlah modal atau pakan, tetapi lebih ditentukan oleh **kemampuan peternak (skill)** dan **pemanfaatan lahan yang optimal**. Pelatihan dan edukasi teknis bagi peternak dapat menjadi solusi nyata.

## 📁 Struktur Proyek
```
├── data_produksi_kelinci.csv       <- Dataset asli
├── Proyek kelinci.ipynb            <- Notebook analisis
├── hasil_prediksi_kelinci.csv      <- Output model
└── README.md                       <- File ini
```

## 🧠 Penutup & Refleksi
Proyek ini merupakan langkah awal saya dalam membangun karier di bidang AI dan data science. Saya mengerjakannya dengan penuh usaha meskipun hanya menggunakan **HP Android tanpa laptop**, memaksimalkan waktu dan alat yang terbatas.

## 📬 Kontak
- 📧 Email: [Ovian4016@gmail.com]
- 🔗 LinkedIn: [linkedin.com/in/username](https://linkedin.com/in/username)
