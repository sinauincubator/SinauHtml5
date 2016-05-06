![](/img/sinaulogo.jpeg)
# 				TABLE
    
    tutorial kali ini kita akan membuat table di web kita 
    tampilan pertama yang akan kita buat adalah seperti di bawah:
   
   <html>
    <head>
  <title>BelajarHtml5</title>      
    </head>
    <body>
        <table style="width:100%">
            <tr>
                <td>ashari</td>
                <td>muklis</td>
                <td>19</td>
            </tr>
            <tr>
                <td>yusuf</td>
                <td>kala</td>
                <td>17</td>
            </tr>
            <tr>
                <td>bambang</td>
                <td>gentolet</td>
                <td>22</td>
            </tr>
        </table>
                
    </body>
</html>


    di bawah adalah source codenya
    
```html
<!DOCTYPE html>
<html>
    <head>
  <title>BelajarHtml5</title>      
    </head>
    <body>
        <table style="width:100%">
            <tr>
                <td>ashari</td>
                <td>muklis</td>
                <td>19</td>
            </tr>
            <tr>
                <td>yusuf</td>
                <td>kala</td>
                <td>17</td>
            </tr>
            <tr>
                <td>bambang</td>
                <td>gentolet</td>
                <td>22</td>
            </tr>
        </table>
                
    </body>
</html></html>
```
table di definisikan dengan`<table>`

Tabel dibagi menjadi baris tabel dengan tag `<tr>`.

Baris tabel dibagi menjadi data tabel dengan `<td>` tag.

Sebuah baris tabel juga dapat dibagi menjadi judul tabel dengan `<th>`tag.

**selanjutnya kita akan menambahkan garis border di table**

kita akan menyambungkan dengan style.css kita  pada tutorial sebelumnya sudah saya jelaskan menghubungkan html ke css. nah di css kita akan membuat bordernya dengan sorce code seperti ini:
```css
table, th, td{
    border: 1px solid black;
    border-collapse: collapse;
}
th,td{
    padding: 15px;
}
```
	setelah kita save dan kita jalankan index.html maka akan muncul tampilan seperti ini:
![](/home/aska/Dokumen/tutorial/img/scr2.png)

penjelasan:

border adalah untuk memberikan efek garis tepi di sini saya set 1px


border-collapse: adalah untuk membuat menjadi model collapse 

setelah itu saya juga membuat jarak antara colom jadi lebih lebar di situ yang saya set adalah untuk th, dan td.

**Step Selanjutnya membuat kolom kategori table **

tampilan yang akan kita buat seperti ini:
![](/home/aska/Dokumen/tutorial/img/scr3.png)

pertama kita buat untuk kategori tablenya dulu

masukan source code di bawah ke index.html

```html
			<tr>
                <th>NAMA PERTAMA</th>
                <th>NAMA AKHIR</th>
                <th>UMUR</th>
            </tr>


```

setelah itu kita set agar teks kolom kategori agar rata kiri , memberi warna hitam di table kolom kategori , merubah warna garis di kolom kategori
source kode:

```
th{
    text-align: left;
    border: 1px solid white;
    border-collapse: collapse;
    padding: 15px;
    background-color: black;
    color: white;
}

```
setelah itu kita save dan jalankan index.htmlnya ....

**SELANJUTNYA KITA BUAT SEL YANG MENCAKUP 2 KOLOM**

buka index.htmlnya lalu isikan code berikut di table row di bagian table hader `<th colspan="2">TELEPON</th>` lalu tambahkan beberapa data di table row table data
sehoingga code index.htmlnya seperti ini:
```html
<table style="width:100%">
            <tr>
                <th>NAMA PERTAMA</th>
                <th>NAMA AKHIR</th>
                <th>UMUR</th>
                <th colspan="2">TELEPON</th>
            </tr>
            <tr>
                <td>ashari</td>
                <td>muklis</td>
                <td>19</td>
                <td>021 000 9999</td>
                <td>085 000 777 888</td>
            </tr>
            <tr>
                <td>yusuf</td>
                <td>kala</td>
                <td>17</td>
                <td>021 000 2222</td>
                <td>085 000 666 888</td>
            </tr>
            <tr>
                <td>bambang</td>
                <td>gentolet</td>
                <td>22</td>
                <td>021 000 5555</td>
                <td>085 000 444 888</td>
            </tr>
        </table>
```

setelah itu di save dan jalankan index.htmlnya

akan muncul tampilan seperti ini:

![](/home/aska/Dokumen/tutorial/img/scr4.png)

**SEKIAN TUTORIAL KALI INI**

semoga bermanfaat dan dapat di pahami  

#SINAU_ACADEMY
#SINAU_RnD
#TIM_ADMIN_GANTENG
#SINAU_HTML5
#Table_Step