# Folder untuk Matkul PBO02

**Nama:** Muhammad Adam Alghifari  
**NPM:** 2210010314  
**Kelas:** 5B Reg Pagi BJB  

---

# Panduan

## 1. Latihan 1: Aplikasi Pertambahan Dua Angka

### Deskripsi Program:
- Pengguna memasukkan dua angka.
- Tombol **Tambah** menampilkan hasil pertambahan.
- Tombol **Hapus** menghapus nilai di TextField dan mengarahkan fokus ke TextField angka pertama.
- Tombol **Keluar** keluar dari aplikasi.

### Komponen GUI:
- JFrame
- JPanel
- JLabel
- JTextField
- JButton

### Logika Program:
- Penambahan dua angka dan validasi input numerik.

### Events:
- **ActionListener** untuk tombol Tambah, Hapus, dan Keluar.

### Variasi:
- **KeyAdapter** pada JTextField untuk membatasi input hanya angka.
- Menggunakan **JOptionPane** untuk menampilkan error input.
- **FocusListener** untuk membersihkan JTextField saat mendapatkan fokus.

---

## 2. Latihan 2: Aplikasi Penghitung Umur

### Deskripsi Program:
- Pengguna memilih tanggal lahir dari **JDateChooser**.
- Setelah menekan tombol **Hitung**, umur dalam tahun, bulan, dan hari ditampilkan.

### Komponen GUI:
- JFrame
- JPanel
- JLabel
- JDateChooser
- JButton

### Logika Program:
- Perhitungan selisih waktu menggunakan **LocalDate**.

### Events:
- **ActionListener** untuk tombol Hitung.
- **PropertyChangeListener** pada JDateChooser untuk deteksi perubahan tanggal.

### Variasi:
- Sediakan informasi tambahan seperti hari ulang tahun berikutnya.
- Integrasikan dengan API eksternal untuk menampilkan peristiwa penting pada tanggal lahir.

---
