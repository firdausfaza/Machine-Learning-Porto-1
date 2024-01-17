# Prediksi Harga Rumah Kalifornia
**Latar Belakang:**
Pada tahun 1990, sensus di California menyediakan data kaya tentang karakteristik rumah-rumah di berbagai distrik. Informasi ini menjadi sangat berharga untuk memahami faktor-faktor yang memengaruhi harga rumah di wilayah tersebut. Dengan kemajuan teknologi dan metode analisis data, kita dapat menggunakan data tersebut untuk membangun model prediksi harga rumah, yang dapat memberikan wawasan berharga bagi pembeli, penjual, dan pemangku kepentingan lainnya di pasar perumahan California.

**Tujuan:**
Tujuan proyek ini adalah memprediksi harga rumah di California berdasarkan berbagai fitur yang diberikan. Dengan melakukan hal ini, kita dapat memberikan estimasi harga yang akurat kepada individu atau pihak yang berkepentingan dalam transaksi properti di California.

# 1. Business Problem Understanding

Masalah bisnis yang ingin kita selesaikan adalah menciptakan model prediksi harga rumah yang akurat. Dengan demikian, kita dapat memberikan panduan harga yang baik bagi mereka yang terlibat dalam transaksi properti di California. Hal ini akan membantu pembeli dan penjual membuat keputusan yang lebih informasional dan meminimalkan ketidakpastian yang terkait dengan nilai properti.
# 2. Data Understanding

## 2.1 Metadata

1. **longitude:** Koordinat geografis bujur rumah.
2. **latitude:** Koordinat geografis lintang rumah.
3. **housing_median_age:** Umur median rumah di distrik tertentu.
4. **total_rooms:** Jumlah total kamar di rumah-rumah distrik.
5. **total_bedrooms:** Jumlah total kamar tidur di rumah-rumah distrik.
6. **population:** Jumlah populasi di distrik tersebut.
7. **households:** Jumlah rumah tangga di distrik tersebut.
8. **median_income:** Pendapatan median rumah tangga di distrik tersebut.
9. **ocean_proximity:** Kedekatan rumah dengan lautan (variabel kategorikal).
10. **median_house_value:** Nilai median rumah di distrik tersebut (variabel target).

**Singkatnya:**
Data ini berisi informasi geografis dan statistik sensus tahun 1990 untuk rumah-rumah di distrik California. Fitur-fiturnya melibatkan lokasi, umur median rumah, jumlah kamar, populasi, pendapatan median, dan kedekatan dengan lautan, dengan tujuan memprediksi nilai median rumah di distrik tersebut.


# Conclusion

Kesimpulan Proyek Prediksi Harga Rumah di California:

Proyek ini bertujuan untuk memprediksi harga rumah di California berdasarkan data sensus tahun 1990. Sejumlah model regresi dan ensambel model, termasuk Linear Regression, Lasso, Ridge, ElasticNet, KNN, Decision Tree, Random Forest, XGBoost, AdaBoost, CatBoost, dan SVM, telah diuji untuk melihat kinerjanya dalam memprediksi harga rumah.

Dari hasil evaluasi, XGBoost dan CatBoost menunjukkan kinerja yang baik dengan nilai RMSE yang lebih rendah, menandakan ketepatan prediksi yang tinggi. Kemudian, melalui proses Hyperparameter Tuning, model XGBoost berhasil dioptimalkan menjadi model terbaik dengan nilai eror yang lebih rendah dibandingkan model awal.

Kesimpulan:

1. **Pemilihan Model:**
   - Model CatBoost dan XGBoost memiliki kinerja yang paling baik dalam memprediksi harga rumah.
   - Setelah Hyperparameter Tuning, XGBOOST menjadi model terbaik dengan nilai eror yang lebih rendah.

2. **Kesimpulan Bisnis:**
   - Model prediksi harga rumah yang akurat dapat memberikan panduan harga yang baik bagi pembeli, penjual, dan pemangku kepentingan lainnya di pasar perumahan California.
   - Menyediakan estimasi harga yang akurat dapat membantu mengurangi ketidakpastian dalam transaksi properti.

Rekomendasi Lebih Lanjut untuk Pengembangan Proyek Prediksi Harga Rumah di California:

Rekomendasi untuk Pengembangan Selanjutnya:

1. **Analisis Faktor Pengaruh:**
   - Melakukan analisis lebih lanjut terhadap faktor-faktor yang paling berpengaruh dalam menentukan harga rumah. Dalam hal ini, penelitian dapat difokuskan pada identifikasi dan pemahaman lebih mendalam terhadap variabel-variabel yang memiliki dampak signifikan terhadap harga properti, seperti lokasi, ukuran rumah, dan fasilitas di sekitar.

2. **Pembaruan Data:**
   - Melibatkan data yang lebih baru dan relevan untuk meningkatkan keakuratan prediksi. Mengupdate dataset dengan data terkini akan membantu model untuk tetap relevan dengan kondisi pasar properti yang selalu berubah.

3. **Peningkatan Kualitas Data:**
   - Melakukan pembersihan data yang lebih mendalam untuk mengidentifikasi dan menangani outlier, serta mengatasi nilai-nilai yang hilang dengan metode yang lebih canggih. Hal ini akan membantu memastikan kebersihan dan integritas data, yang sangat penting untuk hasil prediksi yang akurat.

4. **Analisis Korelasi:**
   - Melakukan analisis korelasi lebih mendalam untuk memahami hubungan antara variabel-variabel yang ada. Hal ini dapat membantu dalam mengidentifikasi pola-pola kompleks dan memahami bagaimana variabel-variabel saling berinteraksi.

5. **Feature Engineering:**
   - Mengeksplorasi opsi feature engineering tambahan, seperti pembuatan fitur baru atau transformasi fitur yang dapat meningkatkan kemampuan model dalam menangkap pola kompleks dalam data. Pemilihan fitur yang cerdas dapat meningkatkan keakuratan dan interpretabilitas model.

Dengan mengambil langkah-langkah ini, proyek prediksi harga rumah di California dapat terus diperbaiki untuk memberikan hasil prediksi yang lebih akurat dan relevan dengan keadaan terkini di pasar properti.
