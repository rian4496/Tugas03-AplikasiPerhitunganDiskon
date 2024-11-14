# Tugas03-AplikasiPerhitunganDiskon
 Tugas03-M. Rian Gunadi-2210010497

![gambar](https://github.com/user-attachments/assets/3f47b1d3-481e-41a2-bc36-aef605f95241)

![gambar](https://github.com/user-attachments/assets/f79e4989-cb2a-4875-a663-309e937a2ff7)

# Aplikasi Perhitungan Diskon

AplikasiPerhitunganDiskon adalah aplikasi desktop berbasis Java yang memungkinkan pengguna untuk menghitung diskon harga dengan opsi tambahan kupon. Aplikasi ini menyediakan antarmuka pengguna sederhana berbasis Swing untuk memasukkan harga, memilih diskon, memasukkan kode kupon, dan menampilkan hasil perhitungan secara interaktif.

## Fitur Utama

- **Perhitungan Diskon Dinamis**: Memungkinkan pengguna untuk memilih diskon dari `JComboBox` dan menyesuaikan diskon menggunakan `JSlider`.
- **Validasi Input Harga**: Mengecek apakah input harga valid dan tidak negatif, dengan notifikasi kesalahan jika tidak sesuai.
- **Kode Kupon Diskon**: Mendukung kode kupon `DISKON10` dan `DISKON20` untuk menambahkan diskon tambahan.
- **Riwayat Perhitungan**: Menyimpan dan menampilkan riwayat setiap perhitungan diskon dalam `txtRiwayat`.
- **Antarmuka Ramah Pengguna**: Dibangun dengan komponen GUI Swing, aplikasi ini menawarkan antarmuka yang mudah dipahami.

## Cara Menggunakan Aplikasi

1. **Input Harga**: Masukkan harga barang yang ingin dihitung di kolom `txtInput`.
2. **Pilih Diskon**: Pilih persentase diskon di `cbbDiskon` atau gunakan `JSlider` untuk mengubah nilai diskon.
3. **Kode Kupon** (Opsional): Masukkan kode kupon `DISKON10` atau `DISKON20` di kolom `txtKodeKupon` untuk diskon tambahan.
4. **Hitung Diskon**: Klik tombol `Hitung` untuk melakukan perhitungan.
5. **Lihat Hasil**: Hasil perhitungan berupa jumlah yang dihemat (`txtJumlahHemat`) dan harga akhir (`txtAkhir`) akan ditampilkan.
6. **Riwayat Perhitungan**: Semua perhitungan yang dilakukan akan ditambahkan ke `txtRiwayat` untuk referensi lebih lanjut.

## Struktur Program

- **`hitungDiskon`**: Metode untuk melakukan perhitungan diskon berdasarkan input harga, diskon dari `JComboBox`, dan diskon kupon jika ada.
- **Antarmuka Pengguna (GUI)**: Dibangun menggunakan Java Swing dengan berbagai komponen, termasuk `JTextField`, `JComboBox`, `JSlider`, dan `JTextArea` untuk menampilkan riwayat.
- **Validasi Input**: Mengecek apakah harga yang dimasukkan valid (tidak kosong atau negatif).
  
## Kode Utama

Kode utama aplikasi terdapat dalam kelas `AplikasiPerhitunganDiskon` yang menginisialisasi komponen GUI dan mendefinisikan metode untuk menangani perhitungan diskon serta perubahan nilai pada `JSlider` dan `JComboBox`.

## Lisensi

Aplikasi ini dilisensikan di bawah MIT License.
