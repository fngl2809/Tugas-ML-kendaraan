# Tugas-ML-kendaraan

**Deskripsi Proyek**
Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan metode machine learning untuk membedakan antara dua jenis kendaraan: mobil dan motor. Dataset yang digunakan terdiri dari total 200 gambar, masing-masing 100 gambar mobil dan 100 gambar motor.

**Dataset**
- jumlah gambar: 200
- kelas:
  -mobil: 100 gambar
  - motor: 100 gambar
- format gambar:  .jpg/.png
- Ukuran gambar telah disesuaikan untuk proses pelatihan.

**Tools dan Library**
Proyek ini dikerjakan menggunakan Google Colab dan memanfaatkan beberapa library populer dalam pengolahan gambar dan machine learning, yaitu:
- Python
- TensorFlow / Keras (untuk membangun model CNN)
- OpenCV / PIL (untuk preprocessing gambar)
- Matplotlib (untuk visualisasi grafik)
- NumPy
- scikit-learn

**Arsitektur Model**
Model yang digunakan adalah Convolutional Neural Network (CNN), yang terdiri dari beberapa lapisan berikut:
- Convolutional layer
- MaxPooling layer
- Flatten layer
- Dense (fully connected) layer
- Output layer dengan aktivasi softmax (untuk klasifikasi 2 kelas)

**Langkah-Langkah Pengerjaan**
- Pengumpulan Data: Mengumpulkan 100 gambar mobil dan 100 gambar motor.
- Preprocessing Data:
  - Resize gambar
  - Normalisasi pixel
  - Labeling data (mobil = 0, motor = 1)
- Pembangunan Model: Menggunakan CNN dengan arsitektur sederhana.
- Pelatihan Model: Data dilatih dengan split data training dan validation.

**Kesimpulan**
Berdasarkan hasil dari pelatihan model klasifikasi gambar antara mobil dan motor, dapat disimpulkan bahwa model Convolutional Neural Network (CNN) yang dibangun mampu mengenali dan membedakan kedua objek tersebut dengan tingkat akurasi yang cukup baik. Model menunjukkan performa stabil selama proses pelatihan dan validasi, ditunjukkan oleh grafik akurasi dan loss yang konsisten serta hasil evaluasi menggunakan confusion matrix.

Penggunaan dataset sebanyak 200 gambar (100 mobil dan 100 motor) menunjukkan bahwa meskipun jumlah data relatif terbatas, model tetap bisa belajar mengenali ciri visual dari masing-masing kelas. Ke depannya, performa model dapat lebih ditingkatkan dengan menambahkan:
- Data latih yang lebih banyak dan beragam
- Teknik augmentasi data (rotasi, zoom, flip)
- Penyesuaian parameter model (tuning)
Proyek ini membuktikan bahwa machine learning, khususnya deep learning dengan CNN, sangat efektif dalam menyelesaikan permasalahan klasifikasi gambar sederhana, dan dapat menjadi dasar yang kuat untuk pengembangan aplikasi computer vision di masa depan.

