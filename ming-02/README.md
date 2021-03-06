<h1>SaaS (Software as a Service)</h1>
Software as a Service adalah layanan software yang digunakan melalui internet. Sebenarnya hal ini bukan merupakan hal yang asing dan sering kita gunakan (hanya mungkin kita belum tahu aja), contoh dari SaaS ini adalah google docs, facebook, aplikasi CRM berbayar, dan lain-lain. Pengguna hanya perlu menggunakan aplikasi tersebut tanpa harus mengerti bagaimana data disimpan, bagaimana aplikasi tersebut di maintenance, karena hal tersebut merupakan service yang disediakan penyedia jasa. Pembayaran dari penggunaan aplikasi-aplikasi ini pun hanya per pemakaiannya (terkadang ada yang tak berbayar tetapi ada fitur-fitur tertentu yang bisa didapatkan ketika pengguna membayar fitur-fitur tersebut, yah semacam nyewa parabola gitu lah, bayar berdasar channel yang diinginkan). Dari sinilah muncul istilah Pay per use, pay as you go dan lain sebagainya. Yang jelas, dengan menggunakan SaaS banyak perusahaan yang terbantu untuk menekan biaya yang harus dikeluarkan untuk membeli sebuah perangkat lunak.

<h1>Sejarah</h1>
Software as a service (SaaS) adalah salah satu bagian dari teknologi Cloud Computing yang sebenarnya sudah mulai berkembang sejak tahun 1960-an bersama dengan virtualisasi, grid computing,ASP/ application service provision. Pertama kali dikenal lebih luas saat terbitnya sebuah artikel berjudul “Strategic Backgrounder : Software As A Service” pada tahun 2001 oleh SIIA - eBussiness Division.
<br><br>SaaS sendiri merupakan ekstensi dari paham model ASP, akan tetapi penggunaan SaaS pun juga sering digunakan dalam beberapa kondisi yang berbeda dengan ASP:
<li>ASP cenderung fokus dalam mengatur dan menjalankan aplikasi dari software independen suatu vendor, sementara SaaS mengatur dan menjalankan aplikasi dari software mereka sendiri.</li>
<li>Penggunaan Saas lebih praktis bagi para pengguna internet, karena mereka tidak perlu repot untuk melakukan instalasi software manual, melainkan hanya dengan mendownload dari web-link, berbeda dengan ASP yang perlu instalasi manual pada komputer pelanggan.</li>
<li>Sementara ASP hanya berfokus pada beberapa sektor bisnis, SaaS saat ini mampu bekerja dengan banyak sektor dan pelanggan, serta pengaturan datanya terkontrol.</li>

<h1>Membangun SaaS (Software as a Service) sebagai Layanan Penyedia Aplikasi Enkripsi Dekripsi</h1>

Dalam perancangan layanan SaaS yang pertama dilakukan adalah instalasi XenServer  pada  server  fisik dan  membuat  dua  virtual  machine  yang  berfungsi sebagai  active  directory  dan  XenApp.  Kemudian  setelah  semua  virtual  machine dirancang  maka  kedua  virtual  machine  dihubungkan  kedalam  satu  jaringan. Setelah terhubung dalam satu jaringan, maka konfigurasi untuk membuat layanan SaaS  dilakukan   didalam   virtual   machine   XenApp,   yang   meliputi   instalasi software, instalasi delivery controller dan instalasi Virtual Delivery Agent (VDA) kemudian mengkonfigurasikan citrix studio.
<br><br>Setelah proses  konfigurasi  selesai,  maka  dilakukan  pengujian  layanan SaaS apakah dapat berjalan pada user, jika user tidak dapat mengunakan  layanan SaaS  yang  diberikan,  maka  perlu  diperiksa  kembali  konfigurasi  di  dalam  citrix studio.   Apabila   user   dapat   menjalankan   aplikasi,   maka   dilakukan   proses monitoring  terhadap  server  XenApp  dan  membuat  analisis  serta  kesimpulan  dari hasil perancangan yang telah dibuat.
<br><br>Untuk  alur proses  bisnis  yaitu  bagaimana  user  nantinya  dapat mengakses layanan  aplikasi  dan  menjalankan  aplikasi  enkripsi  dikripsi.</br>
<br><br>Langkah pertama yang dilakukan useruntuk mendapatkan aplikasi adalah meminta username dan password kepada administrator, setelah user mendapatkan usernamedan password, kemudian user masuk   kehalaman websitedan mengunduh citrix  receiverlalu  diinstal  didalam  komputer user.  Setelah proses instalasi  selesai,  kemudian user  loginmenggunakan usernamedan password, apabila   gagal  dalam  proses login maka   perlu   diperiksa   kembali   kepadaadministrator, apabila berhasil melakukan proses 
login, maka userdapat memilih aplikasi enkripsi  dekripsi yang tersedia,  setelah  aplikasi  dipilih,  maka otomatis citrix  receiverberjalan  pada komputer user, setelah  itu  tampilan citrix  receiver tersebut  berubah   menjadi   aplikasi   yang   sudah   dipilih,   sehingga user dapat menggunakan aplikasi enkripsi dekripsi.

<h1>Distribusi</h1>
Dalam pendistribusian model SaaS dapat dikatakan cukup sulit bagi software tradisional yang ingin bergabung, dikarenakan struktur dan pandangan dari SaaS sendiri berbeda dengan software-software terdahulu. Bisa dikatakan bahwa perbedaan ini mencakup hampir semua sektor dalam dunia bisnis dan ekonomi. Akan tetapi, usaha penggabungan dari software lama ke SaaS sangatlah pentih untuk mengikuti perkembangan dunia ekonomi TI.

<h1>Penjualan</h1>
Software as a service (SaaS) memiliki cara yang berbeda dalam mempromosikan dan dalam memberikan layanan mereka pada pelanggan. SaaS memiliki harga jual yang lebih murah dibandingkan dengan perangkat tradisional, mereka menggunakan sistem berlangganan, umumnya selama per bulan atau per tahun. Hal ini dilakukan berdasarkan observasi banyaknya pengguna aplikasi, karena SaaS juga memperhatikan area profit.
<br><br>Selain dengan mengadakan program berlangganan, SaaS juga mengadakan program demo, versi SaaS yang sama, tetapi dengan fitur-fitur yang terbatas bagi para pengguna baru yang ingin mencoba terlebih dahulu. Kemudian apabila mereka ingin mendapatkan fitur yang lain, mereka cukup memilih pilihan yang ada.

<h1>Konfigurasi</h1>
Pada dasarnya SaaS hanya memiliki 2 bentuk, yaitu Vertical SaaS dan Horizontal SaaS.

<li>Vertical SaaS berguna dalam menentukan data yang diperlukan dalam suatu sektor perusahaan yang spesifik, seperti sektor perusahaan software, kesehatan, agrikultur, dan keuangan.</li>
<li>Horizontal SaaS lebih berfokus pada sektor software saja, tetapi masih dalam lingkup perusahaan.</li>

<h1>Hambatan</h1>
• Karena data disimpan dalam independen server, keamanan data menjadi rentan.<br>• Jarak kerja SaaS yang melalui koneksi jaringan menjadi kendala untuk bekerja lebih cepat.<br>• Perubahan-perubahan SaaS dalam perusahaan banyak mengalami pembatasan untuk mendapatkan efisiensi dana.<br>• Keamanan data yang tersimpan dalam SaaS bisa menjadi akses bagi para kriminal, karena akses data yang rentan.<br>• Karena menggunakan koneksi internet, pemindahan jumlah data yang besar akan menjadi masalah.<br>• Karena menggunakan koneksi internet, pemindahan jumlah data yang besar akan menjadi masalah.         

<h1>Tujuan</h1>
Tujuan utama SaaS.com adalah membantu organisasi memberikan Software-as-a-Service untuk memperoleh pangsa pasar dan mempertahankan pelanggan dengan cara sebagai berikut:<br>• Meningkatkan kegunaan dan aspek fungsional dari aplikasi perangkat lunak<br>• Membangun struktur pendapatan dan biaya yang lebih tepat.<br>• Mengurangi waktu implementasi, pelatihan, dan dukungan.<br>• Meminimalkan risiko bisnis secara keseluruhan dengan data aksebilitas dan keamanan data.

<h1>Keuntungan</h1>
Keuntungan potensial penerapan SaaS antara lain:<br>• Kemudahan administrasi<br>• Pengelolaan update dan patch perangkat lunak secara otomatis<br>• Kompatibilitas, karena semua pengguna memiliki versi software yang sama<br>• Kemudahan kolaborasi<br>• Dapat di akses dari seluruh dunia (global), karena menggunakan browser internet


