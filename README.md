# ANALISISDATAGAJI
Natasya Kayla Najla_12030122140218
Berikut adalah interpretasi dari data yang terdapat dalam file `Natasya.csv`:

### Deskripsi Umum Data
Data dalam `data_baru.csv` terdiri dari 10 baris dengan 4 kolom yang menggambarkan informasi tentang karyawan dalam sebuah perusahaan. Kolom-kolom tersebut adalah:

- `age`: Usia karyawan dalam tahun.
- `salary`: Gaji karyawan dalam USD per tahun.
- `gender`: Jenis kelamin karyawan (male atau female).
- `department`: Departemen tempat karyawan bekerja.

### Lima Baris Pertama Data
```
   age  salary  gender   department
0   25   50000    male  Engineering
1   30   60000  female   Marketing
2   35   70000    male  Engineering
3   28   48000  female       Sales
4   40   80000    male   Marketing
```

### Informasi Umum tentang Data
- Kolom `age` dan `salary` memiliki tipe data numerik (int64).
- Kolom `gender` dan `department` memiliki tipe data objek (string).
- Tidak ada nilai yang hilang (missing values) dalam dataset ini.

### Ringkasan Statistik
```
             age        salary
count  10.000000     10.000000
mean   35.200000  67300.000000
std     7.782010  15136.679142
min    25.000000  48000.000000
25%    29.000000  53000.000000
50%    34.500000  67500.000000
75%    39.500000  79500.000000
max    50.000000  90000.000000
```
- Usia rata-rata karyawan adalah sekitar 35 tahun.
- Gaji rata-rata karyawan adalah sekitar 67,300 USD per tahun.
- Usia tertua adalah 50 tahun dan usia termuda adalah 25 tahun.
- Gaji tertinggi adalah 90,000 USD dan gaji terendah adalah 48,000 USD.

### Jumlah Data yang Hilang dalam Setiap Kolom
```
age          0
salary       0
gender       0
department   0
dtype: int64
```
- Tidak ada nilai yang hilang dalam dataset ini.

### Jumlah Nilai Unik dalam Setiap Kolom
```
age           10
salary        10
gender         2
department     4
dtype: int64
```
- Kolom `age` dan `salary` memiliki 10 nilai unik, menunjukkan bahwa setiap karyawan memiliki usia dan gaji yang berbeda.
- Kolom `gender` memiliki 2 nilai unik: male dan female.
- Kolom `department` memiliki 4 nilai unik: Engineering, Marketing, Sales, dan HR.

### Tipe Data dari Setiap Kolom
```
age            int64
salary         int64
gender        object
department    object
dtype: object
```
- `age` dan `salary` bertipe numerik (int64).
- `gender` dan `department` bertipe objek (string).

### Visualisasi Data
1. **Scatter Plot (Age vs. Salary)**
   - Menunjukkan hubungan antara usia dan gaji karyawan.
   - Tidak ada pola yang jelas yang menunjukkan hubungan langsung antara usia dan gaji.

2. **Histogram (Salary)**
   - Menunjukkan distribusi gaji karyawan.
   - Gaji berkisar antara 48,000 USD hingga 90,000 USD, dengan kebanyakan karyawan memiliki gaji di sekitar rata-rata.

3. **Box Plot (Age)**
   - Menunjukkan distribusi usia karyawan.
   - Usia karyawan berkisar dari 25 hingga 50 tahun, dengan sebagian besar karyawan berada di sekitar usia rata-rata.

4. **Bar Plot (Gender)**
   - Menunjukkan jumlah karyawan berdasarkan jenis kelamin.
   - Jumlah karyawan pria dan wanita hampir sama.

![Screenshot 2024-06-06 213124](https://github.com/natasyakaylanajla/ANALISISDATAGAJI/assets/167093710/8219a0b9-58b2-4c39-8bb5-1ae6ee19a494)

### Kesimpulan
- Dataset ini memberikan gambaran umum tentang usia, gaji, jenis kelamin, dan departemen dari 10 karyawan dalam sebuah perusahaan.
- Data ini seimbang dalam hal distribusi jenis kelamin dan mencakup berbagai departemen.
- Analisis visual menunjukkan distribusi yang bervariasi dalam usia dan gaji karyawan.
