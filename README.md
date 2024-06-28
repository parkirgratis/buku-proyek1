# Website informasi parkir gratis bandung 

## DAFTAR ISI 
### KATA PENGANTAR
### PRAKATA
### DAFTAR ISI
### DAFTAR GAMBAR
### BAB I PENGENALAN WEBSITE PARKIR GRATIS
### 1.1 Apa itu Website parkir gratis
### 1.2 Tujuan dan manfaat Website parkir gratis
### BAB II BAHASA DAN APLIKASI YANG DIGUNAKAN SERTA PENGINSTALANNYA
### 2.1 Bahasa pemrograman yang digunakan
### 2.1.1 HTML
### 2.1.2 CSS
### 2.1.3 JAVASCRIPT
### 2.1.4 CSS SKELETON / GETSKELETON
### 2.1.5 NODE JS
### 2.1.6 Golang
### 2.2 Aplikasi yang digunakan
### 2.1 Visual Studio Code
### 2.2 Mongodb
### 2.3 Instalasi aplikasI
### 2.3.1 Visual studio code
### BAB III	PERANCANGAN APLIKASI

### KATA PENGANTAR

Segala puji bagi Allah, Tuhan Yang Maha Esa atas karunia dan rahmat-Nya sehingga penulis dapat menyelesaikan buku ini. Sholawat serta salam semoga senantiasa tercurahkan kepada Nabi Besar Muhammad SAW.
Kami ucapkan juga rasa terima kasih kami kepada pihak-pihak yang mendukung lancaranya pembuatan buku ini mulai dari proses penulisan hingga proses cetak, yaitu orang tua kami, pembimbing kami, rekan-rekan kami, dan masih banyak lagi yang tidak bisa kami sebutkan satu per satu.
Adapun, buku kami yang membahas tentang Sistem Informasi Parkir Gratis ini telah selesai kami buat semaksimal dan sebaik mungkin agar menjadi manfaat bagi pembaca yang membutuhkan informasi dalam mengembangkan sistem informasi parkir gratis pada map yang efisien dan ekonomis.
Kami sadar, masih banyak kekeliruan yang tentu saja jauh dari sempurna dalam buku ini. Oleh karena itu, kami mohon agar pembaca memberi kritik serta saran terhadap buku ini agar kami dapat terus meningkatkan kualitasnya. Demikian buku ini kami buat, dengan harapan agar pembaca dapat memahami informasi mengenai sistem informasi parkir gratis dan mendapatkan wawasan yang bermanfaat bagi masyarakat luas Terima kasih.

### PRAKATA

Pada era teknologi yang terus berkembang, teknologi telah masuk ke berbagai aspek kehidupan kita, termasuk cara kita mengelola fasilitas umum seperti parkir. Salah satu inovasi yang semakin populer adalah sistem informasi parkir gratis berbasis peta open street map, yang membuat mencari dan mengelola informasi parkir gratis lebih mudah dan lebih fleksibel.
Sistem informasi parkir gratis ini menggabungkan teknologi internet dengan manajemen parkir. Dalam hal ini, pengguna dapat menggunakan web untuk menemukan parkir gratis di berbagai lokasi. Informasi ini terdapat lokasi tempat parkir pada map di marker yang sudah dibuat dan lokasi sudah di survei sebelum memasukan data pada map.
Tujuan dari buku ini adalah untuk memberikan petunjuk tentang cara membuat sistem informasi parkir gratis berbasis peta digital yang mudah diakses oleh masyarakat. Buku ini disusun dengan cara yang mudah diikuti oleh pembaca pemula, dan setiap bagian memiliki penjelasan rinci yang disertai dengan gambar dan contoh kode program.
Kami berharap pembaca yang tertarik untuk membangun sistem serupa dapat menggunakan buku ini sebagai sumber inspirasi dan panduan praktis. Anda dapat mengakses semua kode program yang disajikan dalam buku ini melalui tautan berikut: https://github.com/parkirgratis/parkirgratis.github.io


## BAB 1 PENGENALAN WEBSITE PARKIR GRATIS<br/>

### 1.1  Apa itu Website parkir gratis <br/>

Website parkir gratis yang di tampilkan pada peta open street map ini menampilkan informasi tentang lokasi-lokasi parkir gratis pada minimarket di daerah bandung. dengan adanya website ini pengguna dapat menemukan lokasi parkir gratis dengan mudah dan menghemat biaya parkir.<br/>

### 1.2  Tujuan dan manfaat Website parkir gratis <br/>

Website parkir gratis ini memudahkan pelanggan minimarket mengetahui lokasi-lokasi yang terdapat fasilitas parkir gratis dan fasilitas lainnya. sehingga pengguna tidak perlu khawatir tentang biaya tambahan pada parkir. dengan menggunakan website ini pelanggan dapat menikmati pengalaman berbelanja lebih nyaman. selain itu, terdapat fasilitas seperti ATM dan UMKM yang meningkatkan kemudahan pengguna dalam memilih minimarket sesuai kebutuhan pengguna. <br/>

## BAB 2 BAHASA DAN APLIKASI YANG DIGUNAKAN SERTA PENGINSTALANNYA <br/>

### 2.1 Bahasa pemrograman yang digunakan 


### 2.1.1 HTML <br/>

![alt text](img/html.png)

HTML adalah singkatan dari Hypertext Markup Language, yang merupakan bahasa markup standar untuk membuat halaman web dan aplikasi web.
Ini digunakan untuk menyusun konten di web dengan mendefinisikan makna dan tata letak teks, gambar, tautan, dan elemen lainnya. Elemen HTML diwakili oleh tag yang tertutup dalam tanda kurung sudut, seperti < head >,< title >,< body >, dll. HTML sangat penting untuk pengembangan web dan merupakan dasar dari sebagian besar situs web di internet.( Izzeddin Gur, 2022)<br/>

### 2.1.2	CSS	<br/>

![alt text](img/css.png)

CSS adalah singkatan dari Cascading Style Sheets, yang merupakan bahasa lembar gaya yang digunakan untuk menggambarkan presentasi dokumen yang ditulis dalam HTML. Ini mengontrol tata letak dan tampilan beberapa halaman web sekaligus dengan memisahkan konten dari desain. CSS memungkinkan pengembang web untuk menentukan gaya untuk berbagai elemen seperti font, warna, spasi, dan tata letak.(Daniel Zhu, Salome Wairimu Kariuki 2020)<br/>

### 2.1.3	JAVASCRIPT	<br/>

![alt text](img/javascript.png)

JavaScript adalah bahasa pemrograman tingkat tinggi yang ditafsirkan terutama digunakan untuk membuat konten interaktif dan dinamis di situs web. JavaScript memungkinkan pengembang untuk menambahkan fungsionalitas ke halaman web, mengontrol perilaku elemen yang berbeda, dan berinteraksi dengan pengguna secara real-time. Biasanya digunakan untuk tugas-tugas seperti validasi formulir, membuat peta interaktif, pembaruan konten dinamis, dan lain-lain. (Abhishek Gedam, 2023)<br/>

### 2.1.4	CSS SKELETON / GETSKELETON	<br/>

![alt text](img/getskeleton.png)

Skeleton adalah Framework CSS yang ringan dan responsif yang dirancang untuk memberikan kerangka kerja dasar untuk pengembangan web. Ini terdiri dari grid sederhana, elemen dasar seperti tombol, formulir, dan tipografi, serta beberapa komponen responsif yang memungkinkan pengembang memulai proyek web dengan cepat tanpa harus menulis CSS dari awal.<br/>

### 2.1.5	NODE JS	<br/>

![alt text](img/nodejs.png)

Node.js adalah lingkungan runtime JavaScript populer untuk membangun aplikasi web. Ini memungkinkan pengembang untuk menulis kode sisi server di JavaScript dan mengelola sisi klien dan server. Node.js memastikan kinerja tinggi melalui input/output yang digerakkan oleh peristiwa, non-pemblokiran, dan paradigma asinkron.(Bonjar Basumatary, Nishant Agnihotri 2022)<br/>

### 2.1.6	Golang

![alt text](img/golang.png)

Menurut (Agung et al., 2017) Golang adalah bahasa pemrograman untuk sistem informasi berbasis cloud yang memiliki performa yang lebih cepat dari pada bahasa pemrograman PHP yang lebih banyak dipakai. Go atau sering juga disebut Golang adalah bahasa pemrograman yang free dan open source dari Google. Bahasa ini dibuat pada tahun 2007 oleh Robert Griesemer, Rob Pike, dan Ken Thompson. Meskipun demikian Golang pertama kali dirilis ke public sebagai proyek open source pada tanggal 10 November 2009. Setelah desain dan pengembangan yang berlangsung selama bertahun-tahun, Golang versi stabil (versi 1) akhirnya dirilis pada tanggal 28 Maret, 2012(A Lulu – 2023)

### 2.2 Aplikasi yang digunakan

### 2.2.1	VISUAL STUDIO CODE	<br/>

![alt text](img/vscode.png)

Visual Studio Code adalah editor kode sumber yang ringan namun kuat yang berjalan di desktop Anda dan tersedia untuk Windows, macOS dan Linux. Muncul dengan dukungan built-in untuk JavaScript, TypeScript dan Node.js dan memiliki ekosistem ekstensi yang kaya untuk bahasa dan runtime lain (seperti C ++, C #, Java, Python, PHP, Go, .NET).(Code.visualstudio.com 05 juni 2024) <br/>


### 2.2.3 MONGODB<br/>

![alt text](img/mongodb.png)

MongoDB adalah basis data NoSQL yang bersifat document based. MongoDB bersifat document based artinya MongoDB tidak memilki tabel,
kolom ataupun baris. MongoDB hanya memilki koleksi dan dokumen.Data yang disimpan dalam basis data MongoDB berupa file JSON yang disebut dengan istilah BSON (Binary JSON).Sistem basis data MongoDB menggunakan key-value, artinya setiap dokumen dalam MongoDB dipastikan memilki key (Putra & Rahmayeni, 2016).<br/>

### 2.3 Instalasi aplikasi

### 2.3.1 Visual Studio Code

### 2.3.2 Mongodb

1. Pertama anda perlu membuat akun mongodb pada website ini https://www.mongodb.com/ lalu anda bisa klik start free pada gambar di bawah ini.

![alt text](image.png)

2. Setelah itu anda akan diarahkan untuk membuat akun mongodb.

![alt text](image-1.png)

3. Setelah anda berhasil membuat akun/signup anda harus mengisi data di bawah sesuai dengan kebutuhan.

![alt text](image-2.png)

4. Pada halaman deploy ini pilih free plan lalu nama sesuaikan saja, pada provider pilih Google Cloud, pada region pilih Jakarta, dan nama cluster sesuaikan saja lalu pilih Create Deployment.

![alt text](image-3.png)

5. Setelah itu ganti password agar tidak pusing lalu pilih Create Database User.

![alt text](image-4.png)

6. Lalu pada connection method pilih compass.

![alt text](image-5.png)

7. Jika anda belum menginstall mongocompass klik dowload compas pada gambar di bawah lalu copy connection string di paling bawah.

![alt text](image-6.png)

8. Pada mongodb.com untuk dapat diakses pada semua IP Address, pada security klik network acces klik ALLOW ACCESS FROM ANYWHERE atau dengan menuliskan 0.0.0.0/0

![alt text](image-7.png)

9. Setting environment masuk ke setting masuk ke environment setting klik environment variable klik new masukan variable MONGOSTRING dan value masukan connection string anda dan save.

![alt text](image-16.png)

10. Buka Mongo DB Compas, Kemudian Add New Connection, tempe connection string yang sudah di salin tadi, ganti kurung sikunya dengan password yang sudah disimpan tadi lalu pilih connect. 

![alt text](image-9.png)

11. Struktur tabel/collection di MongoDB sudah terlihat dan terdapat data dalam bentuk json.

![alt text](image-10.png)

### 2.3.3 GOLANG

1. Instalasi Golang melalui link ini https://go.dev/dl/ lalu pilih Microsoft window.

![alt text](image-11.png)

2. Setelah menginstall golang lalu masuk setting Environment, lalu pilih environment Variable.

![alt text](image-12.png)

3. Pilih PATH klik edit pilih new dan masukan C:\Go\bin seperti pada gambar di bawah.

![alt text](image-17.png)

4. setelah menambahkan path lalu cek golang di Command Prompt dengan mengetik go version.

![alt text](image-14.png)

## BAB 3 PERANCANGAN APLIKASI<br/>

### 3.1 FRONTEND<br/>

Hal pertama yang harus di lakukan adalah membuat kode untuk membuat open layer. Fitur ini adalah tampilan open street map yang akan muncul pada website Dengan menggunakan bahasa pemrograman javascript dan library dari skypack.

Berikut adalah langkah-langkah untuk membuat fitur open layer

1. buatlah folder baru dan masuk ke dalam visual studio code.

2. lalu buat file index.html, main.js, skeleton.css bisa mendowload disini
http://getskeleton.com dan jangan lupa menginstall node js.

3. isi kode program seperti gambar di bawah.

![alt text](img/index.png)

Disini kita membuat link pada skypack ini adalah tautan ke lembar gaya css Dari open layer. Yang digunakan untuk styling elemen elemen pada peta. Lalu ada link rel untuk menghubungkan ke skeleton css yang sudah di dowload.Di body kita menambahkan div id=”map” ini untuk menampung peta interaktif Yang akan dibuat menggunakan open layer. Dan tag javascript untuk Menambahkan fungsi ke peta pada open layer.

![alt text](img/css.png)

Lalu menambahkan css pada file skeleton.css yang sudah di dowload di getskeleton.com Tambahkan kode di paling bawah kode ini untuk mengatur posisi dan Lebar pada map.

lalu kita membuat file main.js

![alt text](img/main.js.png)

Disini terdapat modul modul dari open layer yang akan diimport ke kode. Ada map Untuk membangun objek peta, View untuk mengatur tampilan peta, TileLayer untuk menambahkan lapisan peta berbasis tile, OSM (OpenStreetMap) sebagai sumber data lapisan tile, dan Overlay untuk menambahkan elemen overlay di atas peta, fromlonlatFungsi ini digunakan untuk mengonversi koordinat geografis dari format longitude dan latitude menjadi format yang sesuai dengan sistem proyeksi yang digunakan oleh peta OpenLayers. 

Lalu disini ada target map untuk menentukan elemen HTML dengan id map sebagaiTarget peta, layers menentukan lapisan-lapisan yang akan ditampilkan di peta. Dalam kode ini, hanya satu lapisan yang ditambahkan, yaitu TileLayer dengan modul OSM (OpenStreetMap). view menentukan tampilan peta, termasuk properti seperti pusat peta (dalam koordinat geografis) dan tingkat zoom. Center fromLonLat untuk mengonversi koordinat longitude dan latitude ke dalam koordinatyg sudah ditentukan. Dan zoom untuk memperbesar tampilan pada map.

Lalu kita jalankan kode tersebut dengan klik Go live seperti gambar di bawah.

![alt text](img/run.png)


![alt text](img/map.png)


Langkah selanjutnya adalah membuat fungsi marker dan fungsi popup pada map kita perlu membuat file seperti gambar di bawah.

![alt text](img/image-2.png)

lalu kita isi marker.js dengan membuat fungsi createmarker.

![alt text](img/image-1.png)

Fungsi createMarker ini untuk membuat dan menampilkan marker pada peta OpenLayers dengan menggunakan koordinat geografis yang akan di buat. Fungsi createMarkerElement membuat elemen HTML untuk marker dengan gambar yang disesuaikan, dan marker ditambahkan ke peta dan fungsi mengembalikan objek marker yang telah dibuat.

lalu setelah itu kita juga membuat fungsi popup yang akan keluar setelah marker di klik.

![alt text](img/carbon%20(8).png)

Disini adalah fungsi untuk membuat popup pada marker yang telah di buat fungsi createPopups membuat pop-up berdasarkan koordinat yang diberikan dan memasukkannya ke peta. Fungsi displayPopup menampilkan konten pada pop-up dan menempatkannya di posisi yang ditentukan sesuai dengan lonlat yang dibuat di marker. Fungsi setPositioning mengatur posisi pop-up relatif terhadap koordinat yang diberikan.


lalu kita mengimport fungsi yang sudah di buat tadi masukan ke dalam main.js

![alt text](img/carbon%20(9).png)

kode di atas yaitu membuat untuk mengambil data marker dan pop-up dari URL fetch yang akan di ambil dari backend yang nanti akan dibuat. Data marker dan pop-up diambil melalui fetch. Sementara marker dibuat dengan createMapMarkers, pop-up dibuat dengan initializeMapPopups. Saat peta diklik di area marker,maka di map akan menampilkan popup yang terdapat di dalamnya isi dari url popup yang akan di tambahkan dari backend. dan saat peta diklik di area kosong, semua pop-up disembunyikan. dan memungkinkan pengguna melihat pop-up dan informasi marker pada peta interaktif.



