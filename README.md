 Latihan 1 - Riska Ariana 2210010057

 # Aplikasi Pertambahan Dua Angka

Aplikasi ini adalah program sederhana berbasis Java Swing yang digunakan untuk menjumlahkan dua angka. Dengan antarmuka grafis yang sederhana, pengguna dapat memasukkan dua angka dan mendapatkan hasil penjumlahan.

## Fitur
- Menambahkan dua angka yang dimasukkan oleh pengguna.
- Membersihkan input dan hasil dengan tombol "Hapus".
- Keluar dari aplikasi dengan tombol "Keluar".
- Validasi input untuk memastikan hanya angka yang dapat dimasukkan.
- Input secara otomatis dibersihkan saat mendapatkan fokus.

## Cara Penggunaan
1. Masukkan angka pertama pada bidang input **Masukkan Angka Pertama**.
2. Masukkan angka kedua pada bidang input **Masukkan Angka Kedua**.
3. Klik tombol **Hitung** untuk mendapatkan hasil penjumlahan.
4. Klik tombol **Hapus** untuk menghapus semua input dan hasil.
5. Klik tombol **Keluar** untuk menutup aplikasi.

## Teknologi yang Digunakan
- **Java**: Bahasa pemrograman utama.
- **Java Swing**: Untuk membangun antarmuka grafis aplikasi.

## Struktur Kode
- **`AplikasiPertambahanDuaAngkaFrame`**: Kelas utama yang mengimplementasikan seluruh logika aplikasi.
- Menggunakan **GridBagLayout** untuk tata letak komponen.
- Event listeners:
  - **ActionListener** untuk menangani aksi tombol.
  - **KeyAdapter** untuk validasi input angka.
  - **FocusAdapter** untuk membersihkan input saat mendapatkan fokus.

## Validasi Input
Program hanya menerima angka (termasuk desimal dengan titik "."). Jika input tidak valid, akan muncul pesan kesalahan menggunakan **JOptionPane**.

## Menjalankan Program
1. Pastikan Anda memiliki **JDK** (Java Development Kit) yang terinstal.
2. Kompilasi program:
   ```bash
   javac AplikasiPertambahanDuaAngkaFrame.java

