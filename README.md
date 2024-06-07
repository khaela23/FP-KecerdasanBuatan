# Dokumentasi Proyek CNN untuk Klasifikasi Ikan

## Pendahuluan

Proyek ini bertujuan untuk mengembangkan model Convolutional Neural Network (CNN) untuk klasifikasi gambar ikan berdasarkan jenisnya. Model ini menggunakan dataset gambar ikan yang telah dikategorikan.

## Deskripsi Proyek

### Tujuan

- Mengembangkan model CNN untuk menganalisis gambar ikan.
- Mengklasifikasikan gambar ikan menjadi jenis-jenis yang relevan berdasarkan karakteristik visual.

### Metodologi

1. **Pengumpulan Data**: Menggunakan dataset gambar ikan dari berbagai sumber.
2. **Praproses Data**: Augmentasi dan normalisasi gambar.
3. **Desain Model**: Membuat arsitektur CNN.
4. **Pelatihan Model**: Melatih model dengan dataset yang sudah disiapkan.
5. **Evaluasi**: Mengukur kinerja model menggunakan metrik akurasi dan loss.

## Struktur Notebook

### 1. Import Library

Mengimpor library seperti `TensorFlow`, `Keras`, `NumPy`, `Pandas`, dan `Matplotlib`.

### 2. Pengaturan Dataset

Mengunduh dan menyiapkan dataset. Termasuk augmentasi gambar dan normalisasi.

### 3. Pembangunan Model

Membangun model CNN dengan lapisan convolutional, pooling, dan fully connected.

### 4. Pelatihan Model

Melatih model menggunakan dataset, memonitor akurasi, dan menghindari overfitting.

### 5. Evaluasi dan Hasil

Menggunakan data pengujian untuk mengevaluasi model. Menampilkan grafik akurasi dan loss, serta confusion matrix.

### 6. Prediksi

Menggunakan model yang telah dilatih untuk memprediksi jenis ikan dari gambar baru.

## Kesimpulan

Model CNN ini menunjukkan kinerja yang baik dalam klasifikasi gambar ikan. Ini membuktikan efektivitas CNN dalam tugas klasifikasi gambar berbasis visual.
