# Webservice-DTD

ANALISIS:
1.	Dalam kode tersebut ada tag <?xml version="1.0" encoding="UTF-8"?> itu merupakan tag penting atau jantungnya dari xml, merupakan sebuah Instruksi Proses / direktif khusus untuk mengelola  xml, Jadi jika kita ingin membuat sebuah xml  maka Perintah tersebut harus ada, jika tidak maka srcpt tersebut tidak bisa di compile menjadi xml. Diawali <?....?>

2.	<!DOCTYPE  Motor [ - Deklarasi DOCTYPE memiliki tanda seru (!) Pada awal nama elemen. DOCTYPE menginformasikan parser yang DTD dikaitkan dengan dokumen XML ini.

3.	Beberapa elemen dinyatakan di sini yang membentuk kosakata dari <lampu> dokumen. <! lampu ELEMEN (#PCDATA)> mendefinisikan lampu elemen untuk menjadi tipe "#PCDATA".

4.	Dalam kode xml  tersebut memiliki element yang mempunyai 2 Sub element yaitu <Motor>..</ Motor> dan didalam sub tersebut mempunyai 5 data yaitu <lampu >….</lampu> , <ban >….</ban >, <stang> …</stang >, <handgrip> …</handgrip>, <rem> …</rem> didalam kode tersebut disematkan data-data yang akan dimunculkan. Jadi semua kode tersebut akan di compile.
