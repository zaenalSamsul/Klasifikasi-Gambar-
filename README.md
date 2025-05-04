## 🌾 **Proyek Klasifikasi Gambar dengan CNN pada Dataset Rice Image Detection**

## 📝 Deskripsi
Proyek ini merupakan bagian dari **Coding Camp 2025 – DBS Foundation**, yang mengimplementasikan **Convolutional Neural Network (CNN)** untuk mengklasifikasikan gambar padi. Model ini dirancang untuk mengidentifikasi jenis padi secara akurat berdasarkan gambar dengan proses:

- 🖼️ **Pengolahan Dataset Gambar**
- 🧪 **Data Augmentation** (peningkatan variasi data)
- 🧠 **Pembuatan Model CNN (Sequential)**
- 📊 **Visualisasi Akurasi & Loss**
- 🧾 **Evaluasi Model** menggunakan *Confusion Matrix* dan *Classification Report*

## 📊 Hasil Model
- **Training Accuracy**: 99.71%
- **Validation Accuracy**: 99.733%
- **Contoh hasil inference**: Model berhasil memprediksi kelas *Basmati* dengan probabilitas **1.0000**.

## 🧰 Tools yang Digunakan
- Bahasa Pemrograman: **Python**
- Framework: **TensorFlow**, **Keras**

## 📂 Struktur Direktori
- `saved_model/`: Menyimpan model dalam format **TensorFlow SavedModel**.
- `tflite/`: Model dalam format **TensorFlow Lite** – cocok untuk aplikasi mobile dan embedded systems.
- `tfjs_model/`: Model dalam format **TensorFlow.js** – digunakan langsung di browser web.

## 🚀 Cara Menjalankan
1. Buka file `submission-klasifikasi-gambar.ipynb` untuk melihat alur pelatihan, validasi, dan evaluasi model.
2. Gunakan salah satu format model untuk melakukan **inference**:
   - **SavedModel**: Untuk pengujian standar di TensorFlow.
   - **TFLite**: Untuk perangkat mobile.
   - **TFJS**: Untuk aplikasi berbasis web.

. **Clone repositori ini:**
   ```bash
    git clone https://github.com/zaenalSamsul/Klasifikasi-Gambar-Rice-Image-Klasifikasi.git
    cd Klasifikasi-Gambar-Rice-Image-Klasifikasi

    `install dependensi:`
     `pip install -r requirements.txt`
--- 


## Persyaratan
Lihat file `requirements.txt` untuk pustaka yang diperlukan.
