# Tugas 3 Komstat
Topik: Random Number Generator (RNG)

# Soal 1
1. Buatlah sebuah fungsi pembangkit bilangan acak dengan fungsi Greenberger (Multiplicative congruential.) dengan ketentuan modifikasi sebagai berikut:
 * 	Xo = 11, a=7, c=5, m = $2^{32}$
 * 	Input fungsi adalah $N$ (jumlah bilangan yang akan dibangkitkan)
 *	Output fungsi adalah sebuah skalar: rata-rata semua $N$ suku dibarisan yang dibangkitkan. 
 *  Jangan lupa untuk menormalisasi semua sukunya dengan $m$.

2. Jika $X = x_1, x_2, ..., x_N$ adalah barisan $N$ output dari fungsi diatas, apakah distribusi dari $X$? Jelaskan.

3. Apakah $X$ memiliki periode? jelaskan.

# Soal 2
Algoritma untuk menghasilkan bilangan random diskrit berdistribusi Poisson dapat anda temukan dari beberapa sumber di dunia maya: https://www.google.com/search?q=algorithm+generate+poisson+distribution&newwindow=1&sxsrf=ALiCzsbKw0SJtuLmaOS3B9XNVrTNtbeuXw:1665702878239&source=lnms&tbm=isch&sa=X&ved=2ahUKEwixjO_iqt76AhXpcGwGHavxB88Q_AUoAXoECAEQAw#imgrc=pnIy3d_qBdlPnM 

1. Aplikasikan algoritma tersebut dengan bahasa Python (tanpa menggunakan module : Pure Python).

2. Bandingkan hasil anda (melalui visualisasi) dengan distribusi Python yang dihasilkan oleh Numpy menggunakan 100.000 sample.
 - https://numpy.org/doc/stable/reference/random/generated/numpy.random.poisson.html

# Soal 3
* Keterangan Metode Crude Monte Carlo adalah sebagai berikut: https://www.google.com/search?q=%22Crude+monte+carlo%22+integral&oq=%22Crude+monte+carlo%22+integral&aqs=edge..69i57.8774j0j1&sourceid=chrome&ie=UTF-8

* Menggunakan fungsi yang sama dengan yang ada di module kuliah $$\theta = \int_0^1 \frac{e^x-1}{e-1} dx$$
Tentukan:
1. Solusi Pendekatannya menggunakan Crude MC dengan N = 100
2. Bandingkan hasil pendekatan anda dengan solusi eksak dan solusi hit-or-miss
3. Buatlah selang kepercayaan 95% dari solusi MC ini.
