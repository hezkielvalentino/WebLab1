# WebLab1
## Belajar Tag Dasar HTML

### Membuat Paragraf
Attribut untuk tag paragraf adalah `<p>` dan untuk attribut tag `<title>` bergungsi untuk menembahkan judul pada paragraf

#### Hasil tampilan attribut tag paragraf

![Gambar 1](Screenshoot/output2.png)

### Memformat Teks
Attribut tag format ada beberapa attribut yang dapat digunakan pada format teks
`<b>` berfungsi untuk menebalkan teks `<u>` berfungsi untuk memiringkan teks

##### Hasil tampilan menggunakan attribut format teks

![Gambar 2](Screenshoot/output2.png)

### Menyisipkan Gambar
Untuk menyisipkan gambar pada halaman HTML simpan file gambar satu folder dengan halaman HTML atau bisa juga menyisipkan gambar dari web eksternal
buat telebih dahulu sub judul untuk gambar yang akan disisipkan dengan attribut dan untuk mengatur tinggi dan lebar gambar bisa menggunakan widht dan height

`<h3>Menambahkan Gambar</h3>`

`<img src="namafilegambar widht="ukurangambaryangdinginkan" title="judulgamabaryangakandisisipkan">`

![Gambar 1](Screenshoot/output5.png)

### Menambahkan Hyperlink
Untuk menambahkan hyperlink pada halaman HTML menggunakan attribut tag `<nav>` pertama kita buat terlebih dahulu file html baru yang ingin di direct di folder yang sama dengan pada halaman html pertama
`<nav>` 

`<a href="filehtml1">Dasar HTML</a>`

`<a href="halamanhtmlyangdidirect">Halaman 2</a>`

`<a href="http://www.google.com">Halaman Web Eksternal Google</a>`

`</nav>`

#### Hasil Tampilan attribut tag Hyperlink
![Gambar 1](Screenshoot/output3.png)

#### Hasil direct ke link yang dibuat
![Gambar 1](Screenshoot/output4.png)

#### Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag ?
2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya !
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya !
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak Berikan penjelasannya !
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut ?

#### Jawab
1. Pasti terjadi error jika ada kesalahan pada penulisan tag karena program tidak bisa memebedakan mana tag mana attribut

2. Tag paragraph `<p>` dimulai dan diakhiri dengan tag penutup `</p>` sebagai akhir dari sebuah paragraph dan akan memasuki baris baru. Sedangkan pada tag `<br/>` juga memiliki fungsi yang sama, yakni untuk membuat paragraph baru atau barisan baru.

3. `<title>` Title image adalah atribut lain yang dapat ditambahkan ke tag gambar dalam HTML. Title image ini digunakan untuk memberikan judul untuk gambar Anda. Text yang Anda masukkan di dalam tag judul tidak akan ditampilkan kepada pengguna ketika gambar tidak dapat ditampilkan. Sebaliknya, tag judul gambar ini ditampilkan saat Anda menyorot gambar dengan mouse.

    `<alt>` Alt text atau text alternatif adalah atribut yang ditambahkan ke tag gambar dalam HTML. Teks ini muncul di dalam wadah gambar ketika gambar tidak dapat ditampilkan. Ini membantu mesin pencari memahami apa isi dari gambar tersebut. Text alternatif juga sangat membantu dalam kasus gambar yang tidak ditemukan pada halaman atau gambar rusak, lihat seperti gambar dibawah ini.

4. Tidak perlu di isi semua karena jia tidak di isi program akan memabaca ukuran gambar pada format awal

5. Link Attribut Target
- `_blank` Berfungsi untuk membuka link di tab baru
- `_self` Berfungsi untuk membuka link di frame yang satu tingkat di atas frame link tersebut berada.
secara simple-nya begini :
jika di website(1) di dalamnya ada website(2) lalu di website(2) ini ada link dan kita klik, maka link akan terbuka di website(1)
- `_top` Berfungsi untuk membuka link di frame paling atas (paling luar).
secara simpel-nya :
jika di website(1) di dalamnya ada website(2) lalu di website(2) di dalamnya ada website (3) lalu di website (3) ini ada link dan kita klik, maka link akan terbuka di website(1)
- `_parent` Berfungsi untuk untuk membuka link di frame yg kita pilih
secara simpel-nya:
jika di website(1) di dalamnya ada website(2), website(3), website(4), dan seterusnya. terus kita taro link di website(1) dan kita perintah link tersebut terbuka di frame website(3) lalu kita klik linknya, maka link akan terbuka di frame website(3)

