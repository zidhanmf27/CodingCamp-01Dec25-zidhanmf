# 🌟 Portfolio Website - Assignment Bootcamp RevoU

![Portfolio Banner](https://img.shields.io/badge/RevoU-Bootcamp%20Assignment-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 📋 Deskripsi Proyek

Website portfolio modern dengan tema **dark mode** yang dibuat sebagai tugas assignment **Bootcamp RevoU**. Website ini menampilkan profil pribadi saya sebagai mahasiswa Teknik Informatika dengan fokus pada **Front-End Development**, dilengkapi dengan fitur-fitur interaktif dan desain yang responsif.

### 🎯 Tujuan Assignment
- Membuat website company profile/portfolio dengan HTML, CSS, dan JavaScript
- Mengimplementasikan validasi form yang komprehensif
- Menerapkan konsep responsive design
- Menggunakan localStorage untuk menyimpan data
- Menerapkan best practices dalam web development

---

## ✨ Fitur Utama

### 1. **Halaman Beranda (index.html)**
- ✅ **Hero Section** dengan sapaan dinamis menggunakan nama pengunjung
- ✅ **Animasi Typewriter** untuk menampilkan nama dengan efek mengetik
- ✅ **Modal Input Nama** yang elegan untuk personalisasi pengalaman
- ✅ **Spotlight Effect** yang mengikuti pergerakan mouse
- ✅ **Section Keahlian** dengan 3 card fitur utama:
  - Front-End Development
  - Desain Responsif
  - UI/UX Interest
- ✅ **Form Kontak** dengan validasi lengkap
- ✅ **Glassmorphism Design** untuk efek modern
- ✅ **Animasi Hover** pada semua elemen interaktif

### 2. **Halaman Profil (profile.html)**
- ✅ **Banner Hero** dengan overlay dan pola dekoratif
- ✅ **Section Tentang Saya** dengan:
  - Deskripsi lengkap profil
  - Foto profil
  - Statistik (10+ Campus Projects, Full Stack Learning, 3+ Years Learning)
- ✅ **Section Tujuan & Nilai** dengan 2 card besar:
  - Tujuan karir sebagai Front-End Developer
  - Nilai-nilai dalam pengembangan web
- ✅ **Section Nilai Inti** dengan 4 card:
  - Inovasi
  - Integritas
  - Kolaborasi
  - Keunggulan
- ✅ **Call-to-Action (CTA)** untuk menghubungi

### 3. **Fitur JavaScript (script.js)**

#### 🎨 Efek Visual
- **Spotlight Effect**: Efek lampu sorot yang mengikuti kursor mouse
- **Fade-in Animations**: Animasi muncul saat scroll
- **Hover Effects**: Transformasi dan shadow pada elemen interaktif
- **Smooth Scrolling**: Navigasi halus antar section

#### 👤 Personalisasi Pengguna
- **Modal Input Nama**: Dialog kustom untuk meminta nama pengunjung
- **LocalStorage**: Menyimpan nama pengguna untuk kunjungan berikutnya
- **Typewriter Animation**: Animasi mengetik nama dengan kursor berkedip
- **Skip Option**: Opsi untuk melewati input nama

#### 📝 Validasi Form Kontak
Form kontak memiliki validasi komprehensif untuk:

**Nama:**
- ❌ Tidak boleh kosong
- ❌ Minimal 3 karakter
- ❌ Hanya boleh huruf dan spasi
- ✅ Contoh valid: "John Doe"

**Email:**
- ❌ Tidak boleh kosong
- ❌ Harus format email valid
- ✅ Contoh valid: "user@example.com"

**Nomor Telepon:**
- ❌ Tidak boleh kosong
- ❌ Minimal 10 digit
- ✅ Contoh valid: "081234567890"

**Pesan:**
- ❌ Tidak boleh kosong
- ❌ Minimal 10 karakter
- ✅ Contoh valid: "Halo, saya tertarik dengan..."

#### 🔒 Keamanan
- **XSS Protection**: Sanitasi input untuk mencegah serangan XSS
- **HTML Sanitization**: Semua input dibersihkan sebelum ditampilkan
- **Safe LocalStorage**: Data disimpan dengan aman di browser

#### 📊 Tampilan Hasil Form
Setelah form berhasil dikirim, akan menampilkan:
- ✅ Nama pengirim
- ✅ Email pengirim
- ✅ Nomor telepon
- ✅ Pesan lengkap
- ✅ Timestamp pengiriman (format Indonesia)
- ✅ Tombol "Kirim Pesan Lain" untuk reset form

---

## 🎨 Desain & Teknologi

### Tema Warna
- **Background**: Black (#000000)
- **Text**: White (#FFFFFF)
- **Accent**: White dengan opacity variations
- **Borders**: White dengan opacity 10-40%

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800

### Teknologi yang Digunakan
1. **HTML5** - Struktur semantik
2. **CSS3** - Styling dengan custom properties
3. **Tailwind CSS** - Utility-first CSS framework (via CDN)
4. **JavaScript (Vanilla)** - Interaktivitas dan validasi
5. **LocalStorage API** - Penyimpanan data lokal
6. **Intersection Observer API** - Scroll animations

### Efek Visual Khusus
- ✨ **Glassmorphism**: Background blur dengan transparency
- ✨ **Spotlight Effect**: Radial gradient mengikuti mouse
- ✨ **Hover Lift**: Transform translateY dengan shadow
- ✨ **Typewriter Cursor**: Animasi kursor berkedip
- ✨ **Fade-in Animations**: Keyframe animations
- ✨ **Card Borders**: Animated border pada hover

---

## 📁 Struktur Proyek

```
CodingCamp-01Dec25-zidhanmf/
│
├── index.html              # Halaman beranda
├── profile.html            # Halaman profil
├── README.md              # Dokumentasi proyek (file ini)
│
├── assets/                # Folder aset
│   ├── cat.gif           # Animasi GIF untuk hero section
│   └── mask.jpg          # Logo dan foto profil
│
└── js/                   # Folder JavaScript
    └── script.js         # File JavaScript utama
```

---

## 🚀 Cara Menjalankan

### Metode 1: Langsung di Browser
1. Clone atau download repository ini
2. Buka file `index.html` di browser favorit Anda
3. Navigasi ke halaman profil melalui menu atau tombol

### Metode 2: Menggunakan Live Server (Recommended)
1. Install extension **Live Server** di VS Code
2. Klik kanan pada `index.html`
3. Pilih "Open with Live Server"
4. Website akan terbuka di `http://localhost:5500`

### Metode 3: Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Buka browser dan akses
# http://localhost:8000
```

---

## 💡 Fitur JavaScript Detail

### 1. Mobile Menu Toggle
```javascript
// Toggle menu mobile saat tombol diklik
mobileMenuBtn.addEventListener('click', function() {
    mobileMenu.classList.toggle('hidden');
});
```

### 2. Dynamic Name Greeting
```javascript
// Cek localStorage untuk nama pengguna
let userName = localStorage.getItem('userName');
if (!userName) {
    showNameModal(); // Tampilkan modal input
} else {
    displayUserName(userName); // Tampilkan nama tersimpan
}
```

### 3. Form Validation
```javascript
// Validasi email dengan regex
function isValidEmail(email) {
    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    return emailRegex.test(email);
}

// Validasi telepon (minimal 10 digit)
function isValidPhone(phone) {
    const digitsOnly = phone.replace(/\D/g, '');
    return digitsOnly.length >= 10;
}
```

### 4. XSS Protection
```javascript
// Sanitasi HTML untuk mencegah XSS
function sanitizeHTML(str) {
    const temp = document.createElement('div');
    temp.textContent = str;
    return temp.innerHTML;
}
```

### 5. LocalStorage Management
```javascript
// Simpan submission ke localStorage
let submissions = JSON.parse(localStorage.getItem('formSubmissions') || '[]');
submissions.push(submission);
localStorage.setItem('formSubmissions', JSON.stringify(submissions));
```

---

## 📱 Responsive Design

Website ini **100% responsive** dan telah dioptimasi untuk berbagai ukuran layar:

### Breakpoints
- 📱 **Mobile**: < 768px
- 💻 **Tablet**: 768px - 1024px
- 🖥️ **Desktop**: > 1024px

### Fitur Responsive
- ✅ Mobile-first approach
- ✅ Hamburger menu untuk mobile
- ✅ Grid layout yang adaptif
- ✅ Font size yang scalable
- ✅ Touch-friendly button sizes
- ✅ Optimized images

---

## 🎓 Konsep yang Dipelajari

Melalui assignment ini, saya telah mempelajari dan mengimplementasikan:

1. ✅ **HTML Semantik** - Penggunaan tag yang tepat
2. ✅ **CSS Modern** - Flexbox, Grid, Custom Properties
3. ✅ **JavaScript ES6+** - Arrow functions, template literals, destructuring
4. ✅ **DOM Manipulation** - Query selectors, event listeners
5. ✅ **Form Validation** - Client-side validation dengan regex
6. ✅ **LocalStorage API** - Persistent data storage
7. ✅ **Responsive Design** - Mobile-first approach
8. ✅ **UX/UI Principles** - User feedback, loading states, animations
9. ✅ **Security** - XSS prevention, input sanitization
10. ✅ **Code Organization** - Modular functions, clear comments

---

## 🔧 Customization

### Mengubah Warna Tema
Edit bagian CSS di `<style>` tag pada file HTML:
```css
/* Ubah warna background */
body {
    background: #000000; /* Ganti dengan warna pilihan */
}

/* Ubah warna teks */
.gradient-text {
    color: #ffffff; /* Ganti dengan warna pilihan */
}
```

### Mengubah Font
Ganti link Google Fonts di `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=NamaFont:wght@weights&display=swap" rel="stylesheet">
```

### Menambah Section Baru
Ikuti struktur section yang ada:
```html
<section class="py-20 px-4 sm:px-6 lg:px-8 bg-black">
    <div class="max-w-7xl mx-auto">
        <!-- Konten section -->
    </div>
</section>
```

---

## 🐛 Known Issues & Future Improvements

### Current Limitations
- Form tidak mengirim data ke server (hanya validasi client-side)
- LocalStorage terbatas pada browser yang sama
- Tidak ada backend integration

### Planned Improvements
- [ ] Integrasi dengan backend API
- [ ] Database untuk menyimpan submissions
- [ ] Email notification saat form dikirim
- [ ] Dark/Light mode toggle
- [ ] Multi-language support (ID/EN)
- [ ] Blog section
- [ ] Portfolio gallery
- [ ] Testimonials section
- [ ] Download CV button
- [ ] Social media integration

---

## 📞 Kontak

**Zidhan Maula Fatih**
- 🌐 GitHub: [@zidhanmf27](https://github.com/zidhanmf27)
- 💼 LinkedIn: [zidhanmf](https://linkedin.com/in/zidhanmf)
- 📧 Email: [Contact via website form]

---

## 📄 Lisensi

Project ini dibuat untuk keperluan **assignment Bootcamp RevoU** dan dapat digunakan sebagai referensi pembelajaran.

---

## 🙏 Acknowledgments

- **RevoU** - Platform bootcamp yang memberikan assignment ini
- **Tailwind CSS** - Framework CSS yang memudahkan styling
- **Google Fonts** - Poppins font family
- **Heroicons** - SVG icons yang digunakan

---

## 📚 Referensi & Resources

- [MDN Web Docs](https://developer.mozilla.org/) - JavaScript & Web APIs
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [HTML5 Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [JavaScript Form Validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- [LocalStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

---

## 📝 Changelog

### Version 1.0.0 (December 2025)
- ✅ Initial release
- ✅ Halaman beranda dengan hero section
- ✅ Halaman profil lengkap
- ✅ Form kontak dengan validasi
- ✅ Modal input nama
- ✅ Typewriter animation
- ✅ Spotlight effect
- ✅ Responsive design
- ✅ LocalStorage integration
- ✅ XSS protection

---

<div align="center">

### ⭐ Jika project ini membantu, jangan lupa beri star!

**Made with ❤️ by Zidhan Maula Fatih**

*Assignment Bootcamp RevoU - December 2025*

</div>
