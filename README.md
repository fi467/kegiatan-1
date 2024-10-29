# HitungNilaiUTS

Kelas `HitungNilaiUTS` adalah program Java sederhana yang digunakan untuk menghitung nilai Ujian Tengah Semester (UTS) berdasarkan bobot dari komponen kehadiran, tugas, dan ujian. Program ini akan meminta pengguna untuk memasukkan nilai setiap komponen, menghitung nilai akhir berdasarkan bobot yang telah ditentukan, dan menampilkan hasilnya.

## Struktur Program
Program ini terdiri dari beberapa bagian:
- **Input Nilai**: Mengambil input nilai untuk komponen kehadiran, tugas, dan ujian dari pengguna.
- **Perhitungan Nilai UTS**: Menghitung nilai akhir UTS berdasarkan bobot dari masing-masing komponen.
- **Output Nilai UTS**: Menampilkan nilai akhir UTS dalam format desimal dua digit.

## Bobot Komponen
Setiap komponen memiliki bobot yang berbeda dalam perhitungan nilai akhir:
- Kehadiran: 20%
- Tugas: 30%
- Ujian: 50%

Nilai UTS dihitung menggunakan rumus berikut:
\[
\text{Nilai UTS} = (\text{Nilai Kehadiran} \times 0.2) + (\text{Nilai Tugas} \times 0.3) + (\text{Nilai Ujian} \times 0.5)
\]

## Prasyarat
Program ini membutuhkan JDK untuk menjalankan aplikasi berbasis Java. Untuk menguji kode ini, pengguna juga perlu menggunakan terminal atau IDE seperti Eclipse atau IntelliJ IDEA.

## Cara Menjalankan Program
1. Pastikan Java telah diinstal di sistem Anda.
2. Simpan file kode ini sebagai `HitungNilaiUTS.java`.
3. Buka terminal, lalu navigasikan ke folder tempat file disimpan.
4. Jalankan perintah berikut untuk mengompilasi program:
   ```bash
   javac HitungNilaiUTS.java
   ```
5. Jalankan program dengan perintah:
   ```bash
   java HitungNilaiUTS
   ```

## Contoh Penggunaan
Program akan meminta input untuk nilai kehadiran, tugas, dan ujian. Misalnya:
```
Masukkan nilai kehadiran (0-100): 80
Masukkan nilai tugas (0-100): 90
Masukkan nilai ujian (0-100): 85
Nilai UTS: 85.50
```

## Catatan
- Pastikan nilai yang dimasukkan berada dalam rentang 0 hingga 100.
- Program ini tidak memiliki validasi untuk nilai di luar rentang tersebut.
