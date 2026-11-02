# Proyek_Akhir_DDP

Sistem Pemesanan Makanan Online

Anggota & Peran:
1. Rafik Anugrah Yana (Programmer) 
2. Septiya Maharani (Flowchart Admin,Registrasi)
4. Nila Amelia Nabilla (Flowchart User, Menu Utama)
5. Wahyu Farras Zaky (Laporan)

Deskripsi:

Perkembangan teknologi informasi dan perubahan gaya hidup masyarakat membuat kebutuhan akan layanan pemesanan makanan yang cepat, praktis, dan terorganisir terus meningkat. Konsumen kini terbiasa mengakses informasi menu, harga, dan ketersediaan makanan dengan mudah. Mereka juga mengharapkan proses pemesanan dan pembayaran yang efisien. Namun, tidak semua pelaku usaha kuliner, terutama usaha skala kecil dan menengah seperti warung makan, kantin, dan kedai, bisa mengikuti perkembangan tersebut. Sebagian besar masih mengelola proses pemesanan secara manual melalui buku catatan, nota kertas, atau ingatan pegawai. Cara kerja seperti ini menimbulkan berbagai permasalahan, baik bagi pelaku usaha maupun pelanggan.
Permasalahan tersebut meliputi: Pencatatan pesanan yang mudah terjadi kesalahan, menghitung total pembayaran yang membutuhkan waktu lama dan sering terjadi kesalahan hitung, pengelolaan stok yang tidak dipantau secara langsung, pengelolaan data menu dan harga yang kurang teratur, tidak adanya pencatatan riwayat transaksi yang rapi, rekapitulasi penjualan yang manual dan sering tidak tepat, sistem pembayaran tidak praktis dan sulit dicatat. Kurangnya kontrol atas hak akses dan keamanan data.

Berdasarkan permasalahan itu, dibutuhkan sistem pemesanan makanan yang bisa mengotomatisasi semua alur transaksi. Proses ini meliputi pendaftaran dan verifikasi pengguna, penampilan menu, pemesanan dengan pengecekan stok dan saldo, pembayaran, pencetakan bukti transaksi, serta pembuatan laporan penjualan. Sistem ini juga harus membedakan hak akses antara admin sebagai pengelola dan pengguna sebagai pelanggan.

Untuk memenuhi kebutuhan ini, penelitian ini membuat program Sistem Pemesanan Makanan Online dengan bahasa pemrograman Python yang berjalan di terminal. Program ini punya fitur registrasi dan login dengan batas percobaan. Pengguna bisa mengelola menu secara penuh, seperti menambah, melihat, mengubah, dan menghapus menu. Ada juga fitur pemesanan dengan keranjang belanja. Pembayaran memakai saldo E-Money. Program bisa mencetak invoice, menampilkan riwayat transaksi, dan membuat laporan ringkas penjualan. Semua data disimpan secara permanen dalam file JSON. Program ini dibuat sebagai prototipe dasar yang menunjukkan konsep sistem pemesanan makanan online dan bisa dikembangkan lagi menjadi aplikasi berbasis web atau mobile dengan basis data dan layanan pembayaran yang sesungguhnya.

Tujuan:

1.	Membuat program pemesanan makanan berbasis Python dengan pemisahan hak akses admin dan user.
2.	Menyediakan sistem registrasi dan login yang aman dengan validasi data dan batas percobaan.
3.	Memudahkan pelanggan melihat menu, memesan makanan, dan membayar menggunakan E-Money dengan validasi stok dan saldo otomatis.
4.	Membantu admin mengelola menu, akun pengguna, riwayat transaksi, dan laporan penjualan.
5.	Menghasilkan bukti transaksi berupa invoice dan riwayat pemesanan yang tercatat otomatis.
6.	Menerapkan konsep dasar pemrograman Python seperti percabangan, perulangan, fungsi, tuple, list, dictionary, penanganan error, dan pengelolaan file JSON.

FLOWCHART

Berikut ini merupakan flowchart dari sistem pemesanan makanan online yang menggambarkan alur proses kerja sistem, mulai dari proses awal hingga proses akhir. Flowchart ini dibuat untuk mempermudah pemahaman terhadap tahapan dan alur kerja sistem yang dikembangkan.<br>
| NAMA FLOWCHART | GAMBAR FLOWCHART | PENJELASAN |
| :---: | :---: | :--- |
| 1.Menu Utama |
| 2.Menu Registrasi | <img width="304" height="1072" alt="Salinan dari pa ddp-Registrasi drawio" src="https://github.com/user-attachments/assets/89efc3eb-bdc9-4639-a8eb-5c390d37faa6" /> | <p>berikut ini adalah penjelasan alur flowchart dari menu registrasi:</p><p><b>1. Input dan Validasi Username</b><br>Pengguna diminta memasukkan username dengan ketentuan minimal 4 karakter. Sistem kemudian melakukan pengecekan kondisi (decision):<br>• Jika Tidak memenuhi syarat (&lt; 4 karakter), sistem menampilkan pesan "Username minimal 4 karakter" lalu mengarahkan pengguna untuk menginput ulang username.<br>• Jika Ya (valid), alur dilanjutkan ke tahap berikutnya.</p><p><b>2. Input dan Validasi Password</b><br>Pengguna diminta memasukkan password dengan ketentuan minimal 6 karakter. Sistem kembali melakukan validasi:<br>• Jika Tidak memenuhi syarat (&lt; 6 karakter), sistem menampilkan pesan "Password minimal 6 karakter" lalu meminta pengguna menginput ulang password.<br>• Jika Ya (valid), proses berlanjut ke penyimpanan.</p><p><b>3. Penyimpanan Data dan Output</b><br>• Sistem memproses data akun baru dan menyimpannya secara permanen ke dalam file penyimpanan database (data.json).<br>• Sistem mencetak pesan sukses "Registrasi berhasil. Silakan login." ke layar.</p><p><b>4. Jika registrasi telah perhasil</b>,program akan mengarahkan untuk kembali ke Menu Utama agar user bisa melakukan login dengan akun yang baru dibuat.</p> |
| 3.Menu Login Sebagai Admin |
| 4.Menu Login Sebagai User | <img width="2407" height="3662" alt="pa ddp-Menu User" src="https://github.com/user-attachments/assets/a346e886-c8a8-4a60-95b3-169e264af5d4" /> |





1.Menu Utama

2.Menu Registrasi
Berikut ini merupakan flowchart menu registrasi yang menggambarkan alur proses pembuatan akun baru untuk user, mulai dari memasukkan data pengguna hingga akun berhasil didaftarkan ke dalam sistem.
><img width="304" height="1072" alt="Salinan dari pa ddp-Registrasi drawio" src="https://github.com/user-attachments/assets/89efc3eb-bdc9-4639-a8eb-5c390d37faa6" />

