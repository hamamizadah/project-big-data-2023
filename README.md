# Judul     : Menjelajahi Pola dan Tren Kanker Paru-paru: Pendekatan Berbasis EDA untuk Prediksi

## Projek UAS B DATA 2023
## Anggota   : 

-  ## Dio Aulia Ari Kurnia Sandi (2041720086)
-  ## Muhammad Hamamiy Zadah     (2041720028)

## Penjelasan Proyek

Proyek  Menjelajahi Pola dan Tren Kanker Paru-paru tujuan untuk meningkatkan akurasi prediksi. Penelitian sebelumnya juga menunjukkan bahwa kebiasaan merokok merupakan faktor risiko utama kanker paru-paru di Indonesia. Oleh karena itu, penelitian ini dapat memberikan kontribusi penting dalam upaya pencegahan dan pengobatan kanker paru-paru di Indonesia.


## Setup dan Running
- Clone repository GitHub: gunakan perintah git clone https://github.com/hamamizadah/project-big-data-2023 untuk menduplikasi repository proyek ini ke perangkat Anda.

- Buka situs colab.research.google.com pada browser Anda.

- Unggah file PreprocessingBigData.ipynb dan Tubes_Bigdata.ipynb yang telah anda unduh sebelumnya di dalam folder src ke Google Colab engan mengklik tombol "Upload" diantarmuka Google Colab.

- Sekarang, jalankan setiap baris kode pada setiap sel satu per satu, mulai dari baris impor (import) hingga mencapai hasil akhir. Anda dapat menjalankan setiap sel dengan mengklik ikon "Run" di sebelah kiri masing-masing sel atau menggunakan pintasan keyboard seperti Shift + Enter.


## Penjelasan Metode

### Life Cycle
![Screenshot ](img/flowchart/lifecycle.png)

### Flow Chart
![Screenshot ](img/flowchart/flowchart.png)

Pendekatan berbasis EDA menggunakan grafik, plot, dan teknik visualisasi data lainnya untuk memperoleh pemahaman yang lebih dalam tentang karakteristik data kanker paru-paru. Metode ini juga melibatkan analisis deskriptif, seperti perhitungan statistik sederhana dan pengelompokan data untuk mengidentifikasi kelompok yang berbeda.


### Preprocessing Big Data
1. install pyspark
![Screenshot ](img/preprocessingBigData/01.png)

2. import Spark Session
![Screenshot ](img/preprocessingBigData/02.importSparkSession.png)

3. menghilangkan nilai null

    ![Screenshot ](img/preprocessingBigData/03.menghilangkan_Nilai_null.png)

4. memilih kolom yang akan digunakan pada dataset
![Screenshot ](img/preprocessingBigData/04.memilih_Kolom_yang_ingin_digunakan_pada_dataset.png)

5. save hasil dari dataset terbaru

    ![Screenshot ](img/preprocessingBigData/05.save_hasil_dari_dataset_terbaru.png)


### Tubes Big Data
1. import library 

    ![Screenshot ](img/tubes_bigdata/1.import_library.png)

2. membaca dataset terbaru

    ![Screenshot ](img/tubes_bigdata/2.membaca_dataset_terbaru.png)

3. menyajikan grafik dari pengidap kanker berdasarkan umur
![Screenshot ](img/tubes_bigdata/3.menyajikan_grafik_dari_pengidap_kanker_berdasarkan_umur.png)

4. menyajikan grafik dari pengidap kanker berdasarkan Air pollution (Polusi udara)
![Screenshot ](img/tubes_bigdata/4.menyajikan_grafik_dari_pengidap_kanker_berdasarka_AirPollution_(Polusi_udara).png)

5. menyajikan grafik dari pengidap kanker berdasarkan gender
![Screenshot ](img/tubes_bigdata/5.menyajikan-grafik-dari-pengidap-kanker-berdasarkan-gender.png)

6. menyajikan grafik dari pengidap kanker berdasarkan perokok
![Screenshot ](img/tubes_bigdata/6.menyajikan-grafik-dari-pengidap-kanker-berdasarkan-perokok.png)

7. menyajikan grafik dari pengidap kanker berdasarkan perokok pasif
![Screenshot ](img/tubes_bigdata/7.menyajikan-grafik-dari-pengidap-kanker-berdasarkan-perokok-pasif.png)

8. histogram dari grafik 
![Screenshot ](img/tubes_bigdata/8.histogram-dari-grafik.png)

9. mendefinisikan variabel 

    ![Screenshot ](img/tubes_bigdata/9.mendefinisikan-variabel.png)

10. melakukan training
![Screenshot ](img/tubes_bigdata/10.melakukan-training.png)

11. menggunakan prediksi logistic regression
![Screenshot ](img/tubes_bigdata/11.menggunakan-prediksi-logistic-regression.png)

dari hasil prediksi logistic regression dengan score 0.66

## Refrensi
https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link


