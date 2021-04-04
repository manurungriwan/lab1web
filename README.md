# lab1web

langkah-langkah pembuatan tag dasar html:
Buka VSCode dan buat file HTML baru. Setelah itu buat struktur dasar HTML.
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>

dan berikut outpitnya
![image](https://user-images.githubusercontent.com/56192368/113498519-ca9da100-9537-11eb-9a71-6c65c29436cf.png)

Langkah 2
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
    
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>

![image](https://user-images.githubusercontent.com/56192368/113498579-68916b80-9538-11eb-8912-03dd9a634d0d.png)


Langkah 3
Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat perbedaan lainnya.
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
 <!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>

![image](https://user-images.githubusercontent.com/56192368/113498608-a8585300-9538-11eb-8a28-a2f707bf6cd1.png)


Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>

berikut out put nya pda firefox:

![image](https://user-images.githubusercontent.com/56192368/113498635-d2aa1080-9538-11eb-99af-a262eb6576b4.png)


LANGKAH 4
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

![image](https://user-images.githubusercontent.com/56192368/113498640-e81f3a80-9538-11eb-9f30-58100ca8419f.png)

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo_upb.png" width="200" title="Logo Univeritas Pelita Bangsa">

untuk mengetahui hasilnya kita refresh lagi firefoxnya:

![6 6](https://user-images.githubusercontent.com/56192368/113498685-5c59de00-9539-11eb-9c8a-df9b7ef0fe93.PNG)


LANGKAH 6
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>  

jangan lupa selalu kita save di vs code nya supaya saat kita refresh lagi dapat memperoleh perubahannya.

![image](https://user-images.githubusercontent.com/56192368/113498714-c2466580-9539-11eb-86bc-9c33266ded55.png)

##LANGKAH 7 Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakan Hyperlink.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>tag html DASAR</title>
</head>
<body>
    
    <h1>SELANJUTNYA Halaman Ke 2</h1>

    <img src="RIWAN.png" width="200" title="Logo Univeritas Pelita Bangsa">

<p align="justify">RIWAN IROSUCIPTO MANURUNG</p>
<p align="justify">311910500</p>
<p align="justify">TI.19.C.1</p>

</body>
</html>

![image](https://user-images.githubusercontent.com/56192368/113498730-e6a24200-9539-11eb-80cd-56476f85019a.png)



##JAWAB PERTANYAAN

1.	Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

Ya ada, huruf besar dan kecil pun sangat berpengaruh.
2.	Apa perbedaan dari tag 
dengan tag ,berikan penjelasannya!

Pada hasil praktik yang saya lakukan, perbedaan  tag <p> jarak enter nya tidak terlalu jauh, sedangkan tag <br> jarak enter nya lebih jauh 1 line dari tag <p>.

3.	Apa perbedaan atribut title dan alt pada tag  , berikan penjelasannya!

Ketika gambar di tampilkan akan terlihat sebuah title. sedangkan, jika gambar gagal ditampilkan akan menampilkan teks atribut alt.

4.	Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

kedua atribut harus di isi semua, karena jika hanya salah satunya maka gambar tersebut akan terlihat terlalu lebar atau tinggi.

5.	Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

Menambah hyperlink baru dan menampilkan yg telah di tentukan, untuk blank akan menambah tab



