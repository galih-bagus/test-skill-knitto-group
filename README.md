# Test Skill Knitto Group

Berikut adalah jawaban dari soal tes skill

1. Apa itu QA (Quality Assurance) dan apa peran utama seorang QA Engineer dalam
siklus pengembangan perangkat lunak?
 - QA adalah sebuah posisi yang dimana berperan memastikan bahwa dalam sebuah produk memenuhi standar kualitas tertentu, dan peranan utama QA Engineer adalah membuat automation testing dari test case yang telah dibuat oleh QA Analyst dan juga berkolaborasi dengan tim lain.

2. Jelaskan perbedaan antara pengujian fungsional dan pengujian non-fungsional dalam
konteks QA.
  - Pengujian Fungsional adalah pengujian yang memastikan semua fitur berjalan sesuai dengan keinginan.
  - Pengujian Non Fungsional adalah pengujian yang memastikan performa, keamanan dan skalabilitas sudah sesuai dengan keinginan.

3. Bagaimana Anda akan merencanakan dan melakukan pengujian manual untuk
aplikasi web e-commerce? Berikan langkah-langkah utama dalam proses ini.
 - Memahami alur aplikasi
 - Membuat test case
 - Melakukan testing berdasarkan test case yang ada
 - Melaporkan temuan issue jika terdapat issue
 - Melakukan retest issue
 - UAT
 - Memberikan dokumentasi testing

4. Apa yang dimaksud dengan uji regresi? Mengapa uji regresi penting dalam pengujian
perangkat lunak?
 - Uji regresi adalah testing untuk memastikan jika ada penambahan fitur, perbaikan issue, atau pembaruan lainnya tidak mempengaruhi fitur yang sudah ada sebelumnya. Uji regresi itu penting karena dapat menemukan issue lama yang sudah diperbaiki, menimalkan resiko terdapat issue jika sudah rilis di production, dan menjaga kualitas sebuah produk.

5. Apa perbedaan antara pengujian otomatis dan pengujian manual? Kapan Anda harus
menggunakan pengujian otomatis daripada pengujian manual?
 - Pengujian manual adalah pengujian yang dilakukan oleh seorang QA dan tidak dilakukan oleh sistem atau script.
 - Pengujian otomatis adalah pengujian yang secara otomatis dilakukan oleh sistem dan scriptnya ditulis oleh seorang QA. Pengujian otomatis dilakukan jika : 
   - Ingin melakukan regresi yang berulang
   - Aplikasi yang tidak sering berubah - ubah

6. Gambarkan aliran kerja atau proses yang akan Anda ikuti untuk mengotomatisasi
pengujian menggunakan alat seperti Selenium. 
 - Menganalisis test case yang sudah ada untuk di buat pengujian otomatis
 - Memilih bahasa pemgrograman dan framework pengujian otomatis
 - Membuat script pengujian otomatis
 - Melakukan pengujian otomatis di berbagai browser
 - Membuat laporan pengujian otomatis
 - Maintenance script pengujian otomatis
 - Integrasi pengujian otomatis dengan CI/CD

7. Apa itu kerangka kerja pengujian (testing framework) dalam pengujian otomatis, dan
bagaimana kerangka kerja ini membantu dalam pengujian perangkat lunak?
 - Testing framework adalah pengujian otomatis adalah struktur atau platform yang memberikan dasar untuk merancang, mengembangkan, dan menjalankan skrip pengujian otomatis dengan cara yang efisien, konsisten, dan terorganisir. Testing framework dapat membantu dalam pengujian otomatis, karena : 
   - Struktur script yang sudah terorganisir
   - Penggunaan ulang kode yang sudah ada
   - Pengelolaan data pengujian
   - Integrasi dengan CI/CD
   - Meningkatkan kolaborasi antar tim

8. Apa yang dimaksud dengan "bug tracking system" dan sebutkan beberapa alat umum
yang digunakan untuk melacak dan mengelola bug dalam perangkat lunak. 
 - Bug tracking system adalah perangkat lunak atau alat yang digunakan untuk melacak, mencatat, dan mengelola masalah, bug, atau cacat (defect) yang ditemukan dalam perangkat lunak selama siklus pengembangan dan pengujian. Berikut adalah perangkat lunak untuk pengecekan / pelacakan bugs : 
   - Jira
   - Trello
   - Spreadsheet
   - Gitlab Card
   - QA Touch
   - Bugzilla
   - GitHub Issues
   - Clickup
   - Test rail

9. Berikan contoh skenario uji fungsional untuk aplikasi pemesanan tiket pesawat
secara online. 
 - Skenario Uji Fungsional : 
    1. Pencarian Penerbangan (Flight Search)\
       Tujuan: Memastikan bahwa user dapat mencari penerbangan sesuai dengan input yang diinginkan.\
       Langkah Pengujian:
       - 1 Buka halaman beranda aplikasi.
       - 2 Pilih jenis penerbangan (sekali jalan atau pulang-pergi).
       - 3 Masukkan bandara keberangkatan dan bandara tujuan.
       - 4 Pilih tanggal keberangkatan (dan tanggal kepulangan, jika pulang-pergi).
       - 5 Tentukan jumlah penumpang.
       - 6 Klik tombol "Cari Penerbangan".

    2. Pengisian Data Penumpang (Passenger Information Input)\
       Tujuan: Memastikan user dapat memasukkan informasi penumpang dengan benar.\
       Langkah Pengujian:
       - 1 Pada halaman pengisian data penumpang.
       - 2 Input semua field mandatory.
       - 3 Klik tombol "Lanjutkan"

    3. Pembayaran Tiket (Ticket Payment)\
       Tujuan: Memastikan bahwa user dapat melakukan pembayaran tiket dengan metode yang tersedia.\
       Langkah Pengujian:
       - 1 Pada halaman pembayaran, pilih metode pembayaran (kartu kredit, transfer bank, e-wallet, dll.).
       - 2 Input semua field mandatory.
       - 3 Klik tombol "Bayar Sekarang".

    4. Pengelolaan Pemesanan (Manage Booking)\
       Tujuan: Memastikan user dapat melihat.\
       Langkah Pengujian:
       - 1 Buka halaman "Pengelolaan Pemesanan" atau "My Bookings".
       - 2 Masukkan nomor pemesanan dan nama belakang penumpang.
       - 3 Klik tombol "Cari Pemesanan".

    5. Pembatalan Pemesanan (Booking Cancellation)\
       Tujuan: Memastikan user dapat membatalkan pemesanan sebelum tanggal penerbangan.\
       Langkah Pengujian:
       - 1 Masuk ke halaman "Pengelolaan Pemesanan".
       - 2 Pilih penerbangan yang ingin dibatalkan.
       - 3 Klik tombol "Batalkan Pemesanan" dan ikuti proses konfirmasi.

10. Anda sedang menguji aplikasi perbankan online. Bagaimana Anda akan menguji
keamanan aplikasi ini? Berikan beberapa contoh uji keamanan yang akan Anda
lakukan. 
- Pengujian keamanan aplikasi perbankan online sangat penting untuk melindungi data pengguna, mencegah pencurian identitas pengguna, dan menghindari akses tidak valid ke akun serta transaksi keuangan. Berikut Contoh pengujian keamanan : 
    1. Authentication Testing
    2. Input Validation Testing
    3. API Vulnerability Testing
    4. Authorization Testing


11. Pada Aplikasi Mobile Shopee, pada Fitur Pesanan Saya - Tab Belum Bayar terdapat penambahan aturan terkait Edit Jenis Pembayaran hanya bisa dilakukan pada kondisi order :\
 - Jika Order tsb belum dibayar
 - Jenis Pembayaran yg sudah dipilih memiliki status ‘gagal-bayar’ Jika salah satu syarat tsb terpenuhi maka pada Fitur Pesanan Saya- TabBelum Bayar pada baris order nya terdapat button ‘Ubah Pembayaran’. 
Coba Buatkan Test Case terkait update fitur tsb dengan menggunakanTest Variable serta contoh Test Data berdasarkan ketentuan diatas.
<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Test case ID</th>
      <th>Judul</th>
      <th>Tipe pengujian</th>
      <th>Langkah langka</th>
      <th>Hasil espektasi</th>
      <th>Test data</th>
      <th>Evidence</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TC0001</td>
      <td>Dapat melihat tombol "Ubah Pembayaran" dengan status order yang belum dibayar</td>
      <td>Positif</td>
      <td>
        1. Buka aplikasi Shopee dan login.<br / >
        2. Akses fitur "Pesanan Saya".<br / >
        3. Pilih Tab "Belum Bayar".<br / >
        4. Temukan order dengan status "Belum Bayar" yang belum dilakukan percobaan pembayaran.<br / >
        5. Periksa apakah tombol "Ubah Pembayaran" muncul.<br / >
      </td>
      <td>
        1. Aplikasi shopee terbuka dan dapat login.<br / >
        2. Muncul tampilan pesanan saya.<br / >
        3. Muncul tab Belum Bayar.<br / >
        4. -<br / >
        5. Terdapat tombol "Ubah Pembayaran".<br / >
      </td>
      <td>
        ID Order: 123456789.<br / >
        Status Pembayaran: Belum dibayar.<br / >
        Jenis Pembayaran: Belum dipilih (belum ada percobaan).<br / >
      </td>
      <td></td>
    </tr>
    <tr>
      <td>TC0002</td>
      <td>Dapat melihat tombol "Ubah Pembayaran" dengan status order yang gagal bayar</td>
      <td>Positif</td>
      <td>
        1. Buka aplikasi Shopee dan login.<br / >
        2. Akses fitur "Pesanan Saya".<br / >
        3. Pilih Tab "Belum Bayar".<br / >
        4. Temukan order dengan status pembayaran "gagal-bayar".<br / >
        5. Periksa apakah tombol "Ubah Pembayaran" muncul.<br / >
      </td>
      <td>
        1. Aplikasi shopee terbuka dan dapat login.<br / >
        2. Muncul tampilan pesanan saya.<br / >
        3. Muncul tab Belum Bayar.<br / >
        4. -<br / >
        5. Terdapat tombol "Ubah Pembayaran".<br / >
      </td>
      <td>
        ID Order: 234567890.<br / >
        Status Pembayaran: Gagal-bayar.<br / >
        Jenis Pembayaran: Kartu Kredit (gagal).<br / >
      </td>
      <td></td>
    </tr>
    <tr>
      <td>TC0003</td>
      <td>Tidak dapat melihat tombol "Ubah Pembayaran" dengan status pembayaran "Sukses"</td>
      <td>Negatif</td>
      <td>
        1. Buka aplikasi Shopee dan login.<br / >
        2. Akses fitur "Pesanan Saya".<br / >
        3. Pilih Tab "Belum Bayar".<br / >
        4. Temukan order yang statusnya sudah dibayar.<br / >
        5. Periksa apakah tombol "Ubah Pembayaran" tidak muncul.<br / >
      </td>
      <td>
        1. Aplikasi shopee terbuka dan dapat login.<br / >
        2. Muncul tampilan pesanan saya.<br / >
        3. Muncul tab Belum Bayar.<br / >
        4. -<br / >
        5. Tidak terdapat tombol "Ubah Pembayaran".<br / >
      </td>
      <td>
        ID Order: 345678901.<br / >
        Status Pembayaran: Sukses (belum dikonfirmasi).<br / >
        Jenis Pembayaran: Transfer Bank (sukses).<br / >
      </td>
      <td></td>
    </tr>
    <tr>
      <td>TC0004</td>
      <td>Tidak dapat melihat tombol "Ubah Pembayaran" dengan status orderan sudah terbayar</td>
      <td>Negatif</td>
      <td>
        1. Buka aplikasi Shopee dan login.<br / >
        2. Akses fitur "Pesanan Saya".<br / >
        3. Pilih Tab "Belum Bayar".<br / >
        4. Temukan order yang statusnya sudah dibayar.<br / >
        5. Periksa apakah tombol "Ubah Pembayaran" tidak muncul.<br / >
      </td>
      <td>
        1. Aplikasi shopee terbuka dan dapat login.<br / >
        2. Muncul tampilan pesanan saya.<br / >
        3. Muncul tab Belum Bayar.<br / >
        4. -<br / >
        5. Tidak terdapat tombol "Ubah Pembayaran".<br / >
      </td>
      <td>
        ID Order: 456789012.<br / >
        Status Pembayaran: Dibayar.<br / >
        Jenis Pembayaran: E-wallet (sukses).<br / >
      </td>
      <td></td>
    </tr>
    <tr>
      <td>TC0005</td>
      <td>Tidak dapat meilhat tombol “Ubah Pembayaran” dengan status “gagal-bayar” dengan menggunakan metode pembayaran COD</td>
      <td>Positif</td>
      <td>
        1. Buka aplikasi Shopee dan login.<br / >
        2. Akses fitur "Pesanan Saya".<br / >
        3. Pilih Tab "Belum Bayar".<br / >
        4. Temukan order dengan metode pembayaran COD yang berstatus gagal.<br / >
        5. Periksa apakah tombol "Ubah Pembayaran" muncul.<br / >
      </td>
      <td>
        1. Aplikasi shopee terbuka dan dapat login.<br / >
        2. Muncul tampilan pesanan saya.<br / >
        3. Muncul tab Belum Bayar.<br / >
        4. -<br / >
        5. Tidak terdapat tombol "Ubah Pembayaran".<br / >
      </td>
      <td>
        ID Order: 567890123.<br / >
        Status Pembayaran: Gagal-bayar.<br / >
        Jenis Pembayaran: COD.<br / >
      </td>
      <td></td>
    </tr>
  </tbody>
</table>
