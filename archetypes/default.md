---
title: "{{ replace .Name "-" " " | title }}"
links:
  - title: Link Google Drive
    description: {{ replace .Name "-" " " | title }}
    website: https://drive.google.com/drive/folders/1a1fnUL-5fwZhCHNVX-polO3eCY_y2ThT?usp=share_link
    image: gambar.png
description: 
date: {{ .Date }}
image: gambar.png
math: 
license: 
hidden: false
comments: true
draft: false
categories:
    - Laporan KKN
    - Laporan KP
    - Laporan TA
    - Buku Terbuka
    - Kode Sumber Terbuka
    - Example Category
tags:
    - Kuliah Kerja Nyata
    - Tugas Akhir
    - Institut Teknologi Sumatera
    - Teknik X
    - Example Tag
---

<!-- format penulisan rincian laporan (repo) -->
## Keterangan Laporan / Buku
| Nama Data                     | Keterangan                                  |
| ----------------------------- | ------------------------------------------- |
| Judul                         | {{ replace .Name "-" " " | title }} |
| Nama Pengarang                | Ahmad Yusuf Maulana |
| NIM                           | 119130046 |
| Prodi / Perguruan Tinggi      | Teknik Elektro / Institut Teknologi Sumatera |
| Pembimbing 1                  | Nike Dwi Grevika Drantantiyas,S.Si., M.T. |
| Pembimbing 2                  | Ferizandi Qauzar Gani S.T., M.T. |

## Baca Laporan / Buku
{{< iframe-drive url="https://drive.google.com/file/d/1n9vA6F59hplkeXEkXU3c8O2Fttf88-sx/preview" >}}


<!-- {{< youtube oO5k-0QpxTk >}} -->
<!-- {{< pdf url="https://drive.google.com/file/d/1n9vA6F59hplkeXEkXU3c8O2Fttf88-sx/preview" fileName="nama file saya">}}
{{< iframe-drive url="https://drive.google.com/file/d/1n9vA6F59hplkeXEkXU3c8O2Fttf88-sx/preview" >}} -->