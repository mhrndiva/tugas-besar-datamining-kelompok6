# tugas-besar-datamining-kelompok6

Judul Kasus : Keterlambatan Pengiriman Barang 

Anggota : 
Devi Wulandari (714220054)
Aria Diva Putri Bintang Maharani (714220050)
Serli Pariela (714220023)

Deskripsi Kasus: 
Keterlambatan pengiriman barang menjadi tantangan serius di era pertumbuhan e-commerce, di mana kepuasan pelanggan sangat dipengaruhi oleh ketepatan waktu pengiriman. Berbagai faktor seperti kondisi cuaca, masalah logistik, dan pengelolaan rantai pasok dapat menyebabkan keterlambatan tersebut. Untuk mengatasi hal ini, analisis prediktif menggunakan algoritma Random Forest diterapkan guna mengidentifikasi pola keterlambatan dan faktor-faktor penyebabnya. Dengan pendekatan ini, perusahaan dapat meningkatkan efisiensi operasional dan merumuskan strategi yang lebih efektif untuk mengurangi risiko keterlambatan di masa depan.

Sumber Dataset :
Dataset yang digunakan merupakan gabungan data transaksi dari 2 ecomerce 

Langkah Prepocessing :
1. 🔍 Hapus kolom yang menyebabkan leakage (misalnya tanggal estimasi dan ID pesanan).

2. 🔠 One-Hot Encoding pada kolom kategorikal agar bisa dibaca oleh model.

3. 🧹 Tangani missing value:

Hapus baris dengan target kosong.

Isi nilai kosong lainnya dengan rata-rata.

4. 🎯 Pisahkan fitur (X) dan target (y).

5. 📏 Lakukan scaling pada fitur numerik menggunakan StandardScaler.

Algoritma : Random Forest 

Evalusi & Hasil : 
Model Random Forest mencapai akurasi 80% pada data uji. Model cukup baik dalam memprediksi pengiriman tepat waktu (F1-score 88%), namun masih lemah dalam memprediksi tidak tepat waktu (F1-score 33%) karena jumlah datanya sedikit. Secara keseluruhan, model menunjukkan performa yang cukup baik namun dapat ditingkatkan terutama pada kelas minoritas.

Cara Menjalankan : 
Gunakan Google Colab (Online)
Buka: https://colab.research.google.com
Klik File > Upload notebook
Pilih file .ipynb hasil download → klik tombol ▶️ di setiap sel untuk menjalankan.


