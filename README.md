UNNES Study Zone - Platform Persiapan UTS & UAS Online #1 di Indonesia
Selamat datang di repositori UNNES Study Zone! Platform ini dirancang untuk menjadi solusi terdepan bagi mahasiswa dalam mempersiapkan Ujian Tengah Semester (UTS) dan Ujian Akhir Semester (UAS) secara online. Dengan antarmuka yang ramah pengguna, fitur-fitur inovatif, dan konten yang relevan, UNNES Study Zone bertujuan untuk mendukung kesuksesan akademik mahasiswa.

login or registered accounts :
{ email: 'mahasiswa@unnes.ac.id', password: 'Password123!', role: 'student' },

{ email: 'dosen@unnes.ac.id', password: 'DosenPass!23', role: 'teacher' },

{ email: 'admin@unnes.ac.id', password: 'AdminPass!23', role: 'admin' }

mahasiswa@unnes.ac.id
dosen@unnes.ac.id
test@example.com

Fitur Utama
1. Otentikasi Pengguna yang Aman dan Ramah Pengguna
Kami telah mengimplementasikan sistem otentikasi yang kuat dan intuitif untuk memastikan pengalaman pengguna yang lancar dan aman.

Halaman Pendaftaran (register.html):

Desain bersih dan profesional.

Mendukung pendaftaran peran Mahasiswa dan Dosen/Pengajar (peran Admin disiapkan secara internal).

Formulir dinamis yang menyesuaikan bidang input berdasarkan peran yang dipilih (misalnya, NIM, Program Studi untuk Mahasiswa; NIP, Fakultas untuk Dosen).

Validasi frontend yang komprehensif untuk format email, kekuatan kata sandi, dan bidang wajib, dengan pesan kesalahan inline dan toast notification.

Simulasi proses verifikasi email.

Halaman Login (login.html):

Antarmuka login yang intuitif dengan bidang email dan kata sandi.

Fitur "Ingat Saya" untuk kenyamanan pengguna.

Opsi untuk masuk dengan Google dan Facebook (simulasi), serta placeholder untuk UNNES Single Sign-On (SSO) di masa mendatang.

Validasi frontend untuk format email dan bidang wajib.

Simulasi perlindungan brute-force dengan batasan percobaan login.

Pengalihan berbasis peran setelah login berhasil (simulasi ke materi.html untuk Mahasiswa dan akun.html untuk Dosen/Pengajar).

Halaman Lupa Kata Sandi (forgot-password.html):

Alur pemulihan kata sandi yang sederhana melalui tautan reset email.

Validasi format email dan simulasi pemeriksaan email terdaftar.

Simulasi rate limiting untuk mencegah penyalahgunaan.

2. Manajemen Paket & Pembelian
Halaman pemilihan paket yang jelas dan proses pembelian yang transparan.

Halaman Paket (paket.html):

Menampilkan berbagai paket belajar (BASIC, PREMIUM, GROUP, Program Sertifikasi Digital).

Badge "BARU" pada "Program Sertifikasi Digital" untuk menyoroti penawaran terbaru.

Fungsionalitas kode promo (UNNESDISKON20, STUDYZONEHEMAT50) yang terintegrasi di halaman utama ringkasan pembelian, memungkinkan pengguna melihat diskon yang diterapkan sebelum pembayaran.

Ringkasan pembelian yang detail, menampilkan harga asli, diskon (jika ada), dan total pembayaran.

Modal konfirmasi pembayaran yang intuitif untuk pemilihan metode pembayaran (Transfer Bank, QRIS, E-Wallet) dan finalisasi transaksi.

3. Mascot UNNES Study Zone
Platform ini kini memiliki maskot yang ramah dan inovatif: seekor burung elang (abstraksi Garuda) dengan gaya kartun minimalis. Maskot ini melambangkan kebebasan belajar, kreativitas, dan aspirasi tinggi, didesain dengan senyum percaya diri, memakai topi wisuda, dan memegang tablet digital dengan aura ide. Warna maskot konsisten dengan branding UNNES Study Zone (biru dominan dengan aksen putih, abu-abu, dan kuning muda), mencerminkan estetika modern dan profesional.

Tumpukan Teknologi
Proyek ini dibangun menggunakan teknologi frontend standar untuk memastikan kompatibilitas dan kinerja yang optimal:

HTML5: Struktur dasar halaman web.

Tailwind CSS: Framework CSS utilitas-pertama untuk styling yang responsif dan cepat.

JavaScript (Vanilla JS): Untuk fungsionalitas interaktif, validasi formulir, dan simulasi alur pengguna.

Font Awesome: Untuk ikonografi.

AOS (Animate On Scroll): Untuk efek animasi saat menggulir.

Cara Menjalankan Proyek Secara Lokal
Untuk menjalankan proyek ini di lingkungan lokal Anda, ikuti langkah-langkah sederhana berikut:

Kloning Repositori (Jika Ada):

git clone [URL_REPOSITORI_ANDA]
cd unnes-study-zone

(Jika Anda mendapatkan file ini langsung, lewati langkah ini.)

Buka File HTML:
Cukup buka file index.html (atau login.html, register.html, paket.html, forgot-password.html) di browser web pilihan Anda. Tidak ada server web atau konfigurasi rumit yang diperlukan karena ini adalah proyek frontend statis.

Contoh: Klik kanan pada index.html dan pilih "Open with Google Chrome" atau browser lainnya.

Peningkatan di Masa Depan (Rencana)
Beberapa area yang diidentifikasi untuk peningkatan di masa depan:

Integrasi Backend Nyata: Mengganti simulasi frontend dengan API backend yang sebenarnya untuk otentikasi pengguna, manajemen akun, pemrosesan pembayaran, dan penyimpanan data.

Verifikasi Email Sesungguhnya: Mengimplementasikan pengiriman tautan verifikasi email dan OTP yang berfungsi penuh.

Integrasi UNNES SSO: Mengembangkan integrasi dengan sistem Single Sign-On Universitas Negeri Semarang.

Dashboard Pengguna Berbasis Peran: Membuat dasbor khusus dan halaman konten terpersonalisasi untuk Mahasiswa dan Dosen/Pengajar setelah login.

Manajemen Kode Promo: Sistem backend untuk mengelola kode promo, batas penggunaan, dan tanggal kedaluwarsa.

Log Aktivitas & Audit: Merekam aktivitas penting untuk tujuan keamanan dan audit.

Fitur Pembayaran Lanjutan: Integrasi dengan payment gateway sungguhan.

Optimisasi SEO: Peningkatan untuk visibilitas di mesin pencari.

Internasionalisasi (I18n): Dukungan multi-bahasa jika diperlukan.

Kontribusi
Kami menyambut kontribusi! Jika Anda memiliki ide atau perbaikan, silakan:

Fork repositori ini.

Buat cabang fitur baru (git checkout -b feature/nama-fitur-baru).

Lakukan perubahan Anda.

Commit perubahan Anda (git commit -m 'Tambahkan fitur baru').

Push ke cabang Anda (git push origin feature/nama-fitur-baru).

Buka Pull Request baru.
