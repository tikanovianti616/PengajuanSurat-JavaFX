# Aplikasi Pengajuan Surat Sekretariat (JavaFX)

Aplikasi desktop berbasis JavaFX untuk pengajuan surat, unduh dokumen PDF, dan verifikasi akses khusus bagi sekretaris.

## Fitur & Cara Penggunaan
### 1. Form Pengajuan Surat (Public User)
* **Deskripsi**: Formulir terbuka bagi pemohon untuk mengajukan permohonan surat baru tanpa perlu melakukan login.
* **Cara Penggunaan**:
  1. Pilih tab/menu **Pengajuan Surat**.
  2. Isi identitas lengkap pemohon dan data permohonan pada form yang tersedia.
  3. Klik tombol **Kirim / Submit** untuk menyimpan data permohonan dan mendapatkan Kode Tracking.

<img width="1600" height="900" alt="WhatsApp Image 2026-11-02 at 09 43 19" src="https://github.com/user-attachments/assets/0c2b4844-a623-4ec1-9e72-2bd3984f8d06" />

<img width="1600" height="900" alt="WhatsApp Image 2026-11-02 at 09 43 33" src="https://github.com/user-attachments/assets/d25c4f54-447c-4702-93ee-416c90df2c79" />


---

### 2. Unduh Surat (Public User)
* **Deskripsi**: Fitur untuk mengunduh berkas fisik dalam format PDF setelah disetujui.
* **Cara Penggunaan**:
  1. Masukkan **Kode Tracking** permohonan pada kolom pencarian.
  2. Klik tombol **Cari / Track**.
  3. Jika berkas sudah selesai diproses, klik tombol **Unduh Dokumen (PDF)** untuk menyimpan surat.

<img width="1600" height="900" alt="WhatsApp Image 2026-11-02 at 09 42 17" src="https://github.com/user-attachments/assets/9b36cd91-fa2c-47eb-af85-d4a499733ed6" />

---

### 3. Login Modal Sekretariat (Restricted Access)
* **Deskripsi**: Jendela autentikasi *popup modal* untuk mengunci hak akses fitur internal khusus petugas sekretaris.
* **Cara Penggunaan**:
  1. Klik tombol **Login Sekretaris** di pojok kanan atas aplikasi.
  2. Masukkan Username (`admin`) dan Password (`admin123`).
  3. Klik **Submit/Login** untuk membuka panel kontrol sekretariat.

<img width="1600" height="900" alt="WhatsApp Image 2026-11-02 at 09 39 43" src="https://github.com/user-attachments/assets/9eadfe21-0943-484b-9ef2-ac911ddc7161" />

---

## 🧰 Teknologi & Persyaratan Sistem
- **Language**: Java (JDK 17+)
- **GUI Framework**: JavaFX & FXML
- **IDE**: Apache NetBeans
- **Build Tool**: Maven

---

## 🚀 Cara Menjalankan Aplikasi

1. Clone atau unduh repository ini.
2. Ekstrak file `src.pengajuansurat.zip` ke dalam direktori project.
3. Buka folder project menggunakan **Apache NetBeans IDE**.
4. Pastikan dependensi Maven ter-load dengan benar (`pom.xml`).
5. Run class utama project (`App.java` / `Main.java`).
