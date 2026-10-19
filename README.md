# Aplikasi Manajemen Rental Kostum

Aplikasi desktop berbasis Java untuk membantu admin mengelola data kostum rental, termasuk kostum bertema anime dan game. Proyek ini dibuat sebagai proyek kelompok untuk menerapkan konsep Pemrograman Berorientasi Objek (PBO), pengelolaan data, dan pemisahan komponen aplikasi.

## Ringkasan Proyek
| Aspek | Keterangan |
|---|---|
| Jenis aplikasi | Aplikasi desktop |
| Bahasa | Java |
| Antarmuka | Java Swing/JFrame |
| Penyimpanan data | Database relasional melalui kelas koneksi database |
| Konsep utama | PBO, enkapsulasi, inheritance, CRUD, pemisahan Model–Control–View |
| Konteks | Proyek akhir kelompok mata kuliah Pemrograman Berorientasi Objek |

## Latar Belakang
Pengelolaan data kostum membutuhkan pencatatan yang rapi agar admin dapat melihat, menambahkan, memperbarui, dan menghapus informasi kostum. Aplikasi ini dibuat sebagai contoh sistem administrasi sederhana untuk kebutuhan rental kostum.

## Fitur Utama
- **Login dan menu admin** untuk mengakses fungsi pengelolaan.
- **Manajemen data kostum** untuk menambah, melihat, mencari, memperbarui, dan menghapus data sesuai implementasi.
- **Kategori kostum anime dan game** dengan atribut tambahan sesuai jenisnya.
- **Manajemen data admin/karyawan** yang tersedia pada aplikasi.
- **Tampilan desktop berbasis JFrame** untuk berinteraksi dengan fitur aplikasi.
- **Integrasi database** untuk menyimpan dan mengambil data aplikasi.

## Konsep Pemrograman yang Diterapkan
### Enkapsulasi
Atribut pada class model diatur menggunakan pembatasan akses dan metode getter/setter sesuai kebutuhan.

### Inheritance
Class turunan seperti `Costume_Anime` dan `Costume_Game` mengembangkan class dasar kostum dengan atribut yang lebih spesifik.

### Pemisahan tanggung jawab
Struktur proyek memisahkan model data, proses pengolahan, dan antarmuka agar kode lebih mudah ditelusuri:
- **Model:** entitas dan representasi data.
- **Control:** proses aplikasi, operasi CRUD, dan akses database.
- **View:** halaman dan komponen antarmuka pengguna.

## Diagram Perancangan

### Flowchart
![Flowchart aplikasi](https://github.com/selaputriismalia/Kelompok4_PA_PBO/assets/88119620/1b4d9d65-58ad-48e3-9f37-0cc30f00f030)

### Entity Relationship Diagram (ERD)
![ERD aplikasi](https://github.com/selaputriismalia/Kelompok4_PA_PBO/assets/88119620/64b2fe43-b2a0-4fbb-9583-3a792c1fde5b)

### Hirarki Class
![Hirarki class](https://github.com/selaputriismalia/Kelompok4_PA_PBO/assets/88119620/70c20e2b-9ddc-453e-841c-3bd74ad92a18)

## Struktur Repository
Struktur utama kode dibagi ke dalam package berikut:
```text
src/
├── Model/    # Class data/entitas, misalnya Costume dan turunannya
├── Control/  # Logika aplikasi dan operasi data
└── View/     # Antarmuka pengguna berbasis JFrame
```

Nama file dan struktur detail dapat dilihat langsung pada folder `src` di repository.

## Gambaran Alur Aplikasi
1. Admin membuka aplikasi dan masuk melalui halaman login.
2. Admin memilih menu pengelolaan yang tersedia.
3. Admin melakukan operasi pada data kostum atau data admin/karyawan.
4. Komponen kontrol memproses permintaan dan berinteraksi dengan database.
5. Hasil operasi ditampilkan kembali pada antarmuka aplikasi.

## Prasyarat dan Menjalankan Aplikasi
Repository ini merupakan proyek Java desktop yang terhubung ke database. Sebelum menjalankan aplikasi:
1. Siapkan Java Development Kit (JDK) yang sesuai dengan proyek.
2. Siapkan database dan struktur tabel yang digunakan oleh aplikasi.
3. Periksa kelas konfigurasi/koneksi database dan sesuaikan dengan lingkungan lokal.
4. Buka proyek menggunakan IDE Java yang mendukung struktur proyek ini.
5. Jalankan class utama atau form awal aplikasi sesuai konfigurasi proyek.

## Dokumentasi Visual
Repository ini menyertakan diagram flowchart, ERD, hierarki class, serta screenshot antarmuka untuk memperlihatkan rancangan dan tampilan aplikasi.

## Konteks dan Kontribusi
Proyek ini dikerjakan secara berkelompok. Dokumentasi ini menjelaskan cakupan sistem dan konsep yang diterapkan; saat menggunakan proyek ini sebagai portofolio, cantumkan secara spesifik bagian yang dikerjakan atau menjadi tanggung jawab pribadi agar kontribusi dapat dipahami dengan jelas.

---
**Repository:** [Kelompok4_PA_PBO](https://github.com/selaputriismalia/Kelompok4_PA_PBO)  
**Topik:** Java · Pemrograman Berorientasi Objek · Aplikasi Desktop · CRUD · Database
