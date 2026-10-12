Repository ini berisi latihan dasar Python sebagai bagian dari tugas/praktikum pemrograman. Program yang tersedia memperkenalkan penggunaan input, output, variabel, konversi tipe data, serta pembuatan tabel sederhana di terminal menggunakan pustaka rich.
Daftar File
File	Deskripsi
halo.py	Meminta nama dan umur pengguna, kemudian menampilkan pesan sapaan serta perkiraan umur tahun depan.
tampil.py	Menampilkan tabel berisi daftar alat praktikum dan fungsinya menggunakan pustaka rich.
requirements.txt	Daftar pustaka Python yang diperlukan oleh proyek.
.venv/	Lingkungan virtual Python lokal (umumnya tidak perlu diunggah ke repository).


Persyaratan
- Python 3
- pip untuk memasang pustaka yang dibutuhkan
Cara Menjalankan
1. Unduh repository
git clone https://github.com/kipeng34/Tugas-PBO-Stipen-GUltom.git
cd Tugas-PBO-Stipen-GUltom
2. (Opsional) Buat dan aktifkan lingkungan virtual
Windows:
python -m venv .venv
.venv\Scripts\activate
Linux/macOS:
python3 -m venv .venv
source .venv/bin/activate
3. Pasang dependensi
python -m pip install -r requirements.txt
4. Jalankan program
Untuk menjalankan program sapaan:
python halo.py
Program akan meminta nama dan umur. Masukkan nama, lalu umur dalam bentuk angka.
Untuk menampilkan tabel alat praktikum:
python tampil.py
Program akan menampilkan tabel berisi nama alat dan fungsi masing-masing.
Penjelasan Singkat Program
halo.py
Program ini menggunakan input() untuk menerima nama dan umur pengguna. Fungsi int() mengubah masukan umur menjadi bilangan bulat, sedangkan print() menampilkan hasil. F-string digunakan untuk menyisipkan nilai variabel ke dalam teks.
tampil.py
Program ini menggunakan Console dan Table dari pustaka rich untuk membuat tabel yang lebih rapi di terminal. Kolom tabel berisi nomor, alat, dan fungsi alat.
Tujuan Pembelajaran
- Memahami masukan dan keluaran dasar pada Python.
- Menggunakan variabel dan konversi tipe data.
- Memahami penggunaan pustaka eksternal melalui pip.
- Menampilkan data dalam bentuk tabel pada terminal.
Catatan
Isi README ini disusun berdasarkan file yang tersedia di repository. Walaupun repository diberi nama tugas PBO, file yang terlihat saat ini merupakan latihan dasar Python dan belum menunjukkan penerapan kelas serta objek secara eksplisit.
Repository
https://github.com/kipeng34/Tugas-PBO-Stipen-GUltom
