# TIPE-DATA-VARIABLE-DAN-OPERATOR
Nama: HARIS ADRIANSYAH

Kelas: TI.24.A4

NIM: 312410286

Matkul: Bahasa Pemrograman

LATIHAN1
gambar

#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')
Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. secara default penggunaan end adalah untuk ganti baris.

print('A', end='')
print('B', end='')
print('C', end='')
Penggunaan print () digunakan untuk mencetak output, seperti syntax dibawah ini :

print()
Syntax dibawah ini digunakan untuk menampilkan output berupa string

print('X')
print('Y')
print('z')
Hasil dari source code tersebut seperti gambar dibawah ini :

gambar

Penggunaan separator Pendeklarasian beberapa variable beserta nilainya

w,x,y,z=10,15,20,25
Menampilkan hasil dari variable tiap-tiap variable

print(w,x,y,z)
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah : (koma)

print(w,x,y,z,sep=",")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah

print(w,x,y,z,sep="")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah : (titik dua)

print(w,x,y,z,sep=":")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah -----

print(w,x,y,z,sep="-----")
hasil dari syntax / source code diatas adalah seperti berikut ini :

gambar

LATIHAN 2
gambar

a=int(input("masukkan nilai a:"))
b=int(input("masukkan nilai b:"))
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
Kita akan coba lagi untuk run file tersebut, maka akan muncul seperti gambar dibawah ini :

gambar

String Format String formatting atau pemformatan string memungkinan kita menyuntikkan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation. Penggunaan source code yang di berikan oleh dosen seperti berikut :

gambar

#string format 1
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

#string format 2
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
String Format 1 Pada syntax / source code strring format satu akan menampilkan output berupa 2 outputan. Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat. Dengan ketentuan sebagai berikut, Operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] ) Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10, dengan output sebagai berikut :

gambar

2 * String Format 2* Pada syntax atau source code string format dua akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri ) Dengan ketentuan sebagai berikut :

secara Default, .format() menggunakan rata kiri, angka ke kanan. kita dapat menggunakan opsi opsional <,^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan .format() sebagai berikut :

gambar

Untuk hasil dari String Format 2 adalah :

Tugas Latihan
gambar

Flowchart Bilangan terbesar dari 3 buah bilangan
gambar

Program bilangan terbesar dari 3 buah yg di inputkan
gambar melalui pernyataan kondisi if-else, program membandingkan bilangan pertama dengan bilangan kedua dan ketiga, dan seterusnya

Hasil output

gambar

untuk meminta pengguna memasukan tiga bilangan

Flowchart Bilangan terbesar dari N bilangan
gambar

Program bilangan terbesar N
gambar setiap angka yang diinputkan diperiksa apakah lebih besar dari angka terbesar yang saat ini disimpan

Hasil output

gambar

jika pengguna memasukan angka 0, program akan memberi tahu bahwa tidak ada bilangan yang dimasukkan dan tidak dapat melanjutkan untuk meminta bilangan selanjutnya
