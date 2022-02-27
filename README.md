# Tugas Kecil 2 IF2211 Strategi Algoritma
### Pembuatan Convex Hull Dengan Algoritma Divide and Conquer

Dibuat Oleh : William Manuel Kurniawan <br>
NIM : 13520020 <br>
Bahasa Pemrograman : Python <br>

## Deskripsi

Program ini menggambarkan convex hull dari sebuah dataset berisi koordinat titik. Program tidak menerima input dari pengguna karena dataset yang digunakan sudah langsung diambil dari library scikit-learn. 

## Kebutuhan

- Windows
- Jupyter Notebook
- Python (Anaconda)

## Cara Menjalankan Program
### 1. Buka Folder Program Pada Jupyter Notebook

Gunakan Command Prompt atau Windows Powershell dan pergi ke lokasi folder repository disimpan lalu ketik perintah berikut :
  
  ```bash
  jupyter notebook
  ```
  
Komputer akan membuka jupyter notebook berisi file dan folder yang berada dalam folder repository.

### 2. Jalankan File convexhull.ipynb

Di dalam jupyter notebook, klik folder src dan klik pada file convexhull.ipynb . <br><br>
Setelah file dibuka, klik tombol run di bagian atas layar.

## Masalah Ketika Menjalankan Program

### Melakukan Instalasi Tertentu
Untuk menjalankan program, ada beberapa library atau program yang harus melakukan instalasi terlebih dahulu. Untuk melakukan instalasi tersebut, dapat menggunakan pip atau menggunakan Anaconda Prompt yang didapatkan setelah melakukan instalasi Anaconda. Berikut adalah cara instalasi pip dan Anaconda :
- pip : https://phoenixnap.com/kb/install-pip-windows
- Ananconda : https://www.anaconda.com/products/individual

### Jupyter Notebook Tidak Jalan
Jika jupyter notebook tidak jalan, ada kemungkinan jupyter belum ada. Untuk melakukan instalasi jupyter, gunakan perintah berikut :
  ```bash
  pip install jupyter
  ```
### Library Tidak Ditemukan
Jika ada library yang tidak ditemukan ketika menjalankan program, ada kemungkinan harus dilakukan instalasi untuk library tersebut terlebih dahulu. Untuk mengunduh semua library yang dibutuhkan untuk menjalankan program, gunakan perintah berikut :
  ```bash
  pip install numpy
  pip install pandas
  pip install matplotlib
  pip install sklearn
  ```
Instalasi juga dapat dilakukan menggunakan Anaconda prompt dengan perintah berikut :
  ```bash
  conda install numpy
  conda install pandas
  conda install matplotlib
  conda install sklearn
  ```
  
### Catatan Tambahan : Mengecek Versi Python Yang Digunakan
Pastikan versi Python yang digunakan Anaconda ada dalam system variable komputer. Penggunaan versi yang salah dapat menyebabkan masalah ketika menjalankan program.

## Catatan Tambahan : Menjalankan Program di Visual Studio Code
File convexhull.ipynb juga dapat dijalankan langsung pada VSCode dengan tahap berikut :
1. Buka file convexhull.ipynb pada VSCode.
2. Pilih interpreter yang benar dengan menekan tombol (Ctrl + Shift + P) dan memilih versi python yang digunakan Anaconda. 
3. Klik tombol run yang biasa berada di sebelah kiri awal sel yang memuat program.
