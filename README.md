# Sentimen-Analisis-Gojek

Metodologi

Proses analisis dalam proyek ini dibagi menjadi beberapa tahapan utama:
-Text Preprocessing (Pra-pemrosesan Teks)
-Case Folding: Mengubah seluruh teks menjadi huruf kecil.
-Tokenizing: Memecah kalimat menjadi kata-kata (token).
-Stopword Removal: Menghapus kata-kata umum yang tidak memiliki makna signifikan (misalnya, "yang", "di", "dan").
-Stemming: Mengubah kata-kata ke bentuk dasarnya menggunakan library Sastrawi untuk Bahasa Indonesia.

Ekstraksi Fitur
Menggunakan metode TF-IDF (Term Frequency-Inverse Document Frequency) untuk mengubah data teks menjadi representasi numerik yang dapat diproses oleh model machine learning.

Pemodelan
Membangun model klasifikasi sentimen menggunakan algoritma Random Forest Classifier. Model ini dilatih menggunakan data yang telah diproses untuk dapat memprediksi sentimen dari teks ulasan baru.

Evaluasi Model
Kinerja model dievaluasi menggunakan metrik seperti Accuracy, Precision, Recall, dan F1-Score yang disajikan dalam bentuk Classification Report.

Hasil Analisis
Berdasarkan analisis yang dilakukan, model Random Forest berhasil mencapai akurasi sebesar 93% dalam mengklasifikasikan sentimen. Temuan utama menunjukkan bahwa sebagian besar ulasan pengguna bernada netral 49.3%, disusul dengan positif 31.4% kemudian negatif 19.3%. Detail lengkap mengenai hasil dan pembahasan dapat ditemukan dalam draf jurnal yang tersedia di repositori ini.

Isi Repositori
analisis_sentimen_gojek_random_forest.ipynb: File Jupyter Notebook yang berisi seluruh kode untuk pra-pemrosesan data, pemodelan, hingga evaluasi.
draft jurnal analisis.[pdf]: Dokumen draf jurnal ilmiah yang menjelaskan penelitian ini secara mendalam, mulai dari latar belakang, metode, hasil, hingga kesimpulan.
