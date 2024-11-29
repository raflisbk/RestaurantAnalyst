# **Analisis Data Restoran dengan KMeans Clusterisasi dan Klasifikasi Menggunakan Random Forest dan Logistic Regression**

Repositori ini berisi proyek analisis data restoran yang diambil dari dataset **Swiggy** yang tersedia di Kaggle. Proyek ini menggunakan **algoritma KMeans** untuk melakukan **clusterisasi** restoran berdasarkan beberapa fitur, kemudian menggunakan **PCA (Principal Component Analysis)** untuk **feature selection** sebelum melanjutkan ke tahap **klasifikasi** dengan **Random Forest** dan **Logistic Regression** untuk memprediksi kategori restoran berdasarkan cluster yang terbentuk.

---

## **Fitur Utama**
- **Preprocessing Data:**
  - Pembersihan data yang melibatkan penanganan nilai hilang, pengolahan tipe data, dan normalisasi fitur.
  - Menyiapkan data untuk analisis clusterisasi dan klasifikasi.
- **Clusterisasi dengan KMeans:**
  - Menggunakan **KMeans** untuk mengelompokkan restoran berdasarkan fitur-fitur yang relevan.
  - Menggunakan **PCA** untuk seleksi fitur dan reduksi dimensi sebelum clusterisasi.
- **Klasifikasi dengan Random Forest dan Logistic Regression:**
  - Menggunakan **Random Forest** dan **Logistic Regression** untuk mengklasifikasikan restoran berdasarkan cluster yang dihasilkan oleh KMeans.
  - Evaluasi model dengan metrik seperti **accuracy**, **precision**, **recall**, dan **F1-score**.

---

## **Sumber Dataset**
Dataset yang digunakan dalam proyek ini berasal dari [Swiggy Restaurant Dataset](https://www.kaggle.com/datasets/abhijitdahatonde/swiggy-restuarant-dataset) yang diunggah oleh pengguna **abhijitdahatonde** di platform Kaggle. Dataset ini berisi informasi terkait restoran yang terdaftar di platform Swiggy, termasuk kategori restoran, harga, rating, dan waktu pengiriman.

---
