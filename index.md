---
title: "Network Attached Storage (NAS)"
permalink: /
layout: default
---

<!-- HEADER -->
<a name="readme-top"></a>
<!-- PRISON TEST -->
<br />
<div align="center">
  <a href="/">
    <img src="images/nas.png" alt="NAS" width="80" height="80">
  </a>

  <h3 align="center">Network Attached Storage (NAS)</h3>
  <h3 align="center">Pelem Fam's</h3>
  <h3 align="center">(WORK IN PROGRESS)</h3>

  <p align="center">
    Butuh sharing file atau penyimpanan tambahan? Pake NAS aja!

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#apa-itu-nas">Apa itu NAS?</a>
      <ul>
        <li><a href="#variants">Fungsi NAS</a></li>
      </ul>
    </li>
    <li>
      <a href="#kamus">Kamus</a>
    </li>
    <li>
      <a href="#cara-pakai">Cara Pakai</a>
    </li>
    <li><a href="#akses">Akses</a></li>
    <li><a href="#login">Login</a></li>
    <li>
      <a href="#instalasi">Instalasi</a>
      <ul>
        <li><a href="#windows-explorer-windows">Windows Explorer (Windows)</a></li>
        <li><a href="#file-manager-plus-android">File Manager Plus (Android)</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- NAS -->
## Apa itu NAS?

NAS adalah sebuah perangkat penyimpanan (seperti hard drive) yang terhubung ke jaringan dan bisa diakses oleh banyak pengguna atau perangkat sekaligus, seperti komputer, laptop, ponsel, atau bahkan smart TV.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Fungsi NAS

* Menyimpan file (foto, video, dokumen, dll)
* Berbagi file antar pengguna dalam jaringan
* Backup data secara otomatis terutama saat HP penuh
* Bisa dijadikan server media (untuk streaming musik/film di rumah)
* Beberapa NAS juga bisa menjalankan aplikasi seperti server web, server CCTV, dan lain-lain

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Kamus  -->

## Kamus
* `hostname` local : `192.168.1.100` : identitas atau alamat server khusus di rumah (paling stabil, bebas quota) 
* `hostname` cloud : `100.123.123.123` : identitas atau alamat server di mana saja saat terkoneksi VPN (bisa tidak stabil, butuh quota)
* `hostname` hybrid : `charmy` : identitas atau alamat server di mana saja saat terkoneksi VPN (bisa tidak stabil, butuh quota) atau di rumah tanpa VPN (cukup stabil, bisa jadi juga berbayar)
* `VPN` : `Tailscale` : aplikasi untuk koneksi jaringan ke server melalui internet
* `client` : aplikasi semacam _Windows Explorer_ untuk mengakses NAS dalam bentuk folder/partisi
* `user` : nama pengguna untuk login NAS
* `passwd` : password untuk login NAS

<!-- Cara Pakai  -->
## Cara Pakai

Perlu instalasi terlebih dahulu. Pemakaian selanjutnya sama dengan membuka _Windows Explorer_ (PC) atau _File Manager_ (smartphone). Hanya saja ada tambahan folder/partisi yang bisa diakses dari mana saja dan siapa saja. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Akses -->
## Akses

Setiap user punya satu folder private sesuai nama user. Semua user bisa mengakses folder family. Semua orang tanpa login (tidak disarankan di Windows) bisa membaca atau mendownload data di folder family.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Login -->
## Login

* Users: gal somsom in ib pi
* Password default: 123 (ganti password sebelum dipakai)

Ganti password [disini](http://charmy/nas/) (via Tailscale) atau [disini](http://192.168.1.100/nas/) (via wifi). Kalo lupa password atau butuh user baru bisa [minta ke admin](https://wa.me/6281233858883).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Instalasi

* [Tailscale](https://tailscale.com/download)
* Windows Explorer (Windows)
* [File Manager Plus](https://play.google.com/store/apps/details?id=com.alphainventor.filemanager&hl=id) (Android)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Windows Explorer (Windows)
1. Cek email untuk accept Tailscale net dan daftar. Bila belum dapat, bisa langsung step 4 menggunakan `hostname` local, dan silakan [minta ke admin](https://wa.me/6281233858883).
<video width="640" height="360" controls>
  <source src="001.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
2. Download dan install [Tailscale](https://tailscale.com/download)
3. Login dan connect Tailscale app
<video width="640" height="360" controls>
  <source src="003.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
4. Setting Windows Explorer dengan `hostname` hybrid (atau local)
<video width="640" height="360" controls>
  <source src="004.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
5. (optional) Ubah nama drives
<video width="640" height="360" controls>
  <source src="005.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### File Manager Plus (Android)
1. Download dan install [File Manager Plus](https://play.google.com/store/apps/details?id=com.alphainventor.filemanager&hl=id) (Android)
2. Masuk menu Remote
3. Login dengan `hostname` local
4. Kalo mau online via `hostname` cloud/hybrid juga bisa install dan connect Tailscape. Aktivasinya sama dengan step 1 di _Windows Explorer_.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Satria Manggala Jati - [@satriamjati](https://twitter.com/satriamjati) - me@jat.my.id - [Whatsapp](https://wa.me/628123385883)

Project Link: [https://github.com/satriamjati/nas](https://github.com/satriamjati/nas)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

