# ARTBOARD – Jasa Desain Grafis dan Dokumen Digital

ARTBOARD merupakan website layanan desain grafis dan pengolahan dokumen digital. Website ini dibuat untuk memudahkan pelanggan melihat layanan, mengajukan pesanan, mengisi kebutuhan desain, melihat estimasi biaya, serta memantau status pesanan melalui satu platform.

## Identitas Kelompok

**Kelompok 5 – Praktikum Kewirausahaan**  
Program Studi Informatika, Fakultas Matematika dan Ilmu Pengetahuan Alam  
Universitas Syiah Kuala  
Tahun Akademik 2026/2027

| No. | Nama Anggota | NPM |
|---|---|---|
| 1 | Nayla Nabila Syahel | 2408107010005 |
| 2 | Rahmatul Uliya | 2408107010012 |
| 3 | Mahda Annisa | 2408107010036 |

*Lengkapi bagian NPM sebelum README dikumpulkan atau dipublikasikan.*

## Deskripsi Sistem

ARTBOARD adalah platform digital yang menyediakan layanan desain grafis dan pengolahan dokumen sesuai kebutuhan pelanggan. Pengguna dapat memilih layanan yang tersedia atau mengajukan permintaan khusus melalui fitur **Custom Request**.

Website dirancang dengan tampilan sederhana dan responsif, menggunakan kombinasi warna krem, cokelat, oranye, dan aksen hijau. Sasaran pengguna ARTBOARD meliputi pelajar dan mahasiswa, karyawan, guru dan dosen, UMKM, organisasi, serta masyarakat umum.

## Fitur Website

### 1. Beranda
- Menampilkan pengenalan dan gambaran umum layanan ARTBOARD.
- Menampilkan ringkasan alur pemesanan.
- Menampilkan manfaat layanan dan target pengguna.
- Menyediakan tombol untuk melihat layanan dan membuat pesanan.

### 2. Katalog Layanan
Pengguna dapat melihat pilihan layanan berikut:
- Pengolahan dokumen (Word, Excel, dan PowerPoint).
- CV dan surat lamaran.
- Infografis.
- Poster dan flyer.
- Sertifikat.
- ID Card.
- Desain menu.
- Diagram dan flowchart.
- Desain presentasi.
- Chart dan visualisasi data.
- Custom Request.

Harga yang ditampilkan merupakan harga awal/contoh pada prototipe. Harga akhir perlu dikonfirmasi sesuai kebutuhan pesanan.

### 3. Masuk dan Daftar
- Pengguna mengisi nama dan email untuk masuk ke prototipe.
- Akun dibuat secara otomatis dalam simulasi.
- Data pengguna disimpan pada `localStorage` browser.

### 4. Formulir Pemesanan
Pengguna dapat:
- Memilih jenis layanan.
- Mengisi judul dan detail pesanan.
- Menentukan jumlah pesanan.
- Menentukan deadline.
- Memilih file bahan atau referensi dari perangkat.
- Melihat ringkasan dan estimasi biaya.

### 5. Estimasi Biaya dan Pembayaran
- Sistem menghitung estimasi biaya berdasarkan jenis layanan dan jumlah pesanan.
- Terdapat tambahan biaya Express Service sebesar 30% dari biaya dasar apabila deadline satu hari atau kurang.
- Sistem menampilkan estimasi DP sebesar 50% dari total biaya.
- Pilihan metode pembayaran yang tersedia pada demo adalah transfer bank, QRIS, dan e-wallet.

### 6. Pesanan Saya
Pengguna dapat melihat status pesanan melalui tahapan:
1. DP dibayar.
2. Dikerjakan.
3. Hasil sementara.
4. Revisi atau persetujuan.
5. Pelunasan.
6. Selesai.

Tombol aksi pada halaman ini digunakan untuk menyimulasikan perubahan status pesanan, revisi, pelunasan, dan pengiriman hasil akhir. Belum ada file hasil yang benar-benar dibuat atau diunduh dari server.

## Alur Kerja Sistem

Alur pemesanan ARTBOARD dari sisi pelanggan adalah sebagai berikut:

1. **Masuk atau daftar** – pelanggan mengisi nama dan email agar data akun tersimpan pada browser.
2. **Memilih layanan** – pelanggan memilih layanan dari katalog atau menggunakan Custom Request.
3. **Mengisi detail pesanan** – pelanggan mengisi judul, deskripsi kebutuhan, jumlah, deadline, serta memilih bahan atau referensi.
4. **Melihat estimasi biaya** – sistem menghitung biaya berdasarkan layanan, jumlah, dan ketentuan Express Service.
5. **Konfirmasi dan pembayaran DP** – pelanggan menyetujui estimasi biaya dan memilih metode pembayaran. Pada prototipe, pembayaran DP disimulasikan.
6. **Proses pengerjaan** – status pesanan berubah menjadi sedang dikerjakan.
7. **Pemeriksaan dan hasil sementara** – pelanggan dapat menyimulasikan penerimaan hasil sementara.
8. **Revisi atau persetujuan** – pelanggan dapat menyetujui hasil atau mengajukan revisi.
9. **Pelunasan** – pelanggan menyimulasikan pembayaran sisa biaya.
10. **Pesanan selesai** – status berubah menjadi selesai. Pengiriman/unduhan file akhir pada versi ini masih berupa simulasi.

## Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| HTML5 | Menyusun struktur dan konten halaman website. |
| CSS3 | Mengatur tata letak, warna, tipografi, komponen, dan responsivitas tampilan. |
| JavaScript | Mengatur navigasi, formulir pemesanan, perhitungan biaya, autentikasi demo, dan perubahan status pesanan. |
| Local Storage | Menyimpan data akun dan pesanan pada browser pengguna. |
| Google Fonts | Menggunakan font Bricolage Grotesque dan DM Sans. |

Website ini tidak memerlukan instalasi framework atau database untuk menjalankan versi prototipe.

## Cara Menjalankan Website

### Cara 1 – Membuka Langsung
1. Unduh atau ekstrak file proyek ARTBOARD.
2. Buka folder `artboard-site`.
3. Klik dua kali file `index.html`.
4. Website akan terbuka melalui browser seperti Google Chrome, Microsoft Edge, atau Firefox.

### Cara 2 – Menggunakan Visual Studio Code
1. Pastikan Visual Studio Code sudah terpasang.
2. Ekstrak proyek ARTBOARD.
3. Buka Visual Studio Code.
4. Pilih **File → Open Folder**, kemudian pilih folder `artboard-site`.
5. Buka file `index.html`.
6. Jalankan file menggunakan ekstensi **Live Server** (klik kanan pada `index.html` → **Open with Live Server**).
7. Website akan terbuka pada browser melalui alamat lokal yang disediakan Live Server.

Tidak diperlukan perintah `npm install` atau `npm run dev` karena proyek ini merupakan website statis HTML, CSS, dan JavaScript.

## Penyimpanan Data dan Batasan Prototipe

- Data akun dan pesanan disimpan pada `localStorage` browser.
- Data tidak tersinkronisasi antarperangkat atau antarbrowser.
- Menghapus data situs/browser dapat menghapus data demo.
- Formulir pemesanan belum mengirim data ke server.
- File yang dipilih pengguna belum diunggah ke server.
- Pembayaran dan pelunasan belum diproses secara nyata.
- Perubahan status pesanan dilakukan melalui tombol simulasi.
- Fitur unduh hasil akhir belum terhubung dengan file hasil produksi.

## Pengembangan Selanjutnya

Pengembangan berikutnya dapat mencakup backend dan database untuk mengelola akun serta pesanan, autentikasi yang lebih aman, penyimpanan dan unggah file, integrasi payment gateway, dashboard admin untuk mengelola pesanan, serta mekanisme pengiriman hasil dan revisi secara nyata.

## Tujuan Pembuatan

Proyek ARTBOARD dibuat sebagai bagian dari Praktikum Kewirausahaan untuk memperkenalkan konsep layanan jasa desain dan pengolahan dokumen digital melalui sebuah prototipe website. Prototipe ini menggambarkan bagaimana pelanggan dapat menemukan layanan, mengajukan pesanan, memperoleh estimasi biaya, dan memantau tahapan pesanan secara terstruktur.

---

**ARTBOARD – From ideas to something real.**  
Kelompok 5 | Praktikum Kewirausahaan | Informatika – FMIPA, Universitas Syiah Kuala
