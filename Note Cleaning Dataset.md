**Note Cleaning Dataset:**
1. Missing values di highlight dengan warna kuning (crtl+G - go to special - blanks)
2. Mengisi missing values di kolom "productname" dan "brand" dengan "UNKNOWN"
3. Mengisi kolom "unitprice" dengan median
4. Hitung nilai MEDIAN kolom "unitprice"
5. masukkan nilai median yg dihasilkan dalam kolom missing di "unitprice"
6. Ambil Value/ nilainya saja dari kolom "Rawweight" 
7. Ambil satuan nilai dari kolom "Rawweight"
8. Strandarisasi satuan pada kolom "weight\_unit" - ada satuan yang masih "aneh" tetapi dibiarkan terlebih dahulu
9. Encoding huruf "aneh-Ã© dll" dalam kolom "brand"
10. Standarisasi kolom "brand" untuk memastikan tulisan sama dg proper dan trim / penulisan nya disamakan
11. Isi kolom "productname" yang kosong dengan "Unknown" \& melakukan standarisari penulisan dengan proper \& trim
12. Menghapus 1 row dari kolom "orderdate" karena nilai kosong. jika mengisi tgl atau lainnya tidak bisa di rata2 dan membuat data tdk akurat. dan hanya 1 row yg kosong, tidak akan banyak mempengaruhi perubahan data
13. Kolom "country" menghapus prefix (en: .....) dan menggantinya dengan kosong-an
14. Kolom "country" mengubah nama negara (multibahasa) ex: alrgelia; maroc; dll menjadi nama negara standar yang diketahui dlm Bahasa inggris
15. Standarisasi penulisan menggunakan proper & trim
