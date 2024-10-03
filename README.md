# hello_world

A new Flutter project.

## Identitas Mahasiswa

> Nama  : Triyana Dewi Fatmawati <br/>
> NIM   : 2241720206 <br/>
> Kelas : TI - 3H <br/>
> Nomor : 25 <br/>

---

### Praktikum 1: Membuat Project Flutter Baru
Jika proses pembuatan project baru hello_world selesai, maka akan ditampilkan pesan berupa "Your Flutter Project is ready!" artinya project telah berhasil dibuat.
![Hasil Praktikum 1](/images/prak1.png)

### Praktikum 2: Menghubungkan Perangkat Android atau Emulator
Untuk menghubungkan aplikasi di Android Studio ke perangkat Android fisik kita dapat menghubungkan perangkat menggunakan kabel/USB atau Wi-Fi. Berikut tampilan pada Android Studio ketika proses penyambungan dengan perangkat fisik berhasil.
![Hasil Praktikum 2](/images/prak2.png)

### Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum
#### Langkah 10 
Melakukan push untuk semua file pada projek hello_world dengan pilih Stage All Changes. Lalu memberi pesan commit "project hello_world". Maka akan tampil di repository GitHub seperti berikut.
![Hasil Praktikum 3 Langkah 10](images/prak3-10.png)

#### Langkah 11 
Running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama akan tampil seperti berikut.
- Google Chrome
    ![Hasil Praktikum 3 Langkah 11 Chrome](images/prak3-11-CR.png)

- Android
    ![Hasil Praktikum 3 Langkah 11 Android](/images/prak3-11.png)

    ![Hasil Praktikum 3 Langkah 11 Handphone](/images/prak3-11-AD.jpg)

#### Langkah 12
Melakukan praktikum seperti Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap.
![Kode Program Praktikum 3 Langkah 12](/images/3-12.png)

- Google Chrome
    ![Hasil Praktikum 3 Langkah 12 Chrome](/images/01.png)

- Android
    ![Hasil Praktikum 3 Langkah 12 Android](/images/02.png)
    
    ![Hasil Praktikum 3 Langkah 12 Handphone](/images/03.jpg)

### Praktikum 4: Menerapkan Widget Dasar
#### Langkah 1: Text Widget
Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart.
![Kode Program Praktikum 4 Langkah 1](/images/4-1.png)

Melakukan import file text_widget.dart ke main.dart
![Kode Program Praktikum 4 Langkah 1](/images/4-1-2.png)

![Kode Program Praktikum 4 Langkah 1](/images/4-1-3.png)

- Google Chrome
    ![Hasil Praktikum 4 Langkah 1 Chrome](/images/prak4-1.png)

- Android
    ![Hasil Praktikum 4 Langkah 1 Android](/images/prak4-2.png)
  
    ![Hasil Praktikum 4 Langkah 1 Handphone](/images/prak4-3.jpg)

#### Langkah 2: Image Widget
Buat sebuah file image_widget.dart di dalam folder basic_widgets.
![Kode Program Praktikum 4 Langkah 2](/images/4-2.png)

Melakukan penyesuaian asset pada file pubspec.yaml dan menambahkan file logo Anda di folder assets project hello_world.
![Kode Program Praktikum 4 Langkah 2](/images/4-2-1.png)

Melakukan import file image_widget.dart ke main.dart
![Kode Program Praktikum 4 Langkah 2](/images/4-2-2.png)

![Kode Program Praktikum 4 Langkah 2](/images/4-2-3.png)

- Google Chrome
    ![Hasil Praktikum 4 Langkah 2 Chrome](/images/prak4-4.png)

- Android
    ![Hasil Praktikum 4 Langkah 2 Android](/images/prak4-5.png)
  
    ![Hasil Praktikum 4 Langkah 2 Handphone](/images/prak4-6.jpg)

### Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino
Pada praktikum 5 mulai dari Langkah 3 sampai 6, membuat file widget tersendiri di folder basic_widgets, kemudian pada file main.dart cukup melakukan import widget sesuai masing-masing langkah.

#### Langkah 3: Scaffold Widget
Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.
![Kode Program Praktikum 5 Langkah 3](/images/5-3-1.png)

![Kode Program Praktikum 5 Langkah 3](/images/5-3-2.png)

- Google Chrome
    ![Hasil Praktikum 5 Langkah 3 Chrome](/images/prak5.png)
    Ketika Button + diklik maka nilai counter akan bertambah 1. Seperti pada gambar berikut.
    ![Hasil Praktikum 5 Langkah 3 Chrome](/images/prak5-1.png)

- Android
    ![Hasil Praktikum 5 Langkah 3 Handphone](/images/prak5-2.gif)

#### Langkah 4: Dialog Widget
Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.
![Kode Program Praktikum 5 Langkah 4](/images/5-4-1.png)

![Kode Program Praktikum 5 Langkah 4](/images/5-4-2.png)

- Google Chrome
    ![Hasil Praktikum 5 Langkah 4 Chrome](/images/prak5-3.png)
    Ketika button "Show alert" diklik maka akan muncul dialog My Message, yang didalamnya terdapat message berupa "Hello! I'm Triyana Dewi Fatmawati" Seperti gambar berikut.

    ![Hasil Praktikum 5 Langkah 4 Chrome](/images/prak5-4.png)

- Android
    ![Hasil Praktikum 5 Langkah 4 Handphone](/images/prak5-5.gif)

#### Langkah 5: Input dan Selection Widget
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.
![Kode Program Praktikum 5 Langkah 5](/images/5-5.png)

- Google Chrome
    ![Hasil Praktikum 5 Langkah 5 Chrome](/images/prak5-6.png)
    Pada hasil praktikum langkah ini, terdapat text field yang dapat diinputkan nama, berikut contohnya.
    ![Hasil Praktikum 5 Langkah 5 Chrome](/images/prak5-7.png)

- Android
    ![Hasil Praktikum 5 Langkah 5 Handphone](/images/prak5-8.gif)

#### Langkah 6: Date and Time Pickers
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.
![Kode Program Praktikum 5 Langkah 6](/images/5-6-1.png)

![Kode Program Praktikum 5 Langkah 6](/images/5-6-2.png)

- Google Chrome
    ![Hasil Praktikum 5 Langkah 6 Chrome](/images/prak5-9.png)
    Pada hasil praktikum langkah ini, menampilkan tanggal hari ini namun bisa disesuaikan/ganti dengan klik button "Pilih Tanggal". Berikut tampilan ketika button tersebut diklik
    ![Hasil Praktikum 5 Langkah 6 Chrome](/images/prak5-10.png)

    Bisa kita sesuaikan, disini saya menggantinya dengan tanggal 28 Januari 2024
    ![Hasil Praktikum 5 Langkah 6 Chrome](/images/prak5-11.png)

    Setelah diklik OK maka tanggal yang ditampilkan akan berganti menjadi 2024-01-28 (sesuai dengan tanggal yang dipilih sebelumnya)
    ![Hasil Praktikum 5 Langkah 6 Chrome](/images/prak5-12.png)

- Android
    ![Hasil Praktikum 5 Langkah 6 Handphone](/images/prak5-13.gif)


### Codelabs: Your first Flutter app
**Perintah!** Selesaikan Codelabs: Your first Flutter app, lalu buatlah laporan praktikumnya dan push ke repository GitHub Anda! 
<br>
**Link pengerjaan** : [Tugas 4 - namer_app](https://github.com/triyanadewi/namer_app)