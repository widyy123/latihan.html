saya membuat sebuah web yang berisikan data pribadi, yang dibuat menggunakan html. kode-koded tersebut saya dapatkan dari praktikum dan juga w3schools, penjelasan kodenya antara lain:
1. Heading
   disini kode yang saya gunakan seperti <h2>About Me~</h2>. Pada kode ini, saya akan membuat sebuah kalimat yang berisikan kata About Me~ dengan tipe hurufnya yang h2.
   
3. Table
     <table border="1">
  <tr>
    <th>Nama</th>
    <td>Widya Rustri Pratiwi</td>
  <tr>
 <tr>
    <th>NPM</th>
    <td>G1A024059</td>
 <tr>
 <tr>
    <th>Usia</th>
    <td>19 tahun</td>
  <tr>
<tr>
    <th>Institusi</th>
    <td>Universitas Bengkulu</td>
  <tr>
<tr>
    <th>Alamat</th>
    <td>Bengkulu Utara, Bengkulu</td>
  <tr>
</table>
itu adalah contoh dari penggunaan table. jika menggunakan kode td maka tulisannya tidak akan bercetak tebal, tetapi jika menggunakan th maka tulisan tersebut akan bercetak tebal. table yang saya gunakan juga bordernya 1.

3. <hr>
saya menggunakan <hr> untuk memisahkan antar kalimat, dimana nanti akan terdapat garis yang memisahkannya.

4. <br>
<br> digunakan untuk memisahkan atau memberi jarak antar kalimatnya saja. 

5. img
saya menambahkan gambar melalui link gambarnya itu. gambar nya juga sudah saya beri ukuran 200px, yaitu width nya 200px dan heightnya 200px. contoh kodenya:
  <img src="https://teknogram.id/gallery/foto-profil-wa/lucu/pp-wa-kosong-lucu-7.jpg" alt="my Profile" width="200px" height="200px">

6. ul dan ol
saya menggunakan ul dan juga ol untuk membuat sebuah kalimat yang memiliki simbol ataupun angka didepannya, yang dapat menunjukkan pilihan. contoh kodenya:
         <ul type="Bahasa Pemrograman">
        <li>HTML</li>
    </ul>

    <h3>Hobi</h3>
    <ol type="Hobi">
        <li>Olahraga</li>
        <li>Bermain Game</li>
        <li>Ngoding</li>
    </ol>

7. form
   saya menggunakan form untuk menambahkan suatu kalimat, dimana ada label (menandai) dan input (memasukkan). contoh kodenya ini: 
   <hr>
 <h2>Contact Me~</h2>
 <form action="">
        <label form="">Nama:</label>
        <br>
        <input type="text">
<br>
        <label form="">Email:</label>
    <br>
        <input type="email">
<br>
        <label form="">Pesan:</label>
    <br>
        <input type="pesan">
        
        <br>
        <br>
        <button>Kirim</button>
<br>
</table>

jadi, berdasarkan hal tersebut, maka akan menghasilkan sebuah profil seperti:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Widya</title>

    <h1>Welcome To My Profile!</h1>
    <img src="https://teknogram.id/gallery/foto-profil-wa/lucu/pp-wa-kosong-lucu-7.jpg" alt="my Profile" width="200px" height="200px">
    <h2>~Hi! I'm Widya Rustri Pratiwi~</h2>
    <h3>A student who is passionate about the world of technology and programming.</h3>

<hr>
 <h2>About Me~</h2>
     <h3>I am an individual who is passionate about the world of technology. Here is a brief summary about me:</h3>

    <table border="1">
  <tr>
    <th>Nama</th>
    <td>Widya Rustri Pratiwi</td>
  <tr>
 <tr>
    <th>NPM</th>
    <td>G1A024059</td>
 <tr>
 <tr>
    <th>Usia</th>
    <td>19 tahun</td>
  <tr>
<tr>
    <th>Institusi</th>
    <td>Universitas Bengkulu</td>
  <tr>
<tr>
    <th>Alamat</th>
    <td>Bengkulu Utara, Bengkulu</td>
  <tr>
</table>
<br>

<hr>
 <h2>Keahlian~</h2>
  <h3>Bahasa Pemrograman</h3>
      <ul type="Bahasa Pemrograman">
        <li>HTML</li>
    </ul>

    <h3>Hobi</h3>
    <ol type="Hobi">
        <li>Olahraga</li>
        <li>Bermain Game</li>
        <li>Ngoding</li>
    </ol>

<hr>
 <h2>Contact Me~</h2>
 <form action="">
        <label form="">Nama:</label>
        <br>
        <input type="text">
<br>
        <label form="">Email:</label>
    <br>
        <input type="email">
<br>
        <label form="">Pesan:</label>
    <br>
        <input type="pesan">
        
        <br>
        <br>
        <button>Kirim</button>
<br>
</table>

<hr>
<h5>@2026Widya Rustri Pratiwi</h5>
<h5>Kunjungi:</h5> 
<a href="http://Instagram.com">Instagram</a> 
<a href="http://GitHub.com">GitHub</a>    
</body>
</html>
