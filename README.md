# agczn-maintenance-503
Membuat website agcnz ke dalam mode maintenance. Ini berfungsi agar content yang telah di index tidak lenyap dari peringkat saat website dalam perbaikan atau downtime.
Mengembalikan response code headers 503 hasil HTTP (Layanan Tidak Tersedia) yang memberi tahu crawler mesin pencari bahwa waktu henti tersebut bersifat sementara. Selain itu, ini memungkinkan pemilik situs untuk memberikan perkiraan waktu kepada pengunjung dan bot kapan situs akan aktif dan berjalan kembali.

# Penjelasan
Dalam penjelasan pada artikel resminya [Lihat Disini](https://developers.google.com/search/docs/crawling-indexing/pause-online-business#best-practices-disabling-site). Google menyarankan, saat website dalam keadaan maintenance harus mematuhi beberapa hal berikut :
- Jangan larang semua perayapan di file robots.txt. Artinya file robots.txt harus tetap dapat di akses dan code response yang dikembalikan harus 200.
- Halaman Home harus dapat di akses dan code response harus 200 [Lihat Disini](https://developers.google.com/search/docs/crawling-indexing/pause-online-business#best-practices-disabling-site:~:text=Jika%20Anda%20perlu%20menonaktifkan%20situs%20untuk%20waktu%20yang%20lebih%20lama%2C%20sediakan%20laman%20beranda%20yang%20dapat%20diindeks).

# Panduan Pemakaian.
