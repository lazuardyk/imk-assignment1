# Insiden Kapal Ferry New York 2013
Pada pagi hari tanggal 9 Januari 2013, sekitar 326 orang menaiki kapal Ferry yang menyeberangi sungai dari Seastreek ke Wall Street. Saat kapal ingin bersandar, bukannya memperlambat kapal malah menaikkan kecepatannya dan menabrak dermaga dengan kecepatan 12 knots atau setara dengan 14 mph. Kejadian ini menyebabkan sekitar 85 orang terluka di mana 83 orang terluka ringan sementara 2 lainnya terluka parah. \
Link berita: (https://edition.cnn.com/2013/01/09/us/new-york-ferry-accident/index.html)
![Korban](Korban.jpg)

## Penyebab
Kejadian ini disebabkan oleh kelalaian kapten kapal saat ingin berlabuh di dermaga. Sebelum berlabuh, kapten kapal merasakan getaran pada kapalnya dan mengira ada sesuatu yang menyangkut di baling=baling kapal. Kapten kapal lalu mengganti mode kendali menjadi *backup mode* di mana dia bisa mengontrol baling-baling secara manual. Nahas, ketika ingin berlabuh kapten kapal lupa mengganti mode kendali ke mode normal sehingga manuver yang dilakukan kapten kapal bukannya memperlambat malah mempercepat laju kapal. Kapten kapal dikenal sebagai kapten yang mahir dan berpengalaman. Dia bahkan menjadi trainer bagi kapten lain tentang *piloting system* ini.

## Design Error
![Controller](Boat_Controller_NTSB.png) \
Konsol pengemudi memiliki 3 sisi, 1 untuk setiap sisi kapal dan 1 di tengah. Ketika ingin berlabuh, kapten mengikuti prosedur dengan cara memindahkan kontrol ke konsol di sisi kanan sehingga dia bisa melihat dermaga. Saat dia menyadari
ferry tidak melambat, dia berpindah ke konsol tengah, berpikir bahwa dia mungkin telah melakukan kesalahan saat mentransfer kontrol. Tapi sekali lagi, kapal tidak merespon. Dalam detik-detik yang dia miliki sebelum tabrakan, dia berpindah dari satu panel kontrol ke panel lainnya, tanpa menyadari dia telah salah mendiagnosis masalah tersebut. \
Kesalahan disebabkan:
- Design tombol dari controller terlalu kecil dan indikatornya hanya titik merah kecil yang menyala jika mode on. Hal ini menyulitkan kapten untuk menyadari dia sedang di mode yang mana.
- Tombol susah dicari karena ukuran sama dan cara penggunaannya sama.
- Banyak tombol yang tidak memiliki label sehingga membingungkan *user* karena tombol tidak diketahui fungsinya dan membuat visualisasi jadi lebih kecil dan sempit

## Improvement
- Visual status dibuat lebih mudah dilihat agar user bisa dengan mudah mengetahui sedang berada di mode yang mana
- Perbedaan bentuk dan penggunaan tombol agar tidak terjadi kesalahan saat memencet tombol yang disebabkan oleh ketidaksengajaan.
- Menghilangkan tombol yang tidak berlabel agar ukuran tombol lebih luas dan besar

## UX Mockup Revised
![UXRevised](ControllerRevised.jpg)

