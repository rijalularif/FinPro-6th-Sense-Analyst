### Summary Insights Stage 1

Insights yang diberikan dari analisis univariat, bivariat, dan multivariat memberikan gambaran yang mendalam tentang faktor-faktor yang memengaruhi pembelian asuransi perjalanan. Pertama-tama, dari segi numerik, ditemukan bahwa fitur AnnualIncome, FamilyMembers, dan Age memiliki distribusi yang cukup normal, sehingga outlier tidak perlu menjadi kekhawatiran utama. Namun, perlu diperhatikan bahwa distribusi variabel TravelInsurance menunjukkan bahwa hanya sedikit konsumen yang membeli paket asuransi perjalanan dalam dataset ini, sehingga perlu dilakukan proses oversampling atau undersampling untuk membuat proses pemodelan lebih representatif.

Analisis kategori menunjukkan bahwa mayoritas pelanggan bekerja di sektor swasta dan merupakan lulusan perguruan tinggi, yang sesuai dengan harapan. Selain itu, mayoritas pelanggan tidak sering melakukan pembelian tiket pesawat terbang dan tidak pernah melakukan perjalanan ke luar negeri sebelumnya.

Analisis multivariat menyoroti bahwa fitur-fitur seperti EverTravelledAbroad, FrequentFlyer, dan FamilyMembers memiliki pengaruh signifikan terhadap pembelian asuransi perjalanan. Namun, fitur-fitur ini juga menunjukkan masalah multicollinearity, terutama dengan fitur-fitur Age, Employment Type, dan AnnualIncome. Oleh karena itu, sebaiknya pertimbangkan untuk tidak menggunakan fitur-fitur yang memiliki masalah multicollinearity dalam tahap selanjutnya dari proyek ini.

Dari semua insights yang diberikan, beberapa rekomendasi bisnis dapat diambil. Pertama, perusahaan dapat memfokuskan upaya pemasaran pada kelompok pelanggan yang lebih mungkin untuk membeli asuransi perjalanan, seperti mereka yang bekerja di sektor swasta, lulusan perguruan tinggi, atau yang memiliki riwayat perjalanan yang lebih sering. Strategi pemasaran tambahan juga dapat diterapkan untuk menarik perhatian kelompok pelanggan yang cenderung memiliki rasio pembelian yang lebih rendah, seperti pelanggan yang bekerja di sektor pemerintah atau yang belum pernah melakukan perjalanan ke luar negeri.

Selain itu, pengembangan paket asuransi keluarga dan program keanggotaan khusus untuk pelanggan yang sering terbang dan yang memiliki jumlah anggota keluarga yang lebih besar dapat menjadi langkah strategis untuk meningkatkan penjualan asuransi perjalanan. Terakhir, dengan mempertimbangkan pola pembelian berdasarkan usia, perusahaan dapat merancang strategi pemasaran khusus untuk menarik kelompok usia yang memiliki proporsi pembelian yang lebih tinggi, seperti usia 25-26 tahun dan 33-35 tahun.

Secara keseluruhan, dengan memperhatikan insights dan rekomendasi di atas, perusahaan dapat mengoptimalkan strategi pemasaran dan penjualan mereka untuk meningkatkan penjualan asuransi perjalanan dan meningkatkan kepuasan pelanggan.

### Summary Insights Stage 2

Hasil analisis tahap kedua mencakup proses pembersihan data, transformasi fitur, encoding, penanganan ketidakseimbangan kelas, rekayasa fitur, dan identifikasi fitur tambahan. Pemeriksaan data tidak menunjukkan kekosongan atau duplikasi. Fitur Age dan FamilyMembers telah dinormalisasi melalui transformasi log, sedangkan fitur-fitur lainnya telah diubah secara manual atau menggunakan metode seperti One Hot Encoding. 

Perlakuan khusus diberikan pada Annual Income dengan dua skenario transformasi yang akan dievaluasi berdasarkan kinerja model. Oversampling dilakukan untuk menyeimbangkan kelas minoritas dalam target variabel. Proses rekayasa fitur dan penghapusan fitur redundan dilakukan dengan cermat untuk meminimalkan overfitting. 

Selain itu, identifikasi empat fitur tambahan yang berpotensi meningkatkan pemahaman tentang preferensi dan risiko pelanggan dilakukan untuk menambah informasi yang relevan dalam model asuransi perjalanan.
