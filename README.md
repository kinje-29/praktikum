# Tutorial lab1 dan lab2


# BIODATA

## Tutorial membuat biodata dengan program Python dan cara install python di linux/Ubuntu

1. Pertama kita buka terminal lalu ketikan code berikut
    `sudo apt install python`
2. Untuk verifikasi instalasi kita ketik code berikut
    `python --version`
    Maka akan muncul
    `Python 2.7.17`
    Python pun telah ter install pada sistem linux/ubuntu anda.

## cara install IDE Spyder di linux

1. pertama buka **software manager**
 ![1data.png](/gambar/1data.png)
2. kemudian cari **IDE Spyder**
 ![3data.png](/gambar/3data.png)
3. Kemudin intsall "tunggu hingga beres"

## langkah membuat bidoata dengan Python

1. buka Spyder yang telah kita install
2. maka tampilan akan seperti berikut

    ![4.png](/gambar/4.png)

3. kemudian **save as** di folder yang kamu inginkan.

    ![5.png](/gambar/5.png)
 
4. lalu ketikan code seperti gambar dibawah ini

    ![6lab.png](/gambar/6lab.png)

5. setelah code yang telak kamu tulis benar selanjut nya klik `RUN atau kalian bisa klik F5`
    maka akan seperti gambar berikut

    ![7.png](/gambar/7.png)


# keterangan
1. `float` = menyatakan bilangan yang mempunyai koma
2. `Boolean` = Menyatakan benar `true` yang bernilai `1`, atau salah `false` yang bernilai `0`
3. `string` = Menyatakan karakter/kalimat bisa merupakan angka, dll (diapit tanda `"` atau `'`
4. `Integer` = Menyatakan bilangan bulat
5. `Hexadecimal` = Menyatakan bilangan dalam format heksa (bilangan berbasis 16) `9a atau 1d3`
6. `Complex` = Menyatakan pasangan angka real dan imajiner `1 + 5`
7. `List` = Data untaian yang menyimpan berbagai tipe data dan isinya bisa diubah-ubah ` ['xyz', 786, 2.23]`
8. `Tuple` = data untaian yang menyimpan berbagai tipe data tapi isinya tidak bisa diubah ` ['xyz', 786, 2.23]`
9. `Dictionary` = data untaian yang menyimpan berbagai tipe data berupa psangan penunjuk dan nilai `{'nama': 'firman','id':1}` 





# oprator

## Pengenalan

1. **Tipe Data** Tipe data adalah suatu media atau memori pada komputer yang digunakan untuk menampung informasi
2. **Variable** Variable merupakan tempat menyimpan data, sedangkan tipe data adalah jenis data yang tersimpan dalam Variable.
3. **Operator** Oprator adalah simbol khusus pada Python yang melakukan perhitungan aritmatika atau logika.

## langkah langka pembuatan Praktikum lab2

1. fungsi `eval()` sering digunakan untuk mengevaluasi input dari user. Kita tahu bahwa input dari user via keyboard hasilnya adalah string walaupun yang kita input adalah bilangan. fungsi `eval()` akan menentukan tipe data yang sesuai untuk kita. Contohnya seperti gambar di bawah ini:
![1tugas.png](/gambar1/1tugas.png)
 
2. Fungsi `input()` berfungsi untuk menerima baris input dari user dan mengembalikannya dalam bentuk string. sedangkan Fungsi `format()` berfungsi untuk melakukan pengaturan *format string* yang akan dicetak atau ditampilkan ke dalam *monitor*.
Contoh seperti gambar di bawah ini
![2.png](/gambar1/2.png) 

3. Fungsi `int() `berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat `(integer)`. Fungsi `print()` berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
![3.png](/gambar1/3.png)

4. bila hasil kita jalankan denngan mengklik `RUN` makan akan menghasilkan seperti gambar di bawah ini

![4.png](/gambar1/4.png)


- Kurung kurawal {} digunakan sebagai placeholder.
- Kita bisa menentukan urutan yang dicetak dengan menggunakan angka (tuple index).
- Untuk mengambil input menggunakan fungsi `input()` 
- `input()` untuk mengambil nilai sesuai Variablenya.
- Untuk menghasilkan dari hasil yang telah kita *input* maka menggunakan sebuah fungsi `print()` yang nanti nya akan    menampilkan pada layar monitor. 
- angka dari 1 dan 0 disebut *operand*, sedangkan tanda *+* adalah operator.
