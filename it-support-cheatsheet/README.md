IT Support Cheatsheet



Repositori ini berisi catatan dan perintah dasar yang sering digunakan oleh IT Support atau Field Engineer dalam pekerjaan sehari-hari. Tujuan dari cheatsheet ini adalah sebagai panduan cepat saat melakukan troubleshooting di lapangan maupun saat belajar mandiri.



WINDOWS COMMAND PROMPT



Untuk mengecek konfigurasi IP Address pada komputer Windows gunakan perintah ipconfig. Perintah ini membantu melihat IP, subnet mask, dan gateway yang digunakan oleh perangkat.



Untuk mengecek koneksi jaringan ke internet atau ke server tertentu gunakan perintah ping, misalnya ping google.com. Jika mendapatkan reply berarti koneksi berjalan dengan baik.



Untuk melihat daftar proses yang sedang berjalan di sistem gunakan perintah tasklist. Perintah ini berguna ketika komputer terasa lambat atau terdapat aplikasi yang tidak responsif.



Untuk menghentikan aplikasi yang bermasalah gunakan perintah taskkill /IM namaprogram.exe /F. Perintah ini akan memaksa program tersebut berhenti.



NETWORK TROUBLESHOOTING



Langkah awal yang dapat dilakukan ketika jaringan bermasalah adalah memastikan kabel LAN terpasang dengan benar. Setelah itu cek IP Address dan gateway, pastikan komputer mendapatkan IP yang sesuai. Lakukan ping ke gateway untuk memastikan koneksi ke jaringan lokal berjalan. Jika masih bermasalah, lakukan restart pada adapter jaringan.



LINUX COMMAND DASAR



Untuk memperbarui daftar paket pada sistem Linux gunakan perintah sudo apt update. Perintah ini penting sebelum melakukan instalasi software.



Untuk melihat konfigurasi IP Address pada Linux gunakan perintah ip a. Informasi ini berguna untuk memastikan koneksi jaringan berjalan normal.



Untuk mengecek status service tertentu gunakan perintah systemctl status nama\_service, contohnya systemctl status ssh untuk melihat apakah service SSH aktif atau tidak.



TIPS LAPANGAN



Sebagai IT Support, selalu mulai pengecekan dari hal yang paling sederhana. Jangan panik ketika terjadi error dan biasakan mencatat setiap permasalahan beserta solusinya agar mudah diingat dan digunakan kembali di kemudian hari.



