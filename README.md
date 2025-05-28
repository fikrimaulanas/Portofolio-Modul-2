# **Analisa Customer Bank Churn menggunakan metode LRFM**

## 📚 Background
*Proyek ini melakukan analisis perilaku pelanggan menggunakan metode LRFM (Length, Recency, Frequency, Monetary) pada dataset BankChurners. Langkah-langkah utama meliputi pembersihan data (cek missing values, duplikasi, dan deteksi outlier dengan IQR), perhitungan skor kuintil untuk masing‑masing dimensi LRFM, serta penyusunan profil pelanggan (LRFM_Profile). Kemudian, kami menyederhanakan segmentasi menjadi empat kategori strategis—Loyal, Potential, New, dan At Risk—berdasarkan kombinasi skor LRFM. Hasil segmentasi divisualisasikan melalui boxplot, bar chart, dan ringkasan metrik rata‑rata untuk setiap segmen. Akhirnya, data terstruktur dan siap di‑export ke BigQuery, serta dihubungkan ke Looker Studio untuk membangun dashboard interaktif yang menampilkan insight utama dan rekomendasi taktis untuk strategi retensi dan akuisisi pelanggan.*

## 🎯 Objectives

Analisis ini bertujuan untuk menggali wawasan strategis dari data CRM yang tersedia melalui beberapa tahapan utama, yaitu:

- **1. Melakukan eksplorasi dan pembersihan data**  
  Membersihkan dataset dari missing values, duplikasi, serta memastikan konsistensi tipe data, sehingga data siap untuk analisis lebih lanjut.

- **2. Menerapkan analisis LRFM (Length, Recency, Frequency, Monetary)**  
  Menghitung skor individual untuk masing-masing dimensi LRFM dengan tujuan memahami tingkat loyalitas, keterlibatan, dan nilai ekonomi masing-masing pelanggan.

- **3. Melakukan segmentasi pelanggan berbasis LRFM score**  
  Membagi pelanggan ke dalam kategori seperti:
  - **Loyal Customers** (pelanggan setia dengan nilai tinggi),
  - **At Risk Customers** (pelanggan yang berpotensi churn),
  - **Potential Loyalists** (pelanggan baru yang menunjukkan potensi loyalitas),
  - **New Customers** (pelanggan baru yang memerlukan nurturing lebih lanjut).

- **4. Menghasilkan visualisasi data yang informatif**  
  Membuat grafik dan plot untuk memperjelas pola-pola penting dalam perilaku pelanggan, sehingga insight dapat dikomunikasikan secara visual kepada stakeholders.

- **5. Menyusun data untuk kebutuhan dashboarding**  
  Menyiapkan dataset terstruktur yang siap diintegrasikan ke dalam tools visualisasi seperti Tableau atau Looker Studio, untuk mendukung pengambilan keputusan berbasis data di tingkat manajerial.

Secara keseluruhan, analisis ini tidak hanya berfokus pada deskripsi data, tetapi juga pada penerjemahan data menjadi strategi nyata yang dapat membantu perusahaan meningkatkan engagement pelanggan, mengurangi churn, dan memaksimalkan nilai pelanggan sepanjang siklus hidup mereka.
