🧠 Stroke Risk Prediction — SDG 3: Good Health and Well-being
📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun model machine learning yang mampu memprediksi risiko penyakit stroke berdasarkan berbagai indikator kesehatan dan gaya hidup. Proyek ini dikembangkan sebagai bagian dari Staff Development — Data Upskilling Program di Enterprise Data Management (EDM) Laboratory, Telkom University.

🌿 Relevansi SDG
Proyek ini mendukung Sustainable Development Goal (SDG) 3: Good Health and Well-being, khususnya pada target:

Target 3.4: Mengurangi sepertiga kematian prematur akibat penyakit tidak menular melalui pencegahan dan pengobatan.

Pemanfaatan Teknologi: Menggunakan deteksi dini berbasis data untuk memperkuat sistem peringatan kesehatan masyarakat.

📊 Dataset
Dataset yang digunakan adalah Stroke Prediction Dataset yang mencakup fitur-fitur berikut:

Indikator Medis: Hipertensi, penyakit jantung, rata-rata kadar glukosa, dan BMI.

Data Demografis: Usia, jenis kelamin, status pernikahan, tipe pekerjaan, dan tipe tempat tinggal.

Target: Status kejadian stroke (0 untuk Tidak, 1 untuk Ya).

🛠️ Tahapan Pengerjaan
Mengikuti kurikulum pelatihan EDM Lab, proyek ini dibagi menjadi beberapa modul utama:

1. Exploratory Data Analysis (Modul 1)
Mengidentifikasi dan menangani 201 missing values pada kolom bmi menggunakan pengisian nilai median.

Melakukan visualisasi distribusi data untuk memahami hubungan antara usia dan risiko stroke.

2. Machine Learning Modelling (Modul 2)
Preprocessing: Melakukan Label Encoding pada data kategorikal dan pembagian data (train-test split) sebesar 80:20.

Algoritma: Menggunakan Random Forest Classifier untuk melatih model prediksi.

📈 Hasil Evaluasi
Berdasarkan pengujian pada data uji, model berhasil mencapai performa sebagai berikut:

Accuracy: 93.93%.

Insights: Faktor usia dan kondisi medis seperti hipertensi menjadi variabel yang paling berpengaruh dalam prediksi risiko stroke.

🚀 Cara Menjalankan
Clone repositori ini.

Unggah file healthcare-dataset-stroke-data.csv ke lingkungan kerja Anda.

Jalankan file FINAL PROJECT FIX.ipynb di Google Colab atau Jupyter Notebook.

👤 Penulis
Darvesh Gladwin Musyaffa

Staff at Enterprise Data Management (EDM) Laboratory.

Student at Telkom University, Information Systems Major.
