## Judul Studi Kasus:
Sistem IoT Monitoring Suhu dan Kontrol Lampu dengan Buzzer serta DHT11 dengan IOT Platform Thingspeak

## Group Members:
- Sancto Metano Crozart (2109106112)
- Muhammad Akbar Fahrezi (2109106117)
- M. Yudith Aryanta Aditya (2109106122)

## Deskripsi:
Studi kasus ini mencakup pembuatan sebuah sistem IoT menggunakan platform Thingspeak. Tujuan dari proyek ini adalah untuk memantau suhu dalam ruang server dan memberikan peringatan suara serta mengontrol lampu sesuai dengan kondisi suhu yang ditentukan.

## Cara Kerja Alat:
1. Sensor DHT11 digunakan untuk mendeteksi suhu di dalam ruang server.
2. NodeMCU (ESP8266) akan membaca data suhu dari sensor DHT11.
3. Data suhu akan dikirim ke dashboard Blynk melalui koneksi Wi-Fi.
4. Pada dashboard Blynk, pengguna dapat memonitor suhu dalam format Celsius, Fahrenheit, dan Kelvin.
5. Sesuai dengan kondisi suhu yang ditentukan (di bawah 30°C, 30-36°C, atau di atas 36°C), LED akan menampilkan warna yang sesuai (hijau, kuning, atau merah).
6. Jika suhu melebihi 36°C, buzzer akan memberikan peringatan suara.

## Pembagian Tugas per Individu:
- Sancto Metano Crozart (2109106112):
  - Membuat proyek dan dashboard Blynk.
  - Menulis kode Arduino untuk membaca data suhu dari sensor DHT11.
- Muhammad Akbar Fahrezi (2109106117):
- - Merangkai rangkaian hardware.
  - Menulis kode Arduino untuk mengontrol LED dan mengirim data suhu ke dashboard Thingspeak.
- M. Yudith Aryanta Aditya (2109106122):
  - Menambahkan fitur peringatan suara menggunakan buzzer.
  - Melakukan pengujian keseluruhan sistem.
  - Membuat Skematik Design

## Komponen yang Digunakan:
1. NodeMCU (ESP8266) - Digunakan untuk mengendalikan sistem dan terhubung ke Wi-Fi.
2. Sensor DHT11 - Digunakan untuk mendeteksi suhu ruangan.
3. LED - Digunakan untuk menampilkan status suhu (hijau, kuning, merah).
4. Buzzer - Digunakan untuk memberikan peringatan suara jika suhu melebihi batas yang ditentukan.
5. Resistor - Digunakan untuk melindungi LED dan buzzer dari arus berlebih.


## Board Skematic:

# 1. Design Scheamtic
![posttest3_skematik_design](https://github.com/yudthadtyaaa/-posttest1-praktikum-iot-unmul-2024/assets/95072812/b2353de5-af65-42d8-944a-9dbf40156629)

# 2. Design Real
![posttest3_skematik_real](https://github.com/yudthadtyaaa/-posttest1-praktikum-iot-unmul-2024/assets/95072812/4cc45081-9d16-4ae6-b85e-5a307a16511d)
