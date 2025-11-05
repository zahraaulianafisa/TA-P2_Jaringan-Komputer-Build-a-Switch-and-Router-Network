TA Praktikum Judul 2 Jaringan Komputer - Build a Switch and Router Network.
Tugas ini merupakan tugas akhir praktikum mata kuliah Jaringan Komputer dengan tujuan untuk membangun jaringan yang terdiri dari switch dan router menggunakan Cisco Packet Tracer. Konfigurasi dilakukan agar setiap perangkat dapat saling berkomunikasi, baik dalam satu jaringan maupun antar jaringan. Pada percobaan ini juga dilakukan pengujian konektivitas jaringan (ping test) untuk memastikan komunikasi antar perangkat berhasil.

Berikut video demo konfigurasi jaringan dan hasil pengujiannya :
https://youtu.be/X2BjNQKqNk8?si=88g2-1ooM7mIOFF2

Hasil Percobaan
Gambar berikut menunjukkan hasil uji konektivitas jaringan sebelum dan sesudah dilakukan konfigurasi (ping test):
<img width="1042" height="711" alt="image" src="https://github.com/user-attachments/assets/be0bed39-93e2-4102-9236-90e1444b1c02" />
Gambar tersebut menunjukkan hasil pengujian konektivitas jaringan menggunakan perintah ping pada Command Prompt di perangkat PC A. Pada bagian pertama terlihat bahwa saat dilakukan pengujian ping ke alamat 192.168.0.3, muncul pesan “Request timed out” sebanyak satu kali. Hal ini menunjukkan bahwa pada saat itu koneksi antara PC A dengan perangkat tujuan belum berhasil. Penyebabnya adalah konfigurasi jaringan yang belum tepat, perangkat tujuan belum aktif, atau koneksi antar perangkat belum tersambung dengan baik. Kemudian, pada bagian kedua gambar terlihat hasil pengujian ping ke alamat 192.168.1.1. Berbeda dengan pengujian sebelumnya, kali ini seluruh paket data berhasil dikirim dan diterima dengan baik tanpa adanya kehilangan data (0% loss). Waktu respons (time) yang muncul berkisar antara 1 ms hingga 24 ms, yang menandakan bahwa koneksi jaringan sudah berhasil dan stabil.
