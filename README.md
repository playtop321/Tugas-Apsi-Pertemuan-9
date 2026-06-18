# Tugas-Apsi-Pertemuan-9

## Use Case Diagram
Use Case Diagram digunakan untuk menggambarkan interaksi antara aktor dengan Sistem Informasi Penjualan Bakpao. Pada sistem ini terdapat tiga aktor yaitu Admin, Kasir, dan Pemilik. Admin memiliki hak akses untuk mengelola data produk, data pelanggan, transaksi penjualan, pembayaran, serta melihat laporan. Kasir bertugas melakukan transaksi penjualan dan pembayaran. Pemilik hanya memiliki akses untuk melihat laporan penjualan yang dihasilkan oleh sistem. Diagram ini membantu dalam memahami kebutuhan fungsional sistem dari sudut pandang pengguna.

## Activity Diagram
Activity Diagram menggambarkan alur aktivitas yang terjadi dalam proses penjualan bakpao. Proses dimulai dari login ke sistem, kemudian pengguna memilih produk yang akan dijual. Setelah produk dipilih, pengguna memasukkan jumlah produk yang dibeli. Sistem kemudian menghitung total harga berdasarkan jumlah dan harga produk. Setelah pembayaran dilakukan, sistem menyimpan data transaksi dan mencetak struk sebagai bukti pembelian. Diagram ini menunjukkan urutan aktivitas yang dilakukan oleh pengguna dan sistem selama proses transaksi berlangsung.

## Flowchart Transaksi Penjualan
Flowchart digunakan untuk menjelaskan alur logika proses transaksi penjualan bakpao. Proses dimulai dari login, kemudian memilih produk dan memasukkan jumlah pembelian. Sistem akan menghitung total pembayaran yang harus dibayar pelanggan. Selanjutnya dilakukan proses pembayaran. Apabila pembayaran berhasil, sistem akan mencetak struk dan proses berakhir. Jika pembayaran gagal, pengguna akan kembali ke proses pemilihan produk. Flowchart ini membantu menggambarkan langkah-langkah operasional secara sederhana dan mudah dipahami.

## Entity Relationship Diagram (ERD)
Entity Relationship Diagram (ERD) digunakan untuk menggambarkan struktur basis data yang digunakan dalam Sistem Informasi Penjualan Bakpao. Terdapat empat entitas utama yaitu Pelanggan, Penjualan, Detail Penjualan, dan Produk. Entitas Pelanggan berhubungan dengan Penjualan karena satu pelanggan dapat melakukan banyak transaksi. Entitas Penjualan berhubungan dengan Detail Penjualan karena satu transaksi dapat memiliki beberapa detail produk yang dibeli. Entitas Produk berhubungan dengan Detail Penjualan karena satu produk dapat muncul pada banyak transaksi. ERD membantu dalam perancangan database agar data tersimpan secara terstruktur dan terhubung dengan baik.

## DFD Level 0 (Context Diagram)
DFD Level 0 atau Context Diagram menggambarkan sistem secara keseluruhan dan menunjukkan hubungan antara sistem dengan entitas luar. Pada diagram ini terdapat tiga entitas eksternal yaitu Pelanggan, Kasir, dan Pemilik. Pelanggan memberikan data pesanan kepada sistem dan menerima struk atau nota. Kasir memberikan data transaksi kepada sistem dan menerima informasi produk. Pemilik menerima laporan penjualan dari sistem. Diagram ini memberikan gambaran umum mengenai aliran data yang masuk dan keluar dari sistem.

## DFD Level 1
DFD Level 1 merupakan pengembangan dari DFD Level 0 yang menjelaskan proses-proses utama dalam sistem secara lebih rinci. Terdapat tiga proses utama yaitu Kelola Pesanan, Kelola Penjualan, dan Kelola Produk. Proses Kelola Pesanan bertugas mengelola data pesanan pelanggan. Proses Kelola Penjualan menangani transaksi penjualan dan penyimpanan data transaksi. Proses Kelola Produk digunakan untuk mengelola data produk yang tersedia. Data dari proses-proses tersebut disimpan ke dalam data store yang terdiri dari tabel Pelanggan, Penjualan, dan Produk. Informasi yang tersimpan kemudian digunakan untuk menghasilkan laporan penjualan.

## Sequence Diagram
Sequence Diagram digunakan untuk menggambarkan urutan interaksi antara Kasir, Sistem, Database, dan Printer selama proses transaksi berlangsung. Proses dimulai ketika Kasir melakukan login ke sistem. Sistem akan memvalidasi data pengguna ke database dan mengembalikan hasil validasi. Setelah berhasil login, Kasir memilih produk yang akan dijual dan sistem mengambil data produk dari database. Selanjutnya transaksi disimpan ke database. Setelah data berhasil disimpan, sistem mengirimkan data ke printer untuk mencetak struk transaksi. Diagram ini menunjukkan komunikasi antar objek berdasarkan urutan waktu.

## Class Diagram
Class Diagram digunakan untuk menggambarkan struktur kelas yang terdapat dalam Sistem Informasi Penjualan Bakpao. Terdapat lima kelas utama yaitu Pelanggan, Penjualan, Produk, DetailPenjualan, dan User. Setiap kelas memiliki atribut yang digunakan untuk menyimpan informasi yang berkaitan dengan objek tersebut. Relasi antar kelas menunjukkan hubungan antara pelanggan dengan transaksi penjualan, transaksi penjualan dengan detail penjualan, serta produk dengan detail penjualan. Diagram ini menjadi dasar dalam pengembangan sistem berbasis objek karena menggambarkan struktur data dan hubungan antar kelas yang akan digunakan dalam aplikasi.
