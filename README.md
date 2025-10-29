## 🔧 **lab6web**

### 1. Identitas

* **Nama:** Razy Al Farisi
* **NIM:** 312410524
* **Kelas:** TI.24.A5

---

### 2. Struktur Dasar HTML + Bootstrap

Buat file `index.html` dengan isi berikut:

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praktikum 6 - CSS Framework (Bootstrap)</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- Header -->
    <header class="bg-primary text-white text-center py-3">
        <h1>Selamat Datang di Website Saya</h1>
        <p>Belajar CSS Framework (Bootstrap)</p>
    </header>

    <!-- Navigasi -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">MyWeb</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Konten Utama -->
    <main class="container my-4">
        <div class="row">
            <!-- Sidebar -->
            <aside class="col-md-4">
                <div class="card mb-3">
                    <div class="card-header bg-secondary text-white">Sidebar</div>
                    <div class="card-body">
                        <p>Ini adalah area sidebar. Kamu bisa menambahkan link, informasi, atau widget di sini.</p>
                    </div>
                </div>
            </aside>

            <!-- Konten -->
            <section class="col-md-8">
                <div class="card">
                    <div class="card-header bg-info text-white">Konten Utama</div>
                    <div class="card-body">
                        <p>Bootstrap adalah framework CSS yang memudahkan pembuatan layout web secara responsif dan cepat.</p>
                        <p>Dengan menggunakan komponen seperti grid, card, navbar, dan alert, kamu dapat membangun tampilan profesional dengan sedikit kode CSS.</p>
                    </div>
                </div>
            </section>
        </div>
    </main>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 - Praktikum Web Framework by Razy Al Farisi </p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

---

### 3. Validasi HTML

* Buka situs: [http://validator.w3.org](http://validator.w3.org)
* Upload file `index.html` atau masukkan URL (jika sudah online).
* Pastikan hasil validasi **tidak ada error besar**.

---

## 🧾 **Laporan Praktikum (README.md)**

Berikut template laporan yang bisa langsung kamu jadikan file `README.md` untuk GitHub:

````markdown
# Praktikum 6: Web Framework (Bootstrap)

## Tujuan
1. Mahasiswa mampu memahami konsep dasar web framework.  
2. Mahasiswa mampu memahami struktur layout web menggunakan CSS framework.  
3. Mahasiswa mampu memahami elemen-elemen dalam CSS framework.

---

## Instruksi Praktikum
1. Persiapkan text editor (VSCode).  
2. Buat folder `lab6_css_framework`.  
3. Buat file `index.html`.  
4. Buat struktur dasar HTML.  
5. Gunakan CSS framework **Bootstrap** untuk membuat layout web sederhana.  
6. Lakukan validasi HTML menggunakan [validator.w3.org](http://validator.w3.org).

---

## Langkah Pengerjaan

### 1. Membuat Struktur Dasar HTML
Membuat file `index.html` dan menambahkan link CDN Bootstrap.

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
````

### 2. Membuat Layout Web

Menggunakan struktur `header`, `navbar`, `main (sidebar + content)`, dan `footer` dengan sistem grid dari Bootstrap.

(Sertakan **screenshot hasil tampilan web** di sini, misalnya `screenshot1.png`.)

### 3. Validasi HTML

Melakukan validasi melalui situs [validator.w3.org](http://validator.w3.org) untuk memastikan kode valid HTML5.

(Sertakan **screenshot hasil validasi** di sini, misalnya `validator.png`.)

---

## Hasil Akhir

Website tampil responsif dengan layout:

* Header dengan judul dan deskripsi.
* Navbar navigasi.
* Sidebar di sisi kiri.
* Konten utama di kanan.
* Footer di bagian bawah.
