#  Diabetes Prediction menggunakan Naive Bayes and Decision Tree

##  Nama Mahasiswa

**Nama:** Abdullah Ahmad Izzah  
**NIM:** (103132430024)  
**Mata Kuliah:** Machine Learning

---

#  Deskripsi Permasalahan

Diabetes merupakan salah satu penyakit kronis yang dapat menyebabkan berbagai komplikasi apabila tidak terdeteksi sejak dini. Oleh karena itu, diperlukan suatu sistem yang mampu membantu memprediksi apakah seseorang berpotensi menderita diabetes berdasarkan data kesehatan yang dimiliki.

Pada proyek ini dibangun model klasifikasi menggunakan algoritma **Naive Bayes** dan **Decision Tree** untuk memprediksi status diabetes seseorang. Kedua algoritma kemudian dibandingkan berdasarkan hasil evaluasi sehingga dapat diketahui algoritma yang memiliki performa terbaik.

---

#  Dataset

Dataset yang digunakan adalah **Diabetes Prediction Dataset**.

Dataset terdiri dari **100.000 data pasien** dengan **9 atribut**, yaitu:

| No | Atribut | Deskripsi |
|----|----------|----------------------------|
| 1 | gender | Jenis kelamin |
| 2 | age | Usia |
| 3 | hypertension | Riwayat hipertensi |
| 4 | heart_disease | Riwayat penyakit jantung |
| 5 | smoking_history | Riwayat merokok |
| 6 | bmi | Body Mass Index |
| 7 | HbA1c_level | Kadar HbA1c |
| 8 | blood_glucose_level | Kadar glukosa darah |
| 9 | diabetes | Target (0 = Tidak Diabetes, 1 = Diabetes) |

---

# Tahapan Preprocessing

Tahapan preprocessing yang dilakukan pada penelitian ini adalah:

- Mengecek missing value
- Mengecek data duplikat
- Melakukan One-Hot Encoding pada atribut kategorikal (`gender` dan `smoking_history`)
- Memisahkan fitur (X) dan target (y)
- Membagi dataset menjadi data training (80%) dan testing (20%)

---

# Metode yang Digunakan

Penelitian ini menggunakan dua algoritma Machine Learning, yaitu:

## 1. Naive Bayes

Naive Bayes merupakan algoritma klasifikasi berbasis probabilitas yang menggunakan Teorema Bayes dengan asumsi bahwa setiap fitur saling independen.

## 2. Decision Tree

Decision Tree merupakan algoritma klasifikasi yang bekerja dengan membentuk pohon keputusan berdasarkan atribut yang paling informatif.

---


#  Cara Menjalankan Program

1. Clone repository ini.

```bash
git clone https://github.com/username/Diabetes-Prediction-ML.git
```

2. Install library yang dibutuhkan.

```bash
pip install -r requirements.txt
```

3. Buka file notebook:

```
Diabetes_Prediction.ipynb
```

4. Jalankan seluruh cell secara berurutan.

---

#  Hasil Eksperimen

Model yang dibandingkan:

- Naive Bayes
- Decision Tree

Evaluasi dilakukan menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

## Hasil Accuracy

| Model | Accuracy |
|---------|----------|
| Naive Bayes | (0.861622) |
| Decision Tree | (0.970567) |

---

#  Kesimpulan

Berdasarkan hasil eksperimen, kedua algoritma mampu melakukan klasifikasi terhadap data diabetes dengan baik.

Performa masing-masing model dievaluasi menggunakan Accuracy, Precision, Recall, F1-Score, Confusion Matrix, dan ROC-AUC. Model dengan nilai evaluasi terbaik dapat dipilih sebagai model yang paling sesuai untuk kasus prediksi diabetes pada dataset yang digunakan.

---

# Author

Abdullah Ahmad Izzah
