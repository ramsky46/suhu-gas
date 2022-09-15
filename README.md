# suhu-gas
esp32 suhu dan gas

Hi, disini aku akan menjelaskan salah satu project aku yaitu suhu dan gas berbasis IoT. 
Disini aku menggunakan ESP32, DHT11, MQ2, dan Blynk. Untuk memprogramnya menggunakan Arduino IDE.

# Parts Required
1. ESP32
2. DHT11
3. MQ2
4. Resistor 10k
5. some jumper wires
6. Breadboard

Setelah mempersiapkan bahan-bahannya, kita bisa langsung merangkainya seperti yang tertera pada gambar.


# Installing Libraries
Untuk membaca dari sensor DHT, kita akan menggunakan library DHT dari Adafruit. Untuk menggunakan library ini Anda juga perlu menginstal library Adafruit Unified Sensor. Ikuti langkah selanjutnya untuk menginstal library tersebut.
Buka Arduino IDE Anda dan pergi ke Sketch > Include Library > Manage Libraries. Manajer Perpustakaan harus terbuka.
Cari "DHT" di kotak Pencarian dan instal library DHT dari Adafruit.
Setelah menginstal library DHT dari Adafruit, ketik "Adafruit Unified Sensor" di kotak pencarian. Gulir ke bawah untuk menemukan library dan menginstalnya.
