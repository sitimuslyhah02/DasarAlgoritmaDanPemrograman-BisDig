# DasarAlgoritmaDanPemrograman-BisDig
Ujian Tengah Semester (UTS) Siti Muslyhah 24110310079 (2A) Bisnis Digital

NO 1. Jelaskan bagaimana struktur kontrol percabangan digunakan untuk logika pemberian diskon.
   Struktur kontrol percabangan digunakan dalam pemrograman untuk membuat keputusan berdasarkan kondisi tertentu. Dalam kasus,
   sistem e-commerce yang memberikan diskon 10% jika total belanja pelanggan di atas Rp500.000.

   Langkah-langkah Penggunaan Struktur Kontrol Percabangan :
1. Input total belanja: sistem meminta pengguna untuk menginput total belanjaan mereka.
   Ini adalah nilai yang akan dinilai untuk menentukan apakah diskon dapat diterapkan,
   Menggunakan struktur kontrol percabangan, kita memeriksa apakah total belanja lebih besar dari Rp500.000.
   Ini dilakukan dengan menggunakan pernyataan if.
2. Terapkan diskon: Jika kondisi terpenuhi (artinya total belanja lebih dari Rp500.000)
   sistem menghitung diskon 10% dari total belanja dan menguranginya dari total belanja.
   Jika kondisi tidak terpenuhi (artinya total belanja kurang dari atau sama dengan Rp500.000),
   total belanja tetap tanpa diskon. Lalu Setelah memeriksa kondisi dan menerapkan diskon (jika ada),
   sistem menampilkan total belanja akhir kepada pengguna.

N0 2. Jelaskan peran tipe data dan operator dalam menyelesaikan perhitungan tersebut.
   Tipe data numerik: Untuk menyimpan nilai dari pelajaran, kita memakai tipe data numerik, seperti int (integer) atau float (bilangan pecahan)
   Tipe data boolean: Setelah menghitung rata-rata, kita harus memutuskan apakah siswa tersebut lulus atau tidak. Untuk keperluan ini, kita bisa memanfaatkan tipe data boolean 
   (True or False).

   Operator Numerik: Operator aritmetika untuk menghitung rata-rata nilai. 
   Operator yang digunakan meliputi: Penjumlahan (+): Untuk menghitung total nilai dari tiga mata pelajaran.
   Pembagian (/): Digunakan untuk membagi total nilai dengan jumlah pelajaran agar bisa memperoleh rata-rata.
   Operator perbandingan: Setelah mendapatkan rata-rata, kita perlu membandingkannya dengan nilai ambang batas kelulusan.

N0 3. Jelaskan manfaat penggunaan fungsi dan bagaimanar rekursi  bekerja dalam menghitung faktorial
    Manfaat penggunaan rekursi yaitu
    
    Modularitas: Fungsi memungkinkan pemecahan program menjadi bagian-bagian kecil yang lebih mudah dikelola dan dipahami.
    Reusabilitas: Fungsi yang telah dibuat dapat digunakan kembali di berbagai bagian program tanpa perlu menulis ulang kode.
    Abstraksi: Fungsi menyembunyikan detail implementasi dan hanya menampilkan antarmuka yang diperlukan, sehingga pengguna fungsi tidak perlu memahami cara kerjanya secara mendalam.
    Pengujian dan Pemeliharaan: Fungsi yang terpisah memudahkan pengujian dan pemeliharaan kode, karena setiap fungsi dapat diuji secara independen.
    
    Cara rekursi bekerja dalam menghitung faktorial:

    1. Basis kasus Basis Kasus: Jika n=0, maka fungsi akan mengembalikan nilai 1.
    2. Kasus Rekursif jika n>0 fungsi akan memanggil dirinya sendiri dengan argumen n-1 dan mengalikan hasilnya dengan n

 NO 4. Jelaskan penggunaan perulangan dan array dalam kasus ini
   Penggunaan perulangan pada kasus: Perulangan (looping) dipakai untuk menjalankan suatu blok kode berulang kali. 
   Dalam kasus ini, kita harus memasukkan nilai untuk 5 siswa. Dengan memanfaatkan perulangan, kita bisa meminta input nilai siswa secara bertahap 
   tanpa harus menuliskan kode yang sama berulang kali.
    
   Penggunaan Array dalam kasus ini adalah: Array (atau list dalam Python) merupakan struktur data yang digunakan untuk menyimpan kumpulan nilai. 
   Dalam kasus ini, kita dapat memanfaatkan array untuk menyimpan nilai-nilai yang dimasukkan bagi setiap siswa. Dengan menyimpan data dalam array, 
   kita bisa dengan mudah mengakses dan mengelola informasi setiap siswa tersebut.

NO 5. Langkah-langkah algoritma dalam menyelesaikan studi kasus tersebut yaitu:
    1. Inisialisasi Variabel: Buat variabel 'total_harga' untuk menyimpan total harga pembelian dan inisialisasi dengan nilai 0.
    2. Input Harga Barang: Buat perulangan yang akan berjalan sebanyak 3 kali (karena ada 3 barang).
       Dalam setiap iterasi, lakukan langkah berikut:
      -Tanyakan kepada pengguna untuk memasukkan harga barang ke-1 (misalnya, "Masukkan harga barang ke-1").
       Simpan harga yang dimasukkan ke dalam variabel harga.
    3. Penjumlahan harga: Tambahkan harga yang dimasukkan ke dalam 'total_harga' setelah setiap input.
    4. Tampilkan Total Harga: Setelah semua harga barang dimasukkan dan dijumlahkan, tampilkan total harga kepada pengguna dengan format yang jelas.
