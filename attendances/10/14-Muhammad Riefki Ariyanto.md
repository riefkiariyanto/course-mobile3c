## Pertemuan Mingguu 10

Dalam pertemuan ke 10 membahas tentang retrofit API untuk menjadi sebuah database lokal yang dijadikan penyimpanan dari android. Dalam Retrofit tersebut juga berguna sebagai REST API yang mana REST sendiri memiliki 6 prinsip, yaitu client-server, stateless, cacheable, uniform interface, layered system, dan code on demand. Client-server: prinsipnya adalah memisahkan permasalahan antara UI dan storage. Sehingga dapat meningkatkan portability UI pada berbagai platform tanpa terkendala dengan ketersediaan data. Stateless: tidak perlu session, hanya ada di sisi client. Cacheable: respon/request dapat disimpan dan digunakan kembali. Uniform interface: memiliki antarmuka dengan banyak bentuk sehingga dapat berkomunikasi dengan arsitektur sistem secara umum. Layered system: berada pada lapisan sistem yang ketika berkomunikasi tidak mudah terekspos dengan komponen lain. Code on demand (optional): sisi client dapat melakukan pengunduhan dan eksekusi code dalam bentuk applet atau script tergantung fitur yang dibutuhkan. Selanjutnya dalam pertemuan ini mencoba membuat sebuah aplikasi android yang dapat menampilkan REST API dari github API untuk menampilkan data yang ada di GITHUB. Pertama yang harus dilakukan membuat koneksi di AndroidManifest menjadi terhubung internet supaya dapat selalu mengakses internet didalam aplikasi androidnya. Kedua membuat library baru pada gradle di android untuk memasang retrofit dan juga gson sebagai pengonversi API yang ada di model nantinya.