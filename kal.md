# Rangkuman: Sistem Persamaan Linear

Berdasarkan materi dari tautan komputasi aljabar linear tersebut, berikut adalah rangkuman mengenai konsep **Sistem Persamaan Linear**:

## 1. Definisi Persamaan Linear
Sebuah persamaan linear dalam $n$ variabel ($x_1, x_2, \dots, x_n$) adalah persamaan yang dapat disederhanakan ke dalam bentuk baku:
$$a_1x_1 + a_2x_2 + \dots + a_nx_n = b$$
di mana $a_1, a_2, \dots, a_n$ adalah bilangan real.
* **Homogen**: Persamaan disebut homogen jika konstanta $b = 0$.
* **Nonhomogen**: Persamaan disebut nonhomogen jika konstanta $b \neq 0$.
* **Nonlinear**: Persamaan yang tidak dapat disederhanakan ke bentuk baku menggunakan penjumlahan dan pengurangan dasar (misal: terdapat variabel kuadrat atau fungsi trigonometri seperti $\sin$).

## 2. Sistem Persamaan Linear
Sistem persamaan linear merupakan himpunan atau kumpulan dari beberapa persamaan linear. 
* Sistem ini dikatakan **homogen** apabila seluruh persamaan di dalam himpunan tersebut adalah persamaan homogen. 
* Dalam penulisan matematisnya, sistem ini sering menggunakan indeks ganda $a_{ij}$, di mana $i$ menunjukkan posisi baris (persamaan ke-$i$) dan $j$ menunjukkan posisi kolom (variabel ke-$j$).

## 3. Solusi Sistem Persamaan Linear
Solusi dari suatu sistem linear adalah himpunan nilai $(s_1, s_2, \dots, s_n)$ yang apabila disubstitusikan akan memenuhi **semua** persamaan dalam sistem tersebut. Terdapat tepat 3 kemungkinan himpunan solusi untuk sistem linear:
1. **Tidak ada solusi** (Himpunan kosong): Sistem diklasifikasikan sebagai sistem **tidak konsisten**.
2. **Memiliki tepat satu solusi** (Solusi tunggal): Sistem diklasifikasikan sebagai sistem **konsisten**.
3. **Memiliki tak hingga banyak solusi**: Sistem diklasifikasikan sebagai sistem **konsisten**.

## 4. Representasi Matriks
Sistem persamaan linear dapat direpresentasikan secara ringkas dengan notasi $\mathcal{LS}(A, \mathbf{b})$.
* **$A$** merupakan **Matriks Koefisien**, yaitu matriks yang berisi nilai-nilai koefisien dari variabel-variabel dalam sistem.
* **$\mathbf{b}$** merupakan **Vektor Konstanta**, yaitu vektor kolom yang berisi nilai dari konstanta (ruas kanan) masing-masing persamaan.

## 5. Matriks Augmentasi (*Augmented Matrix*)
Untuk mempermudah perhitungan, sistem persamaan linear direpresentasikan menggunakan matriks augmentasi yang ditulis dengan simbol $[A \mid \mathbf{b}]$.
* Matriks ini dibentuk dengan menggabungkan kolom-kolom matriks koefisien $A$ dan menambahkan vektor konstanta $\mathbf{b}$ sebagai kolom terakhir (kolom ke-$n+1$).
* Matriks ini merangkum seluruh informasi penting dari sebuah sistem persamaan dengan mengabaikan penulisan nama variabelnya, sehingga posisinya murni ditentukan oleh letak baris dan kolom.