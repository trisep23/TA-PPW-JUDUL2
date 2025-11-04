# Website Portofolio – Tri Septiani

Repository ini dibuat untuk memenuhi **_Tugas Akhir Percobaan 2: Git & Version Control_**  
pada mata kuliah **_Praktikum Pemrograman Web_**, Teknik Informatika, Fakultas Teknik, Universitas Lampung.

**Nama:** Tri Septiani  
**NPM:** 2315061036  

## Tujuan
Menerapkan workflow Git pada proyek website portofolio, mulai dari inisialisasi repository, commit bertahap, pembuatan dan penggabungan branch, hingga push ke GitHub serta pembuatan README.md sebagai dokumentasi.

## Langkah-Langkah Pengerjaan

### Langkah 1 : Konfigurasi Awal dan Inisialisasi Repository Git
- Konfigurasi username dan email Git menggunakan `git config`<br>
- Membuat folder proyek **TA-PPW-2** dan masuk ke dalamnya<br>
- Inisialisasi repository lokal dengan `git init`<br>
- Verifikasi dengan `git status`

<img width="764" height="511" alt="step 1" src="https://github.com/user-attachments/assets/60d13591-c21e-46df-8db5-1d94bef1e4c8" />


_Repository lokal bernama TA-PPW-2 berhasil dibuat dan konfigurasi Git atas nama Tri Septiani telah diatur._

---

### Langkah 2 : Commit HTML Awal
- Menambahkan file `index.html` yang berisi struktur dasar HTML website.  
- Melakukan commit pertama dengan pesan *"tambah file index.html"*.  

<img width="608" height="223" alt="step 2" src="https://github.com/user-attachments/assets/26ef8f8e-ac48-40b6-a449-669d99fe22b1" />


*Menampilkan hasil commit pertama pada terminal menggunakan perintah `git log --oneline`, menunjukkan bahwa commit berhasil dibuat pada branch master.*

---

### Langkah 3 – Commit style.css Awal
- Menambahkan file `style.css` dan folder `asset` yang berisi gambar pendukung website portofolio.  
- Melakukan commit kedua dengan pesan *"tambah file style.css"*.  

<img width="598" height="424" alt="step 3" src="https://github.com/user-attachments/assets/9726530a-1b57-4c9b-9f8a-c4f227bfc755" />


*Hasil perintah `git log --oneline` menampilkan dua commit, yaitu commit pertama untuk `index.html` dan commit kedua untuk `style.css`, menandakan proses commit bertahap telah berhasil dilakukan.*

---

### Langkah 4 : Update File HTML
- Melakukan perubahan pada file `index.html` untuk memperbarui tampilan portofolio.  
- Commit ketiga dilakukan dengan pesan *"update index.html portofolio"*.  

<img width="597" height="243" alt="step 4" src="https://github.com/user-attachments/assets/2e893979-581b-4a0a-ae7f-9702f9394f33" />


*Perintah `git log --oneline --graph` menampilkan tiga commit yaitu `index.html`, `style.css`, dan pembaruan pada file `index.html`.*

---

### Langkah 5 : Membuat dan Mengelola Branch
- Membuat branch baru bernama `feature-styling` untuk percobaan tampilan baru.  
- Melakukan perubahan pada file `style.css` di branch tersebut.  
- Commit branch dilakukan dengan pesan *"update style baru beranda dan animasi hover di projek"*.  

<img width="735" height="459" alt="step 5" src="https://github.com/user-attachments/assets/532cb687-93a3-4dbb-bd90-97919a2c784f" />


*Branch `feature-styling` digunakan untuk melakukan eksperimen styling agar tidak mengganggu branch utama.*

---

### Langkah 6 : Merge Branch ke Master
- Berpindah kembali ke branch `master` dengan `git checkout master`.  
- Menggabungkan branch `feature-styling` menggunakan perintah `git merge feature-styling`.  
- Menghapus branch `feature-styling` setelah merge selesai dengan `git branch -d feature-styling`.  

<img width="682" height="412" alt="step 6" src="https://github.com/user-attachments/assets/a9526155-da3e-4ab9-a8e0-fedc411aed70" />


*Hasil merge menunjukkan file `style.css` telah diperbarui dengan perubahan dari branch feature-styling.*

---

### Langkah 7 : Push ke GitHub
- Menambahkan remote repository GitHub dengan perintah:  
  `git remote add origin https://github.com/trisep23/TA-PPW-JUDUL2.git`  
- Melakukan push pertama ke GitHub menggunakan:  
  `git push -u origin master`  

<img width="693" height="467" alt="step 7" src="https://github.com/user-attachments/assets/2e255791-82c9-4ed7-a7ea-8eb487a512dd" />


*Proses push berhasil dan repository lokal kini terhubung dengan repository GitHub bernama `TA-PPW-JUDUL2`.*
