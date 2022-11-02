Nama : Frans Putra Sinaga

Nim : 312210046

Kelas : TI.22.A1

Latihan Python di Pycharm
DAFTAR ISI
No 	Description 	Link
1 	Cara Installasi Pycharm 	Click Here
2 	Latihan 1 	Click Here
3 	Latihan 2 	Click Here
4 	Latihan 3 	Click Here
5 	Menghitung Luas Dan Keliling Lingkaran 	Click Here
6 	Flowchart Menghitung luas dan keliling lingkaran 	Click Here
Cara Installasi Pycharm

    Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows , Dan anda pilih yang Community Screenshot (76)
    Anda next saja semua perintahnya
    Jika sudah selesai maka program siap di gunakan

Cara Menjalankan Pycharm
Latihan 1

    Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini Screenshot (78) Screenshot (77)

    Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan Screenshot (79) Screenshot (80)

    anda masukan code dari latihan1 anda lalu Run

# penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')

# penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')

# string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

# string format
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
print('{0:>3} {1:>16}'.format(10, 10**10)

Screenshot (63) Screenshot (64)

Hasil run Screenshot (61) Screenshot (62)
Latihan 2

    Anda masukan code latihan 2 anda lalu Run

a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

#koversi nilai variable
a=int(a)
b=int(b)
print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%s".format(a,b) %(a/b))

Screenshot (68) Hasil Run Screenshot (69)
Latihan 3

    Anda masukan code seperti dibawah ini dan lalu Run

string = ""

x = int(input("Masukkan angka :"))
bar = x
# Looping Baris
while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri		
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1		
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1	

	string = string + "\n\n"
	bar = bar - 1

bar = 1	
# Looping Baris
while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri	
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1	
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri	
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
print (string)

Screenshot (71) Screenshot (72)

Hasil Run Screenshot (70)
Menghitung Luas Dan Keliling Lingkaran

    Masukan code di bawah ini lalu run

import math

r = float(input("Masukan Jari-jari : "))

luas = math.pi * (r * r)
keliling = 2 * math.pi * r

print("Luas Lingkaran \t\t= ", luas)
print("Keliling Lingkaran\t= ", keliling)

Screenshot (82)

Hasil Run Screenshot (81)
Flowchart Menghitung luas dan keliling lingkaran

Flowchart menghitung luas dan keliling lingkaran

Terima Kasih
