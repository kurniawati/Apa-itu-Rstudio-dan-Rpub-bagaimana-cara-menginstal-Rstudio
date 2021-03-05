### Apa-itu-Rstudio-dan-Rpub-bagaimana-cara-menginstal-Rstudio
Baik, kali ini kita akan mempelejarai tentang Rstudio terdahulu, R adalah sebuah program komputasi statistika dan grafis (R Core Team 2020). Saat ini R sudah dikenal luas sebagai salah satu powerful software untuk analisis data dan Data Science. Tentu saja selain R masih banyak software lain yang juga sering digunakan untuk analisis data, misalnya Python. R dibuat dengan tujuan awal untuk komputasi statistika dan grafis. Awalnya digunakan oleh para ilmuwan dalam riset mereka dan para akademisi. Namun seiring perkembangan teknologi, cakupan kemampuan R sebagai bahasa pemrograman menjadi jauh lebih luas. Anda dapat membuat dan update report rutin menggunakan R Markdown. Anda juga dapat membuat aplikasi web interaktif atau dashboard dengan package shiny. Karena R didesain untuk analisis data dan perkembangan serta kemampuannya mencakup hampir semua lini dalam analisis data, tidak heran saat ini banyak analis data dan ilmuwan data (data scientist) menggunakan R untuk menyelesaikan berbagai masalah mereka. Berikut ini beberapa kemampuan R. Sedangkan Rpubs adalah sebagai tempat untuk menampung atau mempublikasikan berbagai content yang sudah diprogram pada Rstudio tersebut.

Gratis dan Open Source
Merujuk kepada opensource.com, istilah open source merujuk kepada sesuatu yang bisa dimodifikasi dan dibagikan. Open Source Software (OSS) sendiri berarti software yang source code-nya dapat diperiksa, dimodifikasi, ditambahkan dan dibagikan oleh siapapun.

Tersedia banyak package
Karena R adalah open source software, hampir semua package yang ada pun dapat digunakan secara bebas. Package adalah kumpulan suatu script yang umumnya berupa function (Bab 2.10) atau data yang dapat digunakan untuk kebutuhan tertentu.

Dibuat oleh statistisi untuk statistisi data analyst/data scientist
R adalah sebuah program yang awalnya dibuat untuk kebutuhan statistisi. Oleh karena itu banyak fungsi-fungsi dasar untuk statistika maupun eksplorasi data dan grafis sederhana sudah terdapat di R meskipun tanpa install package tambahan. Namun saat ini R sudah menjadi salah satu software yang digunakan dalam data science karena banyaknya package yang dapat mendukung.

Mudah dalam melakukan transformasi dan pemrosesan data
Karena R adalah program untuk analisis data, maka kemampuan R dalam transformasi data seperti penyiapan data, import dan export data dalam berbagai format, dan lain-lain.

Mampu menghasilkan grafik yang sangat bagus
Salah satu keunggulan yang dimiliki oleh R adalah kemampuannya untuk menghasilkan grafik yang sangat bagus. Salah satu yang diunggulkan adalah package {ggplot2}. Tentu saja masih banyak package untuk visualisasi selain {ggplot2}

Membuat Reproducible report
Ketika Anda mempunyai pekerjaan untuk membuat laporan secara rutin, maka Anda dapat menggunakan R sebagai robot Anda. Dengan package {rmarkdown} Anda dapat membuat laporan rutin dengan hanya satu baris perintah.

Dapat membuat aplikasi interaktif/dashboard berbasis web
Package {shiny} (dan semua pengembangannya) dan {flexdashboard} dapat Anda gunakan untuk membuat visualisasi interaktif ataupun sebagai sebuah produk dari data science.

Membuat REST API
Setelah Anda membuat fungsi atau model prediktif dan ingin digunakan secara lebih luas, Anda dapat membuatnya sebagai API menggunakan package {plumber}.

Dan masih banyak lagi kemampuan R yang dapat dimanfaatkan untuk mendukung dan memudahkan pekerjaan Anda dalam hal analisis data ataupun data science.

Di PC dengan OS Windows dapat melakukan langkah-langkah berikut untuk install R.

Buka halaman https://cran.r-project.org
Pilih Download R for Windows
Comprehensive R Archive Network (CRAN)

Gambar 1.1: Comprehensive R Archive Network (CRAN)

Bagi Anda yang menggunakan OS lain maka Anda dapat mengikuti petunjuk dengan membuka tautan yang sesuai.

Klik install R for the first time
Download R Installer

Gambar 1.2: Download R Installer

Kemudian klik Download R x.x.x for Windows
Download R untuk Windows

Gambar 1.3: Download R untuk Windows

Simpan file installer tersebut dan tunggu hingga proses download selesai
Setelah download selesai, jalankan file R x.x.x.exe tersebut
Anda hanya perlu klik Next dan Finish
catatan: mungkin Anda hanya perlu memilih untuk install versi 64bit jika Anda menggunakan OS Windows 64bit.

1.1.2 Menjalankan R
Setelah selesai install, Anda bisa membuka R GUI.

Pada Windows 10, klik atau tekan tombol Start
Cari Folder R dan pilih R sesuai versi yang sudah terinstall
Menu untuk Menjalankan R

Gambar 1.4: Menu untuk Menjalankan R

Di bawah ini adalah tampilan ketika Anda membuka program R GUI.R GUI

Gambar 1.5: R GUI

Anda sudah dapat menggunakan R melalui R GUI ini. Namun Anda juga dapat menggunakan Integrated Development Environment (IDE) untuk lebih nyaman, mudah dan efisien ketika bekerja dengan R. IDE untuk R yang saat ini sangat sering digunakan adalah RStudio. Berikut ini adalah cara untuk install RStudio di PC Windows.

1.2 RStudio
Sebelum membahas lebih lanjut tentang R, sebaiknya Anda download RStudio dan install terlebih dahulu. RStudio adalah Integrated Development Environment (IDE) untuk R yang banyak digunakan hingga saat ini. Dapat dikatakan bahwa hampir semua pengguna R yang sudah mengetahui RStudio akan lebih memilih menggunakan R melalui RStudio dibandingkan dengan menggunakan R GUI.

Download RStudio versi desktop sesuai dengan kebutuhan Anda. Sangat disarankan untuk menggunakan RStudio versi terbaru, termasuk juga dengan R. R dan RStudio adalah dua program yang berbeda. Anda tidak harus install RStudio untuk dapat menggunakan program R (melalui R GUI). Tapi Anda diwajibkan untuk install R terlebih dahulu sebelum install dan menggunakan RStudio karena RStudio membutuhkan program R yang sudah terinstall di PC atau server. Gambar 1.6 mengilustrasikan perumpamaan R ini seperti kerangka mobil dan mesinnya, sedangkan RStudio seperti kerangka luar mobil dan interiornya. Anda tidak akan dapat menggunakan mobil tersebut jika Anda hanya mempunyai kerangka luar dan dashboardnya (RStudio) saja.R dan RStudio (sumber: https://community.rstudio.com/t/differentiating-r-from-rstudio/8009)

Gambar 1.6: R dan RStudio (sumber: https://community.rstudio.com/t/differentiating-r-from-rstudio/8009)

Install RStudio dengan cara berikut.

Download RStudio Desktop (https://www.rstudio.com/products/rstudio/download/)
Jalankan installer yang sudah didownload
Klik Next Install: Langkah 1 Gambar 1.7: Install: Langkah 1
Klik Next Install: Langkah 2 Gambar 1.8: Install: Langkah 2
Klik Install Install: Langkah 3 Gambar 1.9: Install: Langkah 3
Klik Next Install: Langkah 4 Gambar 1.10: Install: Langkah 4
Klik Finish Install: Langkah 5 Gambar 1.11: Install: Langkah 5
Selanjutnya di buku ini akan lebih banyak menggunakan RStudio dibandingkan dengan R GUI karena lebih mudah dan interaktif.

1.3 Penggunaan RStudio
Untuk menggunakan RStudio di Windows 10, hampir sama ketika Anda akan membuka program R (Bab 1.1.2)Membuka RStudio

Gambar 1.12: Membuka RStudio

1.3.1 Membuat Sebuah Project
Hal yang sebaiknya menjadi kebiasaan Anda ketika menggunakan RStudio adalah membuat sebuah Project untuk setiap pekerjaan yang berbeda. Jika pekerjaan Anda tidak terdapat data yang confidential, Anda juga dapat menggunakan GitHub repository sebagai backup atau berbagi yang Anda kerjakan. Anda dapat membuat sebuah project baru di RStudio dengan cara:Pilihan Membuat Project di RStudio

Gambar 1.13: Pilihan Membuat Project di RStudio

Pilih New Project… dari 3 menu yang tersedia, a) dari menu File, b) dari toolbar, atau c) dari menu di pojok kanan atas seperti terlihat pada Gambar 1.13.
Pilihan New Project

Gambar 1.14: Pilihan New Project

Gambar 1.14 menampilkan pilihan jenis project yang akan dibuat.
New Directory: jika Anda belum mempunyai folder yang Anda jadikan sebagai working directory untuk project tersebut.
Existing Directory: Jika folder Anda sudah ada sebelumnya.
Version Control: Jika Anda akan membuat project berdasarkan repository yang sudah ada, misalnya di GiHub atau SVN.
Karena kita akan membuat project baru dan belum ada folder yang sudah kita siapkan, maka kita akan pilih New Directory.
Tipe New Project

Gambar 1.15: Tipe New Project

Pilih Project Type sesuai dengan project yang akan Anda buat seperti yang terlihat di Gambar 1.15. Misalnya kita buat sebuah project kosong, pilih New Project.
Nama Project

Gambar 1.16: Nama Project

Tuliskan nama project yang juga akan menjadi nama folder baru sebagai subfolder di dalam folder “Create project as subdirectory of:” seperti terlihat pada Gambar 1.16
Klik Create Project
Untuk jenis project lainnya Anda dapat mencoba dan mengeksplorasi sendiri.

1.3.2 Membuat File Script Baru
Seperti halnya pada R GUI, Anda juga dapat menuliskan langsung perintah atau script pada jendela console di RStudio. Namun di buku ini Anda akan menuliskan semua script di bagian script editor. Hal ini sebaiknya menjadi kebiasaan Anda ketika menggunakan RStudio. Untuk membuat script editor baru di RStudio, Anda dapat klik menu File >> New File >> R Script. Cara yang kedua adalah dengan toolbar New File. Anda dapat lihat pada Gambar 1.17. Anda juga dapat menggunakan shortcut RStudio dengan menekan tombol Ctrl + Shift + N jika Anda menggunakan OS Windows.Membuat Script Baru

Gambar 1.17: Membuat Script Baru

Akan muncul file script kosong seperti tampilan Gambar 1.18.Tampilan Script Baru

Gambar 1.18: Tampilan Script Baru

1.3.3 Menjalankan Script Pada Script Editor
Setelah berhasil menyiapkan file script editor baru yang masih kosong Anda dapat menuliskan semua yang akan Anda lakukan dengan R. Mencoba “Hello world!” di R? Baiklah.Menuliskan "Hello World!" Menggunakan Beberapa Bahasa Pemrograman

Gambar 1.19: Menuliskan “Hello World!” Menggunakan Beberapa Bahasa Pemrograman

Di R Anda cukup menuliskan "Hello World!" di script editor, kemudian Run atau tekan tombol Ctrl + Enter ketika cursor berada pada baris script tersebut (Gambar 1.20). Tentu saja Anda juga dapat melakukannya seperti yang ada di Python dengan fungsi print().Menuliskan Hello World di R

Gambar 1.20: Menuliskan Hello World di R

1
print("Hello World!")
1
## [1] "Hello World!"
Selanjutnya untuk menyimpan script tersebut menjadi sebuah file, Anda dapat lakukan dengan a) klik lambang simpan, b) pilih menu File >> Save atau Save As... atau c) menggunakan shortcut dengan menekan tombol Ctrl + S.Menyimpan Script R

Gambar 1.21: Menyimpan Script R

Kemudian tentukan lokasi folder tempat menyimpan file script tersebut. Selanjutnya berikan nama file pada kotak File name: seperti pada Gambar 1.22. Terakhir klik Save.Memberi Nama Script R

Gambar 1.22: Memberi Nama Script R

1.3.4 Menutup RStudio
Setelah selesai menggunakan RStudio Anda dapat menutupnya seperti menutup software lainnya. Namun yang perlu di perhatikan adalah ketika muncul konfirmasi seperti Gambar 1.23. Sangat disarankan untuk tidak menyimpan workspace ketika menutup RStudio. Karena ketika Anda membuka kembali RStudio maka akan memuat (loading) kembali semua yang disimpan dari pekerjaan sebelumnya. Hal ini akan sangat berpengaruh ketika ukuran image dari pekerjaan yang disimpan tersebut relatif besar.Konfirmasi Mentutup RStudio

Gambar 1.23: Konfirmasi Mentutup RStudio

