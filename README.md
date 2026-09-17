# Pertemuan 03 Seleksi Python

**Nama:** Fahrezi sauqi alghani
**NIM:** 2225250029
**Kelas:** 3-E

## Tujuan

Tujuan dari tugas ini adalah untuk memahami dan menerapkan struktur seleksi dalam Python, yaitu `if`, `if-else`, kondisi majemuk, dan `nested if` melalui program analisis persamaan kuadrat.

## Cara Menjalankan

Program dapat dijalankan melalui terminal dengan perintah:

```bash
python3 tugas/analisis_persamaan_kuadrat.py
```

## Algoritma Tugas

1. Program meminta pengguna memasukkan nilai koefisien `a`, `b`, dan `c`.
2. Program mengecek apakah nilai `a` sama dengan 0.
3. Jika `a = 0`, program menampilkan bahwa input tersebut bukan persamaan kuadrat.
4. Jika `a` tidak sama dengan 0, program menghitung nilai diskriminan.
5. Jika diskriminan lebih besar dari 0, program menyatakan bahwa persamaan memiliki dua akar real yang berbeda.
6. Jika diskriminan sama dengan 0, program menyatakan bahwa persamaan memiliki satu akar real kembar.
7. Jika diskriminan kurang dari 0, program menyatakan bahwa persamaan tidak memiliki akar real.

## Hasil Pengujian

| No | Input (a, b, c) | Keluaran yang Diharapkan                       | Keluaran Aktual | Status   |
| -- | --------------- | ---------------------------------------------- | --------------- | -------- |
| 1  | 1, -5, 6        | Diskriminan = 1.00, dua akar real berbeda      | Sesuai          | Berhasil |
| 2  | 1, -4, 4        | Diskriminan = 0.00, satu akar real kembar      | Sesuai          | Berhasil |
| 3  | 1, 2, 5         | Diskriminan = -16.00, tidak memiliki akar real | Sesuai          | Berhasil |
| 4  | 0, 2, 3         | Bukan persamaan kuadrat                        | Sesuai          | Berhasil |

## Refleksi

Kesalahan logika yang ditemukan adalah lupa memberikan indentasi pada kode setelah `if` dan `else`. Dalam Python, indentasi sangat penting karena menunjukkan bagian kode yang termasuk dalam suatu kondisi. Kesalahan tersebut diperbaiki dengan memberikan indentasi pada setiap perintah yang berada di dalam `if`, `elif`, dan `else`. Setelah diperbaiki, program dapat berjalan dan memberikan keluaran sesuai dengan kondisi diskriminan. 
=======
# pertemuan-03-seleksi-2225250029
>>>>>>> 71154a276fa8af160ed80bdf3d00b1801e0cd79a
