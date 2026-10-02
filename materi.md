Mountrawr : Platform sederhana untuk meminjam/sewa alat pendakian sesuai kebutuhan dan durasi.

1. Siapa targetnya? Peminjam, Pemilik
2. Masalah yang diselesaikan? Sulit mengetahui alat tersedia pada tanggal tertentu, Peminjaman secara manual lewat WhatsApp/DM bisa bikin data berantakan.
3. Kenapa project ini harus diselesaikan? Agar proses pencatatan menjadi lebih rapi dan transparan
4. Fitur?
Login & Register — autentikasi pengguna.
Katalog Alat — melihat daftar dan kategori alat pendakian.
Detail & Ketersediaan — melihat informasi alat dan tanggal tersedia.
Peminjaman — mengajukan peminjaman dengan tanggal mulai dan kembali.
Approval Admin — admin menerima atau menolak pengajuan.
Status Peminjaman — melihat status peminjaman secara real-time.
Pengembalian — mencatat pengembalian alat.
Riwayat Peminjaman — melihat riwayat transaksi pengguna.
5. scope? backend php, frontend taildwind, database mysql
6. UserFlow
Register / Login → User masuk ke aplikasi.
Lihat Katalog → User melihat daftar alat pendakian.
Pilih Alat → User melihat detail dan ketersediaan alat.
Ajukan Peminjaman → User menentukan tanggal dan mengirim request.
Menunggu Approval → Admin menerima atau menolak request.
Peminjaman Disetujui → User mengambil alat dan status menjadi Dipinjam.
Pengembalian → User mengembalikan alat sesuai tanggal.
Selesai → Admin mengonfirmasi pengembalian dan transaksi masuk riwayat
7. arsitektur pakai mvc
8. kontrak data model (sesuaikan)


layered architecture?
1. presentation/ UI
2. service/ business logic
3. data/ storage

MVC (Model, View, Controller)

contract & data model
tentukan bentuk data, atributnya apa aja
contract = kesepakatan, field apa aja, tipe datanya apa, aturannya gmn
