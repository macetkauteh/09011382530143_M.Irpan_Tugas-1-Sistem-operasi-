# 09011382530143_M.Irpan_Tugas-1-Sistem-operasi-
Nama 	:  M.Irpan
Nim	: 09011382530143
Mata kuliah	: Sistem operasi
 Tugas
1. Buatlah laporan proses instalasi di komputer mahasiswa dan tampilkan screenshot-nya. 
1.Install virtual box
 gambar-01.jpeg
gambar-02.jpeg
 

2.Install ubuntu 24.04.4
 
 
3.Setting virtual box untuk ubuntu
 
 

 
 
 
 
4.lanjut masuk keubuntu
1.fase awal
 
 
 
 
 
 
2.fase buat akun dan login 
 
 
 
 
 

2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ? 
Jawaban:
Mount Point / disebut root directory (root filesystem) dan merupakan direktori utama dalam sistem Linux. Semua file dan direktori penting sistem Ubuntu berada di bawah /, seperti /home, /etc, /var, /usr, dan lainnya.
Oleh karena itu, ketika membuat partisi untuk instalasi Ubuntu, partisi utama harus diberikan Mount Point / agar Ubuntu mengetahui bahwa partisi tersebut digunakan sebagai filesystem utama untuk menjalankan sistem operasi.
Jika tidak ada partisi yang dipasang sebagai /, installer tidak memiliki lokasi utama untuk memasang sistem Ubuntu sehingga proses instalasi tidak dapat dilakukan dengan benar.
3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !
Jawaban:
1.ext4
Filesystem Linux yang paling umum digunakan. Stabil, cepat, mendukung ukuran file dan partisi besar, serta memiliki fitur journaling.
2.ext3
Filesystem Linux generasi sebelumnya yang merupakan pengembangan dari ext2 dengan fitur journaling. Saat ini banyak digantikan oleh ext4.
3.swap
Area yang digunakan Linux sebagai memori virtual ketika RAM tidak mencukupi. Swap juga dapat digunakan untuk mendukung fitur hibernasi.
4.NTFS
Filesystem utama yang digunakan oleh Windows. Mendukung file dan partisi berukuran besar serta memiliki fitur keamanan dan journaling.
5.FAT32
Filesystem yang sangat kompatibel dengan berbagai sistem operasi dan perangkat. Kekurangannya, ukuran satu file maksimal sekitar 4 GB.
6.Btrfs
ilesystem Linux modern yang memiliki fitur seperti snapshot, compression, checksumming, dan pengelolaan volume yang lebih fleksibel.

