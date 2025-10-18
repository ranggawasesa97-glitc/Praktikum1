# Praktikum3: Menentukan Bilangan Terbesar dari 3 Bilangan (Python)

## Penjelasan Tugas
Tugas ini bertujuan untuk membuat program Python yang dapat menerima tiga buah input bilangan bulat dan menentukan serta mencetak bilangan mana yang memiliki nilai terbesar.

---

## Flowchart Program
<img width="775" height="648" alt="image" src="https://github.com/user-attachments/assets/455ab0d6-9eeb-4b31-b55f-759ab4fa596c" />




**Penjelasan Flowchart:**
Flowchart diawali dengan START, dilanjutkan dengan proses INPUT untuk tiga bilangan (bil1, bil2, bil3). Kemudian, program menggunakan serangkaian keputusan untuk membandingkan nilai-nilai tersebut.
1. Pertama, membandingkan bil1 dengan bil2 dan bil3. Jika bil1 lebih besar dari keduanya, maka bil1 adalah yang terbesar.
2. Jika tidak, program membandingkan bil2 dengan bil1 dan bil3. Jika bil2 lebih besar dari keduanya, maka bil2 adalah yang terbesar.
3. Jika kedua kondisi di atas tidak terpenuhi, secara otomatis bil3 adalah bilangan terbesar.
Hasil perbandingan (bilangan terbesar) akan dicetak melalui proses OUTPUT, dan alur program diakhiri dengan END.

---

## Kode Program (terbesar.py)

```python
A = int(input("bilangan 1: "))
B = int(input("bilangan 2: "))
C = int(input("bilangan 3: "))



if A >= B and A >= C:
    print("1 bilangan terbesar")
elif B >= A and B >= C:
    print("2 bilangan terbesar")
else:
    print("3 bilangan terbesar")

```
Penjelasan Kode Program:

1. Input: Program menggunakan input() dan diubah ke tipe int() untuk menerima tiga bilangan bulat. Blok try-except digunakan untuk menangani kesalahan jika input yang dimasukkan bukan angka.

2. Percabangan if-elif-else:

if A >= B and A >= C:: Mengecek apakah A lebih besar atau sama dengan kedua bilangan lainnya.

elif B >= A and B >= C:: Jika kondisi pertama salah, cek apakah B lebih besar atau sama dengan A dan C.

else:: Jika kedua kondisi di atas salah, maka otomatis C adalah yang terbesar.

3. Output: Bilangan terbesar dicetak menggunakan fungsi print().
---
## Hasil OUTPUT 
<img width="1869" height="404" alt="image" src="https://github.com/user-attachments/assets/4bae3503-75b3-4df2-8096-1b7146db7f48" />
