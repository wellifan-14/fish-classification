## Klasifikasi Ikan Cakalang dan Tongkol Menggunakan Convolutional Neural Network
Projek ini bertujuan untuk menerapkan CNN dalam melakukan klasifikasi spesies  ikan  cakalang (Katsuwonus pelamis)  dan  tongkol (Euthynnus  affinis).
Dalam  proses  pelatihan model   klasifikasi   CNN,   Projek   ini   menggunakan pendekatan transfer  learning  dengan  memanfaatkan  model terlatih / model pre-trained dari pustaka Keras Applications, yaitu VGG16 dan ResNet50. Pada penggunaan kedua model tersebut,  dilakukan  perbandingan  untuk  mendapatkan  model klasifikasi dengan performa yang terbaik.
## Hasil
1. Percobaan yang dilakukan pada projek ini, mendapatkan model klasifikasi CNN terbaik yang dibangun  menggunakan pendekatan transfer learning dengan memanfaatkan model pre-trained ResNet50.
2. Proses pelatihan pada model ini mendapatkan nilai loss train 0.000069, akurasi train 1.0000, loss validasi 0.0806, akurasi validasi  0.9884.
3. Setelah  pelatihan,  model  ini  diuji menggunakan data citra baru yang terdiri dari 20 citra perkelas. Model yang digunakan adalah model Pelatihan Keseluruhan (200 Epoch). Model ini mendapatkan nilai performa akurasi 0.95, rata-rata  makro precision 0.95,  rata-rata  makro recall 0.95, rata-rata makro f1 score 0.95.

- Dataset : [Link 1](https://drive.google.com/file/d/1-gkYMouqtRfol-EqKwfBG4qpKJgzaPET/view?usp=drive_link)
- Model Hasil: [Link 2](https://drive.google.com/file/d/1bRxdTIKUDV2ftIRmJncvCGtePHzolU_w/view?usp=drive_link)
