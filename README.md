Belajar Machine Learning untuk Pemula - Dicoding
Submisi Akhir Kelas Dicoding "Belajar Machine Learning untuk Pemula"

Deskripsi Proyek
Repositori ini berisi submisi akhir untuk kelas "Belajar Machine Learning untuk Pemula" (BMLP) yang diselenggarakan oleh Dicoding Indonesia. Proyek ini bertujuan untuk mendemonstrasikan pemahaman dan kemampuan dalam mengimplementasikan dua tugas fundamental dalam Machine Learning:

Klasifikasi (Classification): Membangun dan mengevaluasi model untuk memprediksi kategori/kelas data.
Clustering (Pengelompokan): Menganalisis dan mengelompokkan data tanpa label (unsupervised) untuk menemukan pola tersembunyi.

Struktur Repositori
Repositori ini terdiri dari file-file yang merupakan hasil pengerjaan dari lingkungan Google Colab:
File / Folder,Deskripsi
[klasifikasi]_submission_akhir_bmlp_fauzan_suryahadi.py,"Implementasi tugas Klasifikasi. File ini mencakup proses data preprocessing, pembangunan model, Hyperparameter Tuning, dan evaluasi model."
[clustering]_submission_akhir_bmlp_fauzan_suryahadi.py,"Implementasi tugas Clustering. File ini berisi langkah-langkah preprocessing, penentuan jumlah cluster optimal, pembentukan cluster, dan interpretasi karakteristik dari setiap cluster."
explore_RandomForest_classification.h5,File model Machine Learning yang telah dilatih (Random Forest Classifier) untuk tugas klasifikasi. (Akan dihasilkan setelah menjalankan script Klasifikasi)
data_clustering_inverse.csv,Dataset hasil Clustering setelah proses inverse transformasi. (Akan dihasilkan setelah menjalankan script Clustering)

Teknologi dan Library
Proyek ini dikembangkan menggunakan bahasa pemrograman Python dan mengandalkan library-library utama untuk analisis data dan Machine Learning:
Python 3.x
Pandas & NumPy: Untuk manipulasi dan analisis data.
Scikit-learn (sklearn): Untuk implementasi model Klasifikasi (RandomForestClassifier, GridSearchCV) dan Clustering.
Joblib: Untuk menyimpan model Klasifikasi.
Matplotlib & Seaborn: (Asumsi) Untuk visualisasi data dan hasil.

Ringkasan Hasil Utama
1. Proyek Klasifikasi
Model Utama: Random Forest Classifier.
Metode Peningkatan: Penerapan Hyperparameter Tuning menggunakan GridSearchCV untuk mengoptimalkan parameter model, seperti n_estimators, max_depth, dan min_samples_split.
Evaluasi: Model dievaluasi berdasarkan metrik Akurasi (accuracy), dan hasil performa disajikan melalui classification_report.
2. Proyek Clustering (Analisis Perilaku Nasabah)
Berdasarkan analisis data perilaku transaksi nasabah, proses Clustering berhasil mengidentifikasi dua kelompok nasabah utama (Cluster 0 dan Cluster 1):
Cluster,Karakteristik Utama,Deskripsi
Cluster 0,Aktif & Digital,"Kelompok nasabah dengan usia rata-rata termuda (Pelajar). Menunjukkan frekuensi transaksi rata-rata tertinggi dan durasi transaksi terpendek, mengindikasikan tingkat aktivitas yang sangat tinggi dan ketergantungan pada layanan digital/cepat."
Cluster 1,Konservatif & Aset Tinggi,"Kelompok nasabah dengan usia rata-rata lebih tua (Dokter). Memiliki saldo akun rata-rata tertinggi, menunjukkan stabilitas finansial yang kuat dan kecenderungan untuk menyimpan aset."

Cara Menjalankan Proyek
1. Clone Repositori:
git clone https://github.com/fs23yayan/BelajarMachineLearningUntukPemula-Dicoding.git
cd BelajarMachineLearningUntukPemula-Dicoding
2. Lingkungan: Disarankan untuk menggunakan lingkungan pengembangan yang mendukung Jupyter Notebook atau Google Colab (sesuai format asli file).
3. Instalasi Dependencies: Pastikan Anda telah menginstal semua library yang diperlukan.
4. Eksekusi: Buka file .py di lingkungan Notebook Anda dan jalankan semua sel kode secara berurutan untuk mereplikasi seluruh proses preprocessing, pelatihan model, dan analisis hasil.
