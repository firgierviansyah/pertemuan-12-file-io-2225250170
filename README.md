# Pertemuan 12 — File Input-Output dan Penanganan Error Dasar

**Nama:** Firgi Erviansyah  
**NIM:** 2225250170 
**Kelas:** 3B

## Deskripsi
Proyek ini berisi latihan dan tugas mata kuliah Algoritma dan Pemrograman pada Pertemuan 12. Materi yang dipelajari adalah pengolahan file menggunakan Python serta penanganan error dasar.

## Tujuan
- Memahami cara menulis, membaca, dan menambahkan isi ke file teks.
- Memproses data dari file teks.
- Memahami penggunaan `try-except` untuk menangani error.
- Mengolah data nilai dan menyimpan hasil rekap ke dalam file.

## Struktur Folder

```text
pertemuan-12-file-io-NIM/
│
├── README.md
├── .gitignore
├── kuis.docx
│
├── data/
│   ├── catatan.txt
│   ├── nilai.txt
│   └── hasil_rekap.txt
│
├── latihan/
│   ├── 01_tulis_file.py
│   ├── 02_baca_file.py
│   ├── 03_append_file.py
│   ├── 04_proses_baris.py
│   ├── 05_file_not_found.py
│   └── 06_value_error.py
│
└── tugas/
    └── rekap_nilai_file.py
```

**Keterangan:** Ganti `NIM` pada nama folder dengan NIM masing-masing. File `hasil_rekap.txt` merupakan file keluaran dari program rekap nilai.

## Materi yang Dipelajari

### 1. Menulis File
Menggunakan mode `w` untuk menulis isi ke dalam file teks.

### 2. Membaca File
Menggunakan mode `r` untuk membaca isi file dan menampilkan datanya.

### 3. Menambahkan Isi File
Menggunakan mode `a` (*append*) untuk menambahkan isi tanpa mengganti data sebelumnya.

### 4. Memproses Data File
Membaca data setiap baris, memisahkan NIM dan nilai, serta mengubah nilai menjadi tipe data numerik.

### 5. Penanganan Error
Menggunakan `try-except` untuk menangani kesalahan, seperti `FileNotFoundError` ketika file tidak ditemukan dan `ValueError` ketika data tidak dapat dikonversi menjadi angka.

### 6. Rekap Nilai
Program tugas membaca data nilai, melewati baris yang tidak valid, menghitung jumlah data valid, rata-rata, nilai minimum, nilai maksimum, dan jumlah mahasiswa dengan nilai minimal 60. Hasil rekap kemudian disimpan ke dalam file `data/hasil_rekap.txt`.

## Cara Menjalankan Program

1. Pastikan Python sudah terpasang di komputer.
2. Buka terminal pada folder utama proyek.
3. Jalankan program tugas dengan perintah:

   ```bash
   python tugas/rekap_nilai_file.py
   ```

4. Periksa hasil rekap pada file `data/hasil_rekap.txt`.

## Kesimpulan
Melalui latihan dan tugas pada Pertemuan 12, saya mempelajari cara mengolah file teks menggunakan Python, memproses data dari file, serta menangani error dasar. Materi ini membantu saya memahami cara membaca data, melakukan perhitungan sederhana, dan menyimpan hasil pengolahan ke dalam file.