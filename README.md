# 🏫 Pemodelan Sistem Antrian Penjadwalan Seminar Proposal, Seminar Hasil, dan Sidang Tugas Akhir Program Studi Sains Data Menggunakan Model M/M/1 dan M/M/c

## 📌 Deskripsi Proyek

Proyek ini merupakan penelitian untuk memodelkan sistem antrian pada tiga jenis proses sidang akademik yang ada di **Program Studi Sains Data Institut Teknologi Sumatera**, yaitu:
- **Seminar Proposal (Sempro)**
- **Seminar Hasil (Semhas)**
- **Sidang Tugas Akhir (TA)**

## 🧠 Latar Belakang Singkat

Program Studi Sains Data menghadapi tantangan dalam mengelola penjadwalan sempro, semhas, dan sidang akhir dengan jumlah ruangan terbatas dan permintaan yang bervariasi. Pengamatan awal menunjukkan bahwa utilisasi ruangan pada beberapa hari mencapai 68,75% dengan waktu tunggu rata-rata mencapai 98,59 menit, mengindikasikan adanya ketidakseimbangan antara kapasitas pelayanan dan permintaan. Kondisi ini berpotensi menurunkan kepuasan mahasiswa dan menghambat kelancaran proses penyelesaian studi.

Setiap periode sidang, banyak mahasiswa datang hampir bersamaan untuk mengikuti proses Sempro, Semhas, atau Sidang TA. Jumlah server (ruang sidang/penguji) yang terbatas dapat menimbulkan bottleneck, seperti:
- Jadwal molor
- Penumpukan antrian mahasiswa
- Utilisasi dosen yang tidak optimal

Penelitian ini bertujuan untuk mengukur performa sistem seperti waktu tunggu, utilisasi, dan panjang antrian, serta mengevaluasi apakah sistem saat ini bekerja secara optimal atau memerlukan perbaikan dengan pendekatan model antrian yang digunakan adalah **M/M/1** dan **M/M/c**.

## 🎯 Tujuan Penelitian

- Menentukan model antrian yang sesuai untuk sistem penjadwalan sempro, semhas, dan sidang menggunakan pendekatan **M/M/1** dan **M/M/c**
- Menghitung ukuran kinerja utilisasi **(ρ)**, rata-rata jumlah mahasiswa dalam antrian **(Lq)**, rata-rata jumlah mahasiswa dalam sistem **(Ls)**, rata-rata waktu tunggu dalam antrian **(Wq)**, dan rata-rata waktu tunggu dalam sistem **(Ws)**

---

## 🧮 Model Antrian yang Digunakan

### M/M/1
- 1 server, arrival ~ Poisson, service ~ Eksponensial.  
- Digunakan untuk skenario satu ruang.

### M/M/c
- c server paralel (beberapa ruang/penguji), arrival ~ Poisson, service ~ Eksponensial.  
- Menggunakan formula Erlang-C untuk menghitung Lq dan probabilitas antrian.

---

## 👥 Tim Penyusun
- Natasya Ega Lina Marbun    (122450024)
- Esteria Ronauli Sidauruk   (122450025)
- Elia Meylani Simanjuntak   (122450026)
- Ukasyah Muntaha		         (122450028) 
