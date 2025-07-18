# CapstoneProject2

Pada projek kedua ini, sebagai data analis, saya diminta untuk menganalisis mengenai pola penumpang Transjakarta. 

### Perusahaan Transjakarta
Transjakarta adalah sistem transportasi Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Selatan dengan jalur lintasan terpanjang di dunia (208 km).sistem transportasi Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Selatan dengan jalur lintasan terpanjang di dunia (208 km). Saat ini, Transjakarta terhubung dengan daerah Bodetabek (Bogor, Depok, Tangerang, dan Bekasi).

### Permasalahan dan Tujuan
Permasalahannya yaitu perusahaan ingin melihat secara detail mengenai kepadatan koridor dan halte, kategori penumpang, serta waktu sibuk dalam satu minggu sehingga dapat dilakukan aksi berkelanjutan untuk meningkatkan kenyamanan penumpang dari hasil analisis.

### Data Understanding
Sebelum lebih jauh dalam menganalisis dan memvisualisasi data, terlebih dahulu memahami isi data yang tersedia. Berikut garis besar langkah-langkahnya: 
#### 1. Informasi Data 
Memahami informasi dan kolom yang tersedia dalam dataset. Dalam dataset Transjakarta terdapat 22 kolom dan 37.900 baris
#### 2. _Missing Value_
Total 38.06% terdapat data yang hilang. Data yang hilang tersebut selanjutnya dapat dicek untuk disimpan untuk menjadi bahan analisis atau sebaiknya dihapus.
#### 3. Duplikasi Data
Dalam dataset tidak terdapat data duplikat
#### 4. Uji Statistik (Normalitas)
Distribusi dalam dataset yaitu distribusi tidak normal.
#### 5. Outlier
Dalam dataset, outlier yang divisualisasikan dapat dicek terlebih dahulu apakah dapat disimpan atau dihapus. 
#### 6. Korelasi
Melihat korelasi dalam bentuk heat map. 

### Data Cleaning
Sebelum lebih lanjut melakukan cleaning data, dapat menambahkan kolom yaitu kategori umur, durasi perjalanan, dan hari. 
Berikut garis besar untuk melakukan cleaning data:
#### 1. Melihat Letak_ Missing Value_
Kolom yang berisi missing value berada dalam kolom corridorID, corridorName, tapInStops, tapOutStops, tapOutStopsName, tapOutStopsLat, tapOutStopsLon, stopEndSeq, tapOutTime, payAmount.
#### 2. Imputasi Nilai
Kolom-kolom yang berisi missing value dapat diisi satu sama lain, contohnya corridorID dengan corridorName, tapInStops dengan tapInStopsName, dan selanjutnya.
#### 3. Cek Hasil Akhir
Setelah berhasil dicleaning, dipastikan lagi missing value-nya telah teratasi seluruhnya, termasuk dalam kolom yang baru ditambahkan

### Visualisasi Data
Setelah data semua bersih dan dipastikan ulang, data dapat divisualisasikan.
#### 1. Kategori Umur dan Gender Penumpang
Melihat kategori umur dan gender yang menaiki Transjakarta.
#### 2. Koridor dan Halte
Koridor dan halte dilihat dari yang terpadat.
#### 3. Waktu Sibuk
Dari kolom tap waktu awal dan tap waktu akhir dapat dilihat waktu-waktu sibuk dalam satu minggu selama 24 jam.

### Kesimpulan dan Rekomendasi
Kesimpulan dan rekomendasi didapat dari hasil analisis dan visual yang telah dilakukan. Perusahaan dapat mempertimbangkan langkah selanjutnya demi meningkatkan kenyamanan penumpang.




