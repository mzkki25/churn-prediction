## Churn prediction menggunakan algoritma decission tree, random forest, dan logistic regression

Churn Prediction adalah proses memprediksi apakah seorang pelanggan akan berhenti menggunakan produk atau layanan perusahaan dalam waktu dekat. Pada umumnya, churn prediction dilakukan dengan menggunakan machine learning atau data mining untuk menganalisis data pelanggan dan memprediksi pelanggan mana yang berpotensi untuk churn.

Di antara beberapa algoritma machine learning yang dapat digunakan untuk churn prediction, berikut adalah penjelasan singkat mengenai tiga algoritma yang umum digunakan: Decision Tree, Random Forest, dan Logistic Regression.

1. Decision Tree
- Decision Tree adalah sebuah model prediksi yang memetakan data input ke dalam output dengan membuat keputusan-keputusan yang berurutan pada sebuah struktur pohon (tree). Dalam churn prediction, decision tree digunakan untuk memprediksi apakah pelanggan akan churn berdasarkan beberapa faktor seperti usia, jenis kelamin, riwayat pembelian, atau aktivitas penggunaan produk. Decision tree akan membagi data ke dalam sub-kelompok yang semakin kecil dan membuat keputusan berdasarkan setiap sub-kelompok.
- Kelebihan dari decision tree adalah mudah untuk diinterpretasikan dan dijelaskan, serta dapat menghasilkan hasil yang cepat dan akurat. Namun, kelemahannya adalah decision tree bisa overfitting jika terlalu kompleks atau jika terdapat noise di dalam data.

2. Random Forest
- Random Forest adalah kumpulan dari beberapa decision tree yang bekerja bersama-sama untuk menghasilkan prediksi yang lebih akurat. Setiap decision tree di dalam random forest akan memprediksi churn berdasarkan sub-kelompok data yang berbeda. Kemudian, hasil dari semua decision tree akan digabungkan dan dihitung rata-rata untuk menghasilkan hasil akhir.
- Kelebihan dari Random Forest adalah mampu menghasilkan hasil prediksi yang lebih akurat daripada Decision Tree, dan lebih resisten terhadap overfitting. Kelemahannya adalah model yang dihasilkan tidak dapat dijelaskan dengan mudah.

3. Logistic Regression
- Logistic Regression adalah sebuah model statistik yang digunakan untuk memprediksi probabilitas dari suatu kejadian (yaitu churn pada kasus ini) berdasarkan beberapa variabel input. Dalam churn prediction, logistic regression digunakan untuk memprediksi probabilitas pelanggan churn berdasarkan faktor-faktor seperti usia, jenis kelamin, riwayat pembelian, atau aktivitas penggunaan produk.
- Kelebihan dari Logistic Regression adalah mudah diinterpretasikan, dan dapat menghasilkan hasil yang cepat dan akurat. Kelemahannya adalah tidak dapat menangani interaksi atau relasi non-linear antara variabel input.
