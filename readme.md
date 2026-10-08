# Praktikum 3: CSS Dasar - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 3 Pemrograman Web.

## Identitas Mahasiswa

| Keterangan      | Data                 |
| --------------- | ---------------      |
| **Nama**        | Najhan Said Ziddan|
| **Kelas**       | I251D                |
| **NIM**         | 312510367		|
| **Mata Kuliah** | Pemrograman Web      |

### Tujuan Praktikum

Mahasiswa mampu memahami konsep dasar CSS.

Mahasiswa mampu memahami aturan penulisan pada CSS (Internal, Eksternal, dan Inline).

Mahasiswa mampu memahami selector sebagai pengontrol CSS (Elemen, ID, dan Class).

Mahasiswa mampu membuat pengaturan CSS pada HTML.

---

## Struktur Folder Proyek

```
Lab3Web/
├── Lab3_css_dasar.html
├── style_eksternal.css
└── README.md

```
## 1. Struktur File

Struktur file pada praktikum ini adalah sebagai berikut:

<img width="331" height="167" alt="Screenshot 2026-10-08 141402" src="https://github.com/user-attachments/assets/82b62df0-0bdf-4720-a39d-5285655fe107" />

## Langkah-langkah Praktikum

### 1. Membuat Dokumen HTML Dasar

Langkah pertama adalah membuat dokumen HTML dasar dengan nama lab2_css_dasar.html. Dokumen ini menggunakan struktur HTML5 yang berisi elemen-elemen seperti header, <nav>, dan <div> untuk menyusun kerangka halaman web.

<img width="1008" height="633" alt="ss halaman 1" src="https://github.com/user-attachments/assets/2f1b9e3a-f019-4f1f-b4c1-6d72b14a22e3" />

Selanjutnya buka pada brwoser untuk melihat hasilnya.

<img width="1365" height="462" alt="hasil ss halaman 1" src="https://github.com/user-attachments/assets/6ed04050-a57a-47a0-918a-0d30849cdb49" />

### 2. Mendeklarasikan CSS Internal

CSS Internal ditulis di dalam tag <style> yang diletakkan pada bagian <head> dokumen HTML. Pada langkah ini, gaya ditambahkan untuk memodifikasi elemen body, header, dan teks h1.

<img width="996" height="492" alt="ss halaman 2" src="https://github.com/user-attachments/assets/b10e0bf9-ba08-40e8-952d-5783594fe32c" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1365" height="517" alt="hasil ss halaman 2" src="https://github.com/user-attachments/assets/679d48f7-ca9f-4bad-8769-bf08a3d2ea2e" />

### 3. Menambahkan Inline CSS

Inline CSS ditulis langsung di dalam baris tag HTML sebagai atribut style. Pada praktikum ini, inline CSS diterapkan pada tag <p> untuk mengubah perataan teks menjadi ke tengah (center) dan mengubah warna tulisan. Gaya ini hanya berdampak pada satu baris elemen tersebut.

<img width="866" height="57" alt="ss 3" src="https://github.com/user-attachments/assets/a5c8c50b-3a0f-4b5f-8e7d-f53fae905f98" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1361" height="452" alt="ss hasil 3" src="https://github.com/user-attachments/assets/02f6451d-23c8-4df4-b8ea-dfcc101f9493" />


### 4. Membuat CSS Eksternal

CSS Eksternal dipisahkan ke dalam file khusus bernama style_eksternal.css. File ini kemudian dihubungkan ke dokumen HTML menggunakan tag <link rel="stylesheet" href="style_eksternal.css">. Metode ini sangat efisien untuk mengatur gaya di banyak halaman sekaligus.

<img width="1022" height="427" alt="ss ke 4" src="https://github.com/user-attachments/assets/5ab7803d-c804-4ffc-bb35-c76136e57338" />

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian
<head>

<img width="587" height="85" alt="Screenshot 2026-10-08 143445" src="https://github.com/user-attachments/assets/66b2cbe9-48f4-4093-b3db-ca2484edc388" />


Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1365" height="560" alt="hasil ss 4" src="https://github.com/user-attachments/assets/998c3498-cf58-4497-ac56-8a6da2b41d6c" />


### 5. Menambahkan CSS Selector (ID dan Class)

Selector digunakan untuk memilih secara spesifik elemen mana yang akan diubah gayanya:

ID Selector (#): Diterapkan pada elemen spesifik (contoh: #intro). ID bersifat unik dan hanya boleh digunakan satu kali pada satu halaman.

Class Selector (.): Digunakan untuk mengelompokkan beberapa elemen (contoh: .button). Class bisa digunakan berulang kali pada elemen-elemen yang berbeda.

<img width="985" height="363" alt="ss ke 5" src="https://github.com/user-attachments/assets/0d3269f3-f85e-429f-844e-3db24280bb87" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1365" height="538" alt="hasil ss  ke 5" src="https://github.com/user-attachments/assets/b8be2257-1d4f-4784-aed5-19592c5b987a" />


### 6. Validasi Dokumen CSS (W3C Validator)

Melakukan pengujian kode pada style_eksternal.css menggunakan layanan W3C CSS Validator. Hasil pengecekan menunjukkan pesan "Tidak ditemukan kesalahan", yang berarti kode yang ditulis sudah valid dan sesuai dengan standar web internasional.

<img width="1365" height="723" alt="ss validasi css ss" src="https://github.com/user-attachments/assets/68a29d00-49a7-4da4-8afa-2235089f33b0" />
