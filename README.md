# PRAKTIKUM API CRUD

NAMA  : MOCH FIRMAN TRISWANDA
NIM   : 362458302013
KELAS : 2B TRPL

## TUGAS
**Tugas 1**: Geocoding (Alamat dari Koordinat)
Saat ini kita hanya menampilkan Lat/Lng. Buatlah agar aplikasi menampilkan alamat
(nama jalan, kota, dll) dari koordinat yang didapat.
Petunjuk:
1. Anda sudah menambahkan paket geocoding di pubspec.yaml.
   <img width="1568" height="864" alt="image" src="https://github.com/user-attachments/assets/ddf3341b-ec56-4eb1-84a3-5d58fa806864" />
   
2. Import paketnya: import ’package:geocoding/geocoding.dart’;
   <img width="1298" height="528" alt="image" src="https://github.com/user-attachments/assets/1fc29f60-6049-455d-9876-9a01eec5f634" />

3. Buat variabel String? currentAddress; di MyHomePageState.
   <img width="1232" height="640" alt="image" src="https://github.com/user-attachments/assets/4080f91b-9646-4c15-9a1e-ca2d028d52c8" />

4. Buat fungsi baru getAddressFromLatLng(Position position).
   <img width="2048" height="1236" alt="image" src="https://github.com/user-attachments/assets/9bbd1a73-f961-4a26-9dcc-6376d560cc89" />

5. Panggil fungsi getAddressFromLatLng( currentPosition!) di dalam getLocation dan startTracking (di dalam .listen()) setelah setState untuk currentPosition.
   <img width="1518" height="2018" alt="image" src="https://github.com/user-attachments/assets/3324f051-1af4-4f95-85fa-d9d34ff4bfa3" />

6. Tampilkan currentAddress di UI Anda, di bawah Lat/Lng.
   ![WhatsApp Image 2025-11-11 at 01 12 17_1bdaa160](https://github.com/user-attachments/assets/56bd02b7-535f-474a-96ee-2943f57fbda3)

