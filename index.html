<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perpustakaan SD Taman Ceria</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;600;700&display=swap" rel="stylesheet">

    <style>
        /* --- TEMA PERPUSTAKAAN CERIA (CSS ASLI LENGKAP) --- */
        body {
            margin: 0;
            font-family: 'Quicksand', sans-serif;
            background-color: #f0f8ff;
            background-image: radial-gradient(#d1e9ff 1px, transparent 1px);
            background-size: 20px 20px;
            color: #2c3e50;
            font-size: 15px;
        }

        /* Navbar Custom */
        .navbar {
            background-color: #0d47a1 !important;
            padding: 15px 0;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .navbar-brand { font-weight: 700; color: white !important; font-size: 1.2rem; letter-spacing: 1px; }
        .navbar-brand img { width: 40px; margin-right: 12px; filter: drop-shadow(2px 2px 2px rgba(0,0,0,0.2)); }
        
        .nav-link { 
            color: #bbdefb !important; font-weight: 600; margin-left: 10px;
            padding: 8px 12px !important; border-radius: 12px; transition: 0.3s; cursor: pointer;
        }
        .nav-link:hover { color: white !important; background: rgba(255, 255, 255, 0.1); }
        .nav-link.nav-active { background: #ffc107 !important; color: #0d47a1 !important; box-shadow: 0 4px 8px rgba(0,0,0,0.2); }

        /* Section Layout */
        .section { display: none; padding: 30px 15px; max-width: 1100px; margin: auto; animation: fadeIn 0.5s ease; }
        .active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

        /* Komponen Utama */
        .hero {
            background: linear-gradient(135deg, #1e88e5, #1565c0);
            color: white; padding: 45px 25px; border-radius: 30px;
            box-shadow: 0 10px 20px rgba(21, 101, 192, 0.3);
            margin-bottom: 30px; text-align: center;
        }

        .card-ceria {
            background: white; padding: 25px; border-radius: 24px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.05); border: 1px solid #e1f5fe;
            margin-bottom: 20px;
        }

        /* Koleksi Grid */
        .koleksi-grid {
            display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
            gap: 15px; margin-top: 25px;
        }
        .buku {
            background: white; border-radius: 18px; overflow: hidden;
            transition: 0.3s; cursor: pointer; border: 1px solid #eee;
            display: flex; flex-direction: column; height: 100%;
        }
        .buku:hover { transform: translateY(-8px); box-shadow: 0 12px 20px rgba(0,0,0,0.1); }
        .buku img { width: 100%; height: 160px; object-fit: cover; }
        .buku p { font-size: 0.85rem; padding: 10px; color: #0d47a1; margin: 0; font-weight: 600; text-align: center; }

        /* Video Wrapper (Biar gak kepotong di HP) */
        .video-container {
            position: relative; padding-bottom: 56.25%; height: 0; 
            border-radius: 20px; overflow: hidden; border: 4px solid white;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1); margin-bottom: 20px;
        }
        .video-container iframe { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }

        /* Login/Auth */
        #auth-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: #0d47a1 url('https://www.transparenttextures.com/patterns/cubes.png');
            display: flex; justify-content: center; align-items: center; z-index: 10000;
        }
        .auth-card { background: white; padding: 40px; border-radius: 30px; width: 100%; max-width: 350px; text-align: center; box-shadow: 0 20px 40px rgba(0,0,0,0.3); }
        input { padding: 12px; margin: 8px 0; border-radius: 12px; border: 2px solid #e3f2fd; width: 100%; font-family: inherit; }
        button { padding: 12px 25px; border-radius: 15px; border: none; background: #ffc107; color: #0d47a1; font-weight: 700; cursor: pointer; transition: 0.3s; box-shadow: 0 4px 0 #e6a800; }
        button:active { transform: translateY(3px); box-shadow: none; }

        /* Admin & Map */
        .admin-box { background: #f8fbff; padding: 15px; border-radius: 15px; border-left: 6px solid #0d47a1; margin-bottom: 10px; }
        .map-item { background: white; padding: 20px; border-radius: 20px; box-shadow: 0 5px 15px rgba(0,0,0,0.05); transition: 0.3s; border: 1px solid #e1f5fe; cursor: pointer; text-align: center; height: 100%; }
        .map-item:hover { background: #e3f2fd; transform: scale(1.02); }

        /* Event */
        .event-card-new { background: white; border-radius: 20px; padding: 20px; box-shadow: 0 6px 15px rgba(0,0,0,0.05); text-align: left; border-top: 6px solid #ffc107; height: 100%; }
        .event-time { background: #fff9c4; color: #f57f17; padding: 5px 12px; border-radius: 10px; font-size: 0.8rem; font-weight: bold; margin-bottom: 10px; display: inline-block; }
    </style>
</head>
<body>

<div id="auth-overlay">
    <div id="login-form" class="auth-card">
        <h2 style="color:#0d47a1;">🔑 Halo Teman!</h2>
        <p style="font-size: 0.9rem; color: #666;">Silakan masuk dulu ya</p>
        <input type="text" id="userIn" placeholder="Username">
        <input type="password" id="passIn" placeholder="Password">
        <button onclick="aksiLogin()" style="width: 100%; margin-top:10px;">Masuk Sekarang</button>
        <p style="font-size: 0.8rem; margin-top: 15px;">Baru di sini? <a href="#" onclick="pindahKeDaftar()" style="color:#1e88e5; font-weight:bold;">Daftar Akun</a></p>
    </div>
    <div id="register-form" class="auth-card" style="display:none;">
        <h2 style="color:#2e7d32;">📝 Daftar Baru</h2>
        <input type="text" id="userReg" placeholder="Username Baru">
        <input type="password" id="passReg" placeholder="Password Baru">
        <button onclick="aksiDaftar()" style="width: 100%; margin-top:10px; background:#4caf50; color:white; box-shadow: 0 4px 0 #2e7d32;">Buat Akun</button>
        <p style="font-size: 0.8rem; margin-top: 15px;">Sudah ada akun? <a href="#" onclick="pindahKeLogin()" style="color:#2e7d32; font-weight:bold;">Login Saja</a></p>
    </div>
</div>

<div id="main-app" style="display:none;">
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container">
            <a class="navbar-brand d-flex align-items-center" href="#">
                <img src="logo.png" alt="Logo">
                SD TAMAN CERIA
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto text-center py-3 py-lg-0">
                    <li class="nav-item"><a class="nav-link" onclick="showPage('home')" id="nav-home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" onclick="showPage('koleksi')" id="nav-koleksi">Koleksi</a></li>
                    <li class="nav-item"><a class="nav-link" onclick="showPage('layanan')" id="nav-layanan">Layanan</a></li>
                    <li class="nav-item"><a class="nav-link" onclick="showPage('profil')" id="nav-profil">Profil</a></li>
                    <li class="nav-item"><a class="nav-link" onclick="showPage('map')" id="nav-map">Map</a></li>
                    <li class="nav-item"><a class="nav-link" onclick="showPage('event')" id="nav-event">Event</a></li>
                    <li class="nav-item"><a class="nav-link" onclick="showPage('admin')" id="nav-admin">Admin</a></li>
                    <li class="nav-item"><a class="nav-link text-danger fw-bold ms-lg-3" onclick="logout()">Keluar</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mt-4">
        <div id="home" class="section active">
            <div class="hero">
                <h1>🎉 Selamat Datang, <span id="displayUser"></span>!</h1>
                <p>Mari jelajahi dunia lewat buku di Perpustakaan SD Taman Ceria 💙</p>
            </div>
            
            <div class="row g-4 mb-5">
                <div class="col-lg-6">
                    <div class="card-ceria text-center h-100">
                        <h2>🧮 Hitung Poin Membaca</h2>
                        <p style="color: #666;">Wah, sudah baca berapa buku hari ini?</p>
                        <div class="bg-light p-3 rounded-4 my-3 border border-primary border-dashed d-inline-block w-100">
                            <input type="number" id="jumlahBuku" placeholder="0" style="width: 80px; text-align: center; font-size: 1.2rem; font-weight: bold;">
                            <span id="hasilPoin" style="font-weight: 700; color: #0d47a1; font-size: 2rem; margin-left: 15px;">0</span>
                            <span style="font-weight: 600;"> Poin</span>
                        </div>
                        <button onclick="hitungPoin()" class="w-100 mt-3">Hitung Poin Saya</button>
                        <p id="pesanMotivasi" style="margin-top: 15px; font-weight: 600; color: #1e88e5; height: 20px;"></p>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="card-ceria h-100" style="background: #fffde7; border-color: #fff59d;">
                        <h2 style="color: #f57f17;">📚 Buku Saku Pribadi</h2>
                        <p style="color: #8d6e63; font-size: 0.9rem;">Catat buku yang ingin atau sudah kamu baca!</p>
                        <input type="text" id="bookTitle" placeholder="Judul Buku..." class="mb-2">
                        <input type="text" id="bookAuthor" placeholder="Penulis..." class="mb-2">
                        <button onclick="tambahBukuSaku()" style="background:#f57f17; color:white; box-shadow: 0 4px 0 #bc6412; width: 100%;">Simpan ke Saku</button>
                        <div id="listBukuSaku" class="mt-3 overflow-auto" style="max-height: 200px;"></div>
                    </div>
                </div>
            </div>

            <h2 class="text-primary text-center mb-4">🎥 Video Seru Untukmu</h2>
            <div class="row g-3">
                <div class="col-md-4"><div class="video-container"><iframe src="https://www.youtube.com/embed/lt-hAsZ4bBE" allowfullscreen></iframe></div></div>
                <div class="col-md-4"><div class="video-container"><iframe src="https://www.youtube.com/embed/UA-eSMgV8bU" allowfullscreen></iframe></div></div>
                <div class="col-md-4"><div class="video-container"><iframe src="https://www.youtube.com/embed/PnkBIKrRVhI" allowfullscreen></iframe></div></div>
            </div>
        </div>

        <div id="koleksi" class="section text-center">
            <h2 style="color:#0d47a1;">📚 Cari Buku Favoritmu</h2>
            <input type="text" id="searchInput" placeholder="🔍 Ketik judul buku..." onkeyup="searchBuku()" style="width: 90%; max-width: 450px; border-radius: 20px; border: 2px solid #0d47a1; margin-bottom: 30px;">
            <div class="koleksi-grid">
                <div class="buku" onclick="showDetail('Petualangan Si Kancil','Cerita dongeng tentang kecerdikan si kancil.')"><img src="https://images.unsplash.com/photo-1512820790803-83ca734da794"><p>Si Kancil</p></div>
                <div class="buku" onclick="showDetail('Belajar Membaca Cepat','Panduan membaca untuk anak SD.')"><img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f"><p>Membaca Cepat</p></div>
                <div class="buku" onclick="showDetail('Matematika Itu Mudah','Belajar berhitung dengan cara menyenangkan.')"><img src="https://images.unsplash.com/photo-1509228627152-72ae9ae6848d"><p>Matematika</p></div>
                <div class="buku" onclick="showDetail('Dongeng Sebelum Tidur','Kumpulan cerita sebelum tidur.')"><img src="https://images.unsplash.com/photo-1519681393784-d120267933ba"><p>Dongeng</p></div>
                <div class="buku" onclick="showDetail('Aku Anak Pintar','Cerita motivasi anak.')"><img src="https://images.unsplash.com/photo-1476275466078-4007374efbbe"><p>Anak Pintar</p></div>
                <div class="buku" onclick="showDetail('Ensiklopedia Mini','Pengetahuan umum untuk anak.')"><img src="https://images.unsplash.com/photo-1495446815901-a7297e633e8d"><p>Ensiklopedia</p></div>
                <div class="buku" onclick="showDetail('Komik Lucu Sekolah','Cerita lucu kehidupan sekolah.')"><img src="https://images.unsplash.com/photo-1516979187457-637abb4f9353"><p>Komik Sekolah</p></div>
                <div class="buku" onclick="showDetail('Belajar Sains Seru','Eksperimen sains sederhana.')"><img src="https://images.unsplash.com/photo-1581090700227-4c4b1a8a0d2d"><p>Sains Seru</p></div>
            </div>
        </div>

        <div id="layanan" class="section text-center">
            <h2 style="color:#0d47a1; margin-bottom: 25px;">✨ Layanan Kami ✨</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="map-item" style="cursor: default;">
                        <h3>📚 Peminjaman</h3>
                        <p>Boleh pinjam sampai 3 buku ya teman-teman.</p>
                        <button onclick="alert('Silakan hubungi petugas 😊')" class="w-100">Pinjam Buku</button>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="map-item" style="cursor: default;">
                        <h3>🔄 Pengembalian</h3>
                        <p>Jangan lupa kembalikan buku tepat waktu ya!</p>
                        <button onclick="alert('Terima kasih sudah menjaga buku ⏰')" class="w-100">Kembalikan</button>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="map-item" style="cursor: default; text-align: left;">
                        <h3 style="text-align: center;">🕒 Jadwal Buka</h3>
                        <table style="width: 100%; border-collapse: collapse; margin-top: 10px; font-size: 0.85rem; color: #2c3e50;">
                            <tr><td style="padding: 4px 0;">Senin - Jumat</td><td>: 08.00 - 15.00</td></tr>
                            <tr><td style="padding: 4px 0;">Sabtu</td><td>: 08.00 - 12.00</td></tr>
                            <tr><td style="padding: 4px 0; font-weight: bold; color: #ff5252;">Minggu</td><td style="font-weight: bold; color: #ff5252;">: Tutup</td></tr>
                        </table>
                    </div>
                </div>
            </div>
        </div>

        <div id="profil" class="section text-start">
            <h2 style="color:#0d47a1; text-align: center; margin-bottom: 30px;">📖 Profil Perpustakaan</h2>
            <div class="card-ceria">
                <h3>📖 Tentang Perpustakaan</h3>
                <p style="text-align: justify; line-height: 1.6;">Perpustakaan SD Taman Ceria merupakan pusat sumber belajar yang mendukung kegiatan pembelajaran bagi seluruh warga sekolah. Perpustakaan ini menyediakan koleksi bahan pustaka yang beragam sesuai dengan kebutuhan peserta didik. Keberadaannya bertujuan untuk menumbuhkan budaya literasi serta meningkatkan minat baca siswa. Dengan suasana yang nyaman dan kondusif, perpustakaan mendukung proses pembelajaran secara optimal. Perpustakaan juga berkomitmen untuk meningkatkan kualitas layanan melalui pemanfaatan teknologi informasi.</p>
            </div>
            <div class="card-ceria">
                <h3>🎯 Visi Kami</h3>
                <p style="text-align: justify; line-height: 1.6;">Menjadi perpustakaan sekolah yang unggul sebagai pusat sumber belajar yang edukatif dan inovatif dalam mendukung kegiatan pendidikan, meningkatkan budaya literasi, serta mengembangkan ilmu pengetahuan siswa sejak dini dan mendukung proses pembelajaran secara optimal, serta membentuk generasi yang cerdas, kreatif, serta berkarakter melalui layanan informasi yang berkualitas.</p>
            </div>
            <div class="card-ceria">
                <h3>🚀 Misi Kami</h3>
                <ul style="line-height: 1.8; padding-left: 20px;">
                    <li>Menyediakan koleksi bahan pustaka yang beragam, berkualitas, serta sesuai dengan kebutuhan dan tingkat perkembangan peserta didik.</li>
                    <li>Mengelola perpustakaan secara profesional dengan pelayanan yang ramah, tertib, serta menciptakan suasana yang nyaman, aman, dan menyenangkan sebagai ruang belajar.</li>
                    <li>Mendorong peningkatan minat baca dan budaya literasi siswa melalui program dan kegiatan yang edukatif, inovatif, serta mendukung proses pembelajaran di sekolah.</li>
                    <li>Menyediakan sumber informasi yang relevan, akurat, dan mudah diakses, serta memanfaatkan teknologi informasi untuk meningkatkan kualitas layanan dan menanamkan nilai-nilai karakter positif kepada siswa.</li>
                </ul>
            </div>
        </div>

        <div id="map" class="section text-center">
            <h2 style="color:#0d47a1; margin-bottom: 25px;">🗺️ Mau ke Mana Hari Ini?</h2>
            <div class="row g-3">
                <div class="col-6 col-md-4"><div class="map-item" onclick="showPage('home')"><h3>🏠 Home</h3><p class="small d-none d-md-block">Halaman utama & hitung poin.</p></div></div>
                <div class="col-6 col-md-4"><div class="map-item" onclick="showPage('koleksi')"><h3>📚 Koleksi</h3><p class="small d-none d-md-block">Daftar buku-buku seru.</p></div></div>
                <div class="col-6 col-md-4"><div class="map-item" onclick="showPage('layanan')"><h3>✨ Layanan</h3><p class="small d-none d-md-block">Info pinjam & jadwal.</p></div></div>
                <div class="col-6 col-md-4"><div class="map-item" onclick="showPage('profil')"><h3>📖 Profil</h3><p class="small d-none d-md-block">Visi & Misi sekolah.</p></div></div>
                <div class="col-6 col-md-4"><div class="map-item" onclick="showPage('event')"><h3>📅 Event</h3><p class="small d-none d-md-block">Acara lomba & festival.</p></div></div>
                <div class="col-6 col-md-4"><div class="map-item" onclick="showPage('admin')"><h3>🔑 Admin</h3><p class="small d-none d-md-block">Info pengelola.</p></div></div>
            </div>
        </div>

        <div id="event" class="section">
            <h2 style="color:#0d47a1; text-align: center; margin-bottom: 30px;">📅 Kegiatan Seru Bulan Ini</h2>
            <div class="row g-4">
                <div class="col-md-4"><div class="event-card-new"><div class="event-time">15 April 2026</div><h3>📖 Festival Dongeng</h3><p>📍 Aula Perpustakaan</p><button class="w-100 mt-2" onclick="alert('Daftar Berhasil!')">Ikuti</button></div></div>
                <div class="col-md-4"><div class="event-card-new"><div class="event-time">22 April 2026</div><h3>🏆 Lomba Resensi</h3><p>📍 Ruang Digital</p><button class="w-100 mt-2" onclick="alert('Daftar Berhasil!')">Daftar</button></div></div>
                <div class="col-md-4"><div class="event-card-new"><div class="event-time">02 Mei 2026</div><h3>🎨 Workshop Pembatas</h3><p>📍 Area Kreatif</p><button class="w-100 mt-2" onclick="alert('Daftar Berhasil!')">Ikuti</button></div></div>
            </div>
        </div>

        <div id="admin" class="section">
            <h2 style="color:#0d47a1; text-align: center; margin-bottom: 30px;">🔑 Dashboard Admin</h2>
            <div class="card-ceria">
                <div class="admin-box">
                    <h3 style="margin-bottom:10px;">Profil Petugas</h3>
                    <p><strong>Nama:</strong> Salsabilla Oktavia Lubis</p>
                    <p><strong>Email:</strong> salsabillaok13@gmail.com</p>
                    <p><strong>Kontak:</strong> 081264089312</p>
                    <a href="https://drive.google.com/drive/folders/1foxSvTkdAC9_uROXseR49T6KYU6bR2IE" target="_blank" class="btn btn-primary rounded-pill mt-2">Buka Dokumen CV</a>
                </div>
            </div>
        </div>
    </div>
</div>

<div id="popup" style="display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.7); justify-content: center; align-items: center; z-index: 20000;">
    <div class="auth-card">
        <h3 id="judulBukuPop" style="color:#0d47a1;"></h3>
        <p id="deskripsiBukuPop" style="color:#666;"></p>
        <button onclick="closePopup()" class="w-100">Tutup</button>
    </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
<script>
function showPage(id) {
    document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
    document.querySelectorAll('.nav-link').forEach(a => a.classList.remove('nav-active'));
    document.getElementById(id).classList.add('active');
    let navEl = document.getElementById('nav-' + id);
    if(navEl) navEl.classList.add('nav-active');

    // Otomatis tutup hamburger di HP saat menu diklik
    const navBar = document.getElementById('navbarNav');
    if(window.getComputedStyle(navBar).display !== 'none' && navBar.classList.contains('show')){
        bootstrap.Collapse.getInstance(navBar).hide();
    }
}

function aksiLogin() {
    let u = document.getElementById('userIn').value; let p = document.getElementById('passIn').value;
    if(u === localStorage.getItem('userPerpus') && p === localStorage.getItem('passPerpus') && u) {
        document.getElementById('auth-overlay').style.display='none'; document.getElementById('main-app').style.display='block';
        document.getElementById('displayUser').innerText = u; showPage('home');
    } else { alert("Maaf, Username atau Password salah!"); }
}

function pindahKeDaftar() { document.getElementById('login-form').style.display='none'; document.getElementById('register-form').style.display='block'; }
function pindahKeLogin() { document.getElementById('register-form').style.display='none'; document.getElementById('login-form').style.display='block'; }
function aksiDaftar() {
    let u = document.getElementById('userReg').value; let p = document.getElementById('passReg').value;
    if(u && p) { localStorage.setItem('userPerpus', u); localStorage.setItem('passPerpus', p); alert("Akun berhasil dibuat!"); pindahKeLogin(); }
}
function logout() { location.reload(); }

let koleksiSaku = JSON.parse(localStorage.getItem('koleksiSaku')) || [];
function tampilkanBukuSaku() {
    let div = document.getElementById("listBukuSaku"); div.innerHTML = "";
    koleksiSaku.forEach((b, i) => {
        div.innerHTML += `<div class="admin-box d-flex justify-content-between align-items-center"><div><strong>${b.judul}</strong><br><small>Penulis: ${b.penulis}</small></div><button onclick="hapusBukuSaku(${i})" style="background:#ff5252; color:white; padding:5px 10px; font-size:0.7rem; box-shadow:0 2px 0 #c62828;">Hapus</button></div>`;
    });
}
function tambahBukuSaku() {
    let j = document.getElementById("bookTitle").value; let p = document.getElementById("bookAuthor").value;
    if(j && p) { koleksiSaku.push({judul:j, penulis:p}); localStorage.setItem('koleksiSaku', JSON.stringify(koleksiSaku)); tampilkanBukuSaku(); document.getElementById("bookTitle").value = ""; document.getElementById("bookAuthor").value = ""; }
}
function hapusBukuSaku(i) { koleksiSaku.splice(i, 1); localStorage.setItem('koleksiSaku', JSON.stringify(koleksiSaku)); tampilkanBukuSaku(); }
tampilkanBukuSaku();

function searchBuku(){
    let input = document.getElementById("searchInput").value.toLowerCase();
    document.querySelectorAll(".buku").forEach(item=>{ item.style.display = item.innerText.toLowerCase().includes(input) ? "" : "none"; });
}
function showDetail(j,d){ document.getElementById("judulBukuPop").innerText=j; document.getElementById("deskripsiBukuPop").innerText=d; document.getElementById("popup").style.display="flex"; }
function closePopup(){ document.getElementById("popup").style.display="none"; }
function hitungPoin() {
    let n = document.getElementById("jumlahBuku").value;
    document.getElementById("hasilPoin").innerText = n * 10;
    document.getElementById("pesanMotivasi").innerText = n > 0 ? "Hebat sekali! Teruslah membaca ya! 🌟" : "Yuk, mulai baca bukumu hari ini!";
}
</script>
</body>
</html>
