[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/dyiPpHu0)


# Tech Company Profile RiamiTech

Ini adalah situs web Profil Perusahaan Teknologi sederhana yang dibuat menggunakan HTML dan CSS tanpa kerangka kerja apa pun. Ini memberikan gambaran umum tentang perusahaan teknologi dengan bagian seperti "Tentang Kami", "Layanan", dan "Kontak".

## Link Website RiamiTech
- Live Site: [RiamiTech](https://dapurku.site/).

## Fitur

Adapun fitur pada website sebagai berikut:

- Structur Semantic HTML5
- Navbar
- List Layanan
- Kontak Form dengan variasi input data

## Setup dan Instalasi

1. **Clone Repository**  
   Clone Repositori ke dalam komputer anda:  
   ```bash  
   git clone https://github.com/revou-fsse-oct24/milestone-1-ridwanam9.git   
2. **Masuk Ke Projek**  
   Pindah ke directori project:  
   ```bash  
    cd milestone-1-ridwanam9.git   

3. **Buka di Browser**  
   Buka file index.html di browser web apa pun untuk melihat situs web:  
    ```plaintext
    Klik kanan pada index.html -> Buka dengan -> Browser Anda 

Alternatifnya, Anda dapat menggunakan ekstensi live server di editor kode Anda (misalnya, VS Code).

## Penggunaan

1. Sesuaikan konten dalam file index.html agar sesuai dengan profil perusahaan Anda.
2. Ubah gaya dalam file style.css untuk memperbarui tampilan dan nuansa situs web.
3. Tambahkan gambar atau file tambahan di folder aset (jika ada).

## Struktur Proyek

    ```
    /project-folder
    │
    ├── index.html                  # Halaman utamawebsite
    ├── style.css                   # File utama styling

    ├── /assets                     # Folder Gambar 
    │   ├── /images                 # Gambar Pengembanagn
    │   └── /image_documentations   # Gambar Dokumentasi
    │
    └── README.md                   # Dokumentasi proyek
    ```


## Kontribusi

Jika Anda ingin berkontribusi untuk meningkatkan proyek ini:

1. Fork repository ini.
2. Buat branch untuk perubahan Anda (git checkout -b feature-nama-fitur).
3. Commit perubahan Anda (git commit -m 'Menambahkan fitur X').
4. Push ke branch Anda (git push origin feature-nama-fitur).
5. Buat Pull Request.


# Tahap Pengembangan

1. Header
![Header](assets/images/header_code.png)
![Header](assets/images/header.png)


2. Hero Section
![Hero](assets/images/herocode.png)
![Hero](assets/images/hero.png)

3. About Section
![About](assets/images/aboutcode.png)
![About](assets/images/about.png)

4. Services Section
![Services](assets/images/servicescode.png)

5. Contact Section
![Contact](assets/images/contactcode.png)
![Contact](assets/images/contact.png)

6. Footer
![Footer](assets/images/footercode.png)
![Footer](assets/images/footer.png)

> Note: Tampilan di atas belum termasuk styling dan mungkin membutuhkan pengembangan lebih lanjut.

# Dependencies
Proyek ini menggunakan beberapa dependencies eksternal untuk meningkatkan desain dan fungsionalitas:

1. **Font Awesome**  
   - **URL**: [https://fontawesome.com](https://fontawesome.com)  
   - **Penggunaan**:  
     Digunakan untuk ikon pada bagian "Services". Contohnya:
     ```html
     <i class="fas fa-laptop-code"></i>
     ```
     Link CDN Font Awesome disertakan di dalam `<head>`:
     ```html
     <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
     ```

2. **Animasi Keyframes CSS**  
   Animasi yang digunakan seperti fadeInUp didefinisikan langsung di file CSS tanpa menggunakan library eksternal.
   ```css
   /* Keyframes for Animation */
    @keyframes fadeInUp {
        from {
            opacity: 0;
            transform: translateY(20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }


## Pilihan Desain

### 1. **Tipografi dan Keterbacaan**
   - Ukuran font dasar diatur ke 18px, dengan judul yang lebih besar untuk kejelasan. Pada perangkat seluler, ukuran font dikurangi menjadi 15 piksel untuk mengoptimalkan keterbacaan.
   - Ukuran judul disesuaikan menggunakan unit `rem` untuk menjaga skala yang konsisten di berbagai ukuran layar.

### 2. **Tata Letak**
   - Sistem grid yang fleksibel digunakan untuk mengatur konten secara efisien, khususnya di services card dan bagian "Tentang Kami", yang beradaptasi dari tata letak horizontal ke vertikal pada layar yang lebih kecil.
   - Tata letaknya responsif, dengan media query menyesuaikan desain untuk layar yang lebih sempit dari 768 piksel. Hal ini mencakup perubahan pada ukuran font, susunan tata letak, dan perilaku navigasi.

### 3. **Navigasi dan Responsif Seluler**
   - Bar navigasi dipasang di bagian atas halaman untuk memudahkan akses.
   - Menu hamburger disertakan untuk perangkat seluler. Menu muncul ketika kotak centang dicentang, memungkinkan pengguna untuk mengubah visibilitas link navigasi.
   - Pada layar yang lebih kecil, link menu ditumpuk secara vertikal, dan header lebih ringkas untuk memaksimalkan ruang yang tersedia.

### 4. **Skema Warna**
   - Warna utama (`#0066cc`) digunakan untuk header, tautan, dan tombol ajakan bertindak untuk menciptakan tampilan profesional dan kohesif.
   - Warna sekunder (`#00aaff`) digunakan untuk efek hover dan elemen aksen guna menarik perhatian dan menciptakan kontras.
   - Latar belakang berwarna putih (`#ffffff`), dengan teks dalam nuansa gelap (`#333333`) agar lebih mudah dibaca.

### 5. **Animasi**
   - Situs web menggunakan animasi `fadeInUp` untuk efek masuk yang lancar pada bagian pahlawan dan bagian konten (Tentang Kami, Layanan).
   - Animasi meningkatkan pengalaman pengguna dengan memberikan interaksi visual tanpa membebani konten.

### 6. **Bentuk dan Aksesibilitas**
   - Bidang formulir ditata untuk memudahkan interaksi, dengan label dan placeholder yang tepat.
   - Atribut `aria-labelledby` digunakan untuk dukungan pembaca layar yang lebih baik, memastikan bahwa semua pengguna dapat menavigasi situs secara efektif.

