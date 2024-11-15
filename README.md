# 🎩 Segmentasi dan Klasifikasi Penumpang Titanic

Proyek ini bertujuan untuk melakukan segmentasi dan klasifikasi penumpang Titanic berdasarkan berbagai karakteristik demografis dan informasi perjalanan. Proses ini mencakup penerapan teknik clustering untuk mengelompokkan penumpang ke dalam grup yang bermakna dan menggunakan model klasifikasi untuk memprediksi kelompok tersebut, guna menemukan pola-pola utama dalam data Titanic.

## 📑 Daftar Isi
- [🔍 Ringkasan Proyek](#-ringkasan-proyek)
- [📂 Dataset](#-dataset)
- [📁 Struktur Proyek](#-struktur-proyek)
- [⚙️ Persyaratan](#️-persyaratan)
- [🚀 Langkah-langkah dalam Proyek](#-langkah-langkah-dalam-proyek)
- [📊 Hasil](#-hasil)
- [🔧 Pengembangan Selanjutnya](#-pengembangan-selanjutnya)

## 🔍 Ringkasan Proyek
Proyek ini terdiri dari dua tahap utama:
1. **Clustering**: Menggunakan teknik clustering untuk mengelompokkan penumpang berdasarkan kesamaan karakteristik.
2. **Klasifikasi**: Membangun model klasifikasi untuk memprediksi kelompok penumpang berdasarkan fitur yang tersedia.

## 📂 Dataset
Dataset yang digunakan adalah data penumpang Titanic, yang mencakup informasi seperti:
- Usia
- Jenis Kelamin
- Kelas Tiket
- Jumlah Keluarga yang Menyertai
- Tarif Tiket
- Pelabuhan Keberangkatan

Dataset ini dapat diunduh dari [Kaggle](https://www.kaggle.com/c/titanic) atau sumber terbuka lainnya.

## 📁 Struktur Proyek
├── data/ # Folder yang berisi dataset ├── notebooks/ # Folder yang berisi notebook Jupyter untuk analisis dan pemodelan ├── src/ # Folder yang berisi kode untuk pemrosesan data, clustering, dan klasifikasi └── README.md # Dokumentasi proyek

## ⚙️ Persyaratan
Untuk menjalankan proyek ini, Anda memerlukan beberapa pustaka Python, termasuk:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
