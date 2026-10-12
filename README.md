# Pertemuan 07 Fungsi Python

Nama: Fridha Septiana  
NIM: 2225250068  
Kelas: 3E

## Tujuan

Menggunakan fungsi, parameter, nilai return, dan scope untuk membuat program Python yang modular. Program ini menyediakan beberapa operasi matematika, yaitu menghitung luas persegi panjang, luas segitiga, jumlah bilangan dari 1 sampai n, dan faktorial.

## Cara Menjalankan

1. Buka folder proyek di VS Code.
2. Buka terminal melalui menu **Terminal → New Terminal**.
3. Jalankan perintah berikut:

   `python3 praktik/utilitas_matematika.py`

   Jika perintah tersebut tidak berhasil di Windows, gunakan:

   `python praktik/utilitas_matematika.py`

4. Pilih operasi matematika melalui menu yang ditampilkan.
5. Masukkan angka sesuai instruksi program.
6. Pilih menu 5 untuk mengakhiri program.

## Struktur Fungsi

1. **`luas_persegi_panjang(p, l)`**  
   Menerima parameter `p` sebagai panjang dan `l` sebagai lebar. Fungsi mengembalikan hasil perkalian panjang dan lebar sebagai luas persegi panjang.

2. **`luas_segitiga(a, t)`**  
   Menerima parameter `a` sebagai alas dan `t` sebagai tinggi. Fungsi mengembalikan hasil perhitungan luas segitiga menggunakan rumus ½ × alas × tinggi.

3. **`jumlah_n(n)`**  
   Menerima parameter `n` berupa bilangan bulat nonnegatif. Fungsi menggunakan perulangan untuk menjumlahkan bilangan dari 1 sampai n, kemudian mengembalikan hasil penjumlahan.

4. **`faktorial(n)`**  
   Menerima parameter `n` berupa bilangan bulat nonnegatif. Fungsi menggunakan perulangan untuk menghitung perkalian bilangan dari 1 sampai n dan mengembalikan hasil faktorial. Faktorial 0 menghasilkan nilai 1.

5. **`tampilkan_menu()`**  
   Tidak menerima parameter dan tidak mengembalikan nilai. Fungsi menampilkan daftar pilihan operasi matematika kepada pengguna.

6. **Program utama**  
   Menggunakan perulangan `while` untuk menampilkan menu dan menerima pilihan pengguna. Program memanggil fungsi sesuai pilihan, menampilkan hasil perhitungan, serta memeriksa input bilangan untuk operasi jumlah dan faktorial.

## Hasil Pengujian

| No. | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| 1 | Panjang = 8, lebar = 5 | 40 | 40 | Berhasil |
| 2 | Alas = 10, tinggi = 6 | 30.0 | 30.0 | Berhasil |
| 3 | Jumlah bilangan, n = 10 | 55 | 55 | Berhasil |
| 4 | Faktorial, n = 5 | 120 | 120 | Berhasil |
| 5 | Faktorial, n = 0 | 1 | 1 | Berhasil |

## Refleksi

Setelah program dipisahkan menjadi beberapa fungsi, perhitungan menjadi lebih sederhana dan mudah dipahami. Setiap fungsi memiliki tugas masing-masing sehingga kode tidak perlu ditulis berulang kali. Contohnya, fungsi `faktorial(n)` dapat digunakan untuk menghitung faktorial dari berbagai bilangan dengan memanggil fungsi yang sama dan memberikan nilai parameter yang berbeda. Selain itu, penggunaan `return` memungkinkan hasil perhitungan dikembalikan dan digunakan oleh bagian program lainnya.
