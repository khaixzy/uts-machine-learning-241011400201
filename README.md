# uts-machine-learning-241011400201
Identitas Mahasiswa

Nama: KHAIRA MAULIDYA
NIM: 241011400201
Kelas: 05TPLM001

Deskripsi
Repositori ini berisi pengerjaan Ujian Tengah Semester (UTS) mata kuliah Machine Learning. Pengerjaan meliputi Linear Regression, Logistic Regression, pemahaman konsep, dan perbandingan model manual dengan Scikit-learn.

Hasil Pengerjaan
A. Linear Regression
Model digunakan untuk memprediksi penjualan berdasarkan biaya iklan.
Intercept: 29,8900
Koefisien: 8,9707
Model Linear Regression digunakan untuk memprediksi penjualan berdasarkan biaya iklan.
Evaluasi Data Training:
MAE: 4.1355
MSE: 33.1564
RMSE: 5.7582
R²: 0.9447 (94.47%)

Evaluasi Data Testing:
MAE: 6.1503
MSE: 52.9009
RMSE: 7.2733
R²: 0.9315 (93.15%)
Berdasarkan hasil evaluasi, model memperoleh nilai R² sebesar 93.15% pada data testing. Artinya, model dapat menjelaskan sekitar 93.15% variasi penjualan pada data testing.

B. Logistic Regression
Model digunakan untuk mengklasifikasikan email sebagai spam atau bukan spam berdasarkan jumlah link dan kata promosi.
Intercept (Scikit-learn): -9.74209133125333

C. Pemahaman Konsep
Bagian ini membahas konsep Linear Regression, Logistic Regression, Gradient Descent, evaluasi model, overfitting, dan perbedaan MSE dengan Log Loss.
Bonus: Perbandingan dengan Scikit-learn
Perbandingan dilakukan antara implementasi model manual dan model dari Scikit-learn. Perbedaan koefisien Logistic Regression dapat terjadi karena perbedaan metode optimasi dan penggunaan regularisasi.

Daftar File
tugas_UTS.ipynb — Notebook pengerjaan UTS beserta kode, hasil, dan grafik.
Ads_Data.csv — Dataset untuk Linear Regression.
Email_Data.csv — Dataset untuk Logistic Regression.
README.md — Identitas mahasiswa dan ringkasan hasil pengerjaan.
