# MySoulB

Proyek ini dibuat untuk memberdayakan kembali handphone Samsung Soul B saya yg sudah lama menganggur karena gak tau sistem operasinya apaan maupun cara ngambil data dari handphone ini gimana. Satu-satunya yg saya tahu cara melakukannya adalah dengan dibuat Mass Storage, yaitu sebagai tempat penyimpanan data (1 GB) dan microSD reader (up to 8 GB). Karena itu sebelumnya saya mencari program yg sudah jadi seperti gammu, ternyata hanya beberapa saja yg di-support dan handphone saya tidak termasuk di dalamnya. Satu lagi keinginan saya adalah memberdayakan handphone ini di OS linux, karena kalau di OS windows tinggal mendownload program jadi saja. Karena keinginan saya banyak dan kemampuan saya sedikit, maka saya bermaksud menjadikan proyek ini sebagai langkah awal saya belajar ilmu reverse engineering dan mungkin di kemudian hari bermanfaat untuk diterapkan ke device-device lain yg mungkin sudah saatnya masuk museum.

## Getting Started

* Karena satu-satunya program jadi yang saya kenal untuk memberdayakan handphone adalah gammu, maka saya bermaksud untuk mencontoh dari source code gammu. Maka untuk langkah awal adalah copy source code gammu. Source code nya tersedia di [github gammu](https://github.com/gammu/gammu) dan saatnya mempelajari git
* Source code gammu ditulis dalam bahasa C, maka langkah selanjutnya adalah mempelajari bahasa C
* (selanjutnya akan ditambahkan seiring berjalannya proyek ini)

### Prerequisites

* install linux (biasanya sudah termasuk gcc, tapi kalau misalkan belum termasuk silakan install gcc, gcc adalah compiler untuk bahasa C)
```
sudo apt install gcc
```
* install git
```
sudo apt install git
```
* (selanjutnya akan ditambahkan seiring berjalannya proyek ini)

## Deployment

Untuk sementara terminal based dulu, jadi bisa dijalankan lewat terminal. Kalau semangat masih membara akan dilanjutkan untuk membuat front end nya dengan GUI (Graphical User Interface)


## Authors

* **Paulus Triswandani** - *Initial work*

## License

Proyek ini menggunakan lisensi [GPL versi 3](http://www.gnu.org/licenses/gpl-3.0.txt) karena gammu jg pake itu. Awalnya mau pake lisensi MIT, tapi karena source code dari GPL gak bisa dijadiin lisensi MIT, yah jadinya pake lisensi GPL. Urusan orang hukum nih.
