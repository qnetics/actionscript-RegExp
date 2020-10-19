# actionscript-RegExp
_**BY : qywok**_
<hr>
RegExp (regular expression) adalah pola yang mendeskripsikan kumpulan kemungkinan string yang dapat dibentuk dengan pola tersebut, mengikuti aturan tertentu. Ekspresi reguler ini menggunakan tanda kurung (bulat, persegi, tanda kurung) dan karakter khusus yang membentuk aturan untuk membentuk kata, atau string apa pun.
Dalam ActionScript, pola RegExp ditulis dalam dua karakter garis miring "/" (/ regexp /).
Untuk memulai, mari kita lihat beberapa pola sederhana

- contoh regexp : **/s[ak]y/** dapat membentuk kata-kata kosong: "say and sky" (ekspresi ditambahkan dalam tanda kurung siku _"[ak]"_, disebut **class pattern**)
- Pola untuk string yang mungkin hanya berisi vokal: **/[aeiou]/** (dengan menempatkan huruf yang ingin Anda cocokkan di dalam tanda kurung siku: )
- Jika Anda ingin mengizinkan vokal huruf besar, tambahkan juga, **/[aeiouAEIOU]/** (atau Anda dapat menggunakan pengubah "i", **/[aeiou]/i** - pengubah penampilan bawah).
- Untuk string yang mungkin berisi huruf apa pun yang ditulis dalam huruf kecil, Anda dapat menulis: **/[abcdefghijklmnopqrstuvwxyz]/**. Atau Anda dapat menggunakan rentang dengan karakter tanda hubung (-): **/[a-z]/** (ekspresi ini berarti serangkaian karakter berurutan dari 'a' hingga 'z').
- Demikian pula, pattern **/[0-9]/** mewakili string yang hanya berisi angka.

**Untuk mencocokkan sejumlah karakter, letakkan kuantitas di antara tanda kurung kurawal, tambahkan jumlah minimum dan maksimum karakter yang diperbolehkan.**
- Misalnya regexp: **/[aeiou]{2,4}/**, cocok dengan string apa pun yang hanya berisi vokal dan memiliki 2, 3, atau 4 karakter ("ai", "oue", "auio", dll.).











terusin besok wkwkwk (mlz)
