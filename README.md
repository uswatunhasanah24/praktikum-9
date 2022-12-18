### PRAKTIKUM 9
### USWATUN HASANAH
### 312210343
### TI.22.A3
### CONTOH DAN PENJELASAN MODUL PRAKTIKUM 13 (PERTEMUAN 13)
Contoh dalam bentuk foto dan penjelasan dalam bentuk tulisan

### PENJELASAN KE- 1

![s1](https://user-images.githubusercontent.com/115516474/208296739-2979c109-d2a3-4e7a-98f2-4e69dfec3871.png)

gambar di atas adalah fungsi yang mengubah suhu dari derajat kelvin ke derjat fahrenheit. Karena 0 derajat kelvin sedingin yang didapat, ketika kode seperti 
gambar di atas dijalankan, maka muncul exception yang bernama Traceback AssertionError artinya terjadi error pada pertanyaan assert. 


### PENJELASAN KE- 2

![s2](https://user-images.githubusercontent.com/115516474/208296760-b205b528-541a-400d-be45-1d9e13f29863.png)

Contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah. Maka menghasilkan hasil berikut.
```
Written content in the file successfully
```

dan kenapa hasilnya seperti itu? karena else akan dijalankan ketika try adalah True


### PENJELASAN KE- 3

![s3](https://user-images.githubusercontent.com/115516474/208296768-43df195f-55aa-43fd-abee-7effc4fdaddc.png)

m
engapa muncul eror?

```
Error: can't find file or read data
```
r adalah read - membuka file untuk membaca, eror jika tidak ada. Dsini ingin membaca file bukan menulis maka dibawahnya `fh = oprn("testfile", "r")`
tambahkan `print(fh.readline())` dan fh.write di hapus. Setelah dijalankan try dan else ditampilkan


### PENJELASAN KE- 4

![s4](https://user-images.githubusercontent.com/115516474/208296775-fcb1613f-cb39-4a25-a31c-e50a10c019a6.png)

Menghasilkan output:

```Error: can\'t find file or read data```

Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.

### PENJELASAN KE- 5

![s5](https://user-images.githubusercontent.com/115516474/208296781-63599332-ecf0-4a6b-a577-45a2647a1fce.png)

ketika dijalankan, maka muncul error. Hapus `#!/usr/bin/python` dan di `except ValueError, Argument:` ganti koma dengan 
as seperti `except ValueError as Argument:` agar tidak error. Jika dijalankan akan muncul error lagi

```
The argument does not contain numbers
invalid literal for int() with base 10: 'xyz'
```

kenapa? karena parameter def temp_convert harus mengandung angka.

### PENJELASAN KE- 6

![s6](https://user-images.githubusercontent.com/115516474/208296791-face1e31-9568-4c3d-85e4-56a4a63a36a3.png)

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada `raise "Invalid level!",` level ganti tanda koma dengan tanda plus. 
Cetak def dengan angka yang lebih besar dari 1.
