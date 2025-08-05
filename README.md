<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistem Antrian Sembako - Selamat Datang</title>
</head>
<body>
    <center>
        <img src="download.jpeg" alt="8888">
        <h1> SISTEM ANTRIAN SEMBAKO</h1>
        <h2>Desa Makmur Sejahtera</h2>
    </center>
    
    <hr>
    
    <!-- SELAMAT DATANG -->
    <table border="1" width="100%" cellpadding="15" bgcolor="lightblue">
        <tr>
            <td align="center">
                <h3> SELAMAT DATANG</h3>
                <p>Sistem Antrian Sembako Digital - Desa Makmur Sejahtera</p>
            </td>
        </tr>
    </table>
    
    <br>
    
    <!-- PENGUMUMAN TERBARU -->
    <table border="2" width="100%" cellpadding="15">
        <tr bgcolor="white">
            <td align="center">
                <h3> PENGUMUMAN PENTING</h3>
            </td>
        </tr>
        <tr bgcolor="white>
            <td>
                <h4> JADWAL DISTRIBUSI SEMBAKO</h4>
                <table border="1" width="100%" cellpadding="10">
                    <tr>
                        <td width="20%"><strong>Hari/Tanggal:</strong></td>
                        <td><strong>Sabtu, 3 Agustus 2025</strong></td>
                    </tr>
                    <tr>
                        <td><strong>Waktu:</strong></td>
                        <td><strong>08.00 - 12.00 WIB</strong></td>
                    </tr>
                    <tr>
                        <td><strong>Tempat:</strong></td>
                        <td><strong>Balai Desa Makmur Sejahtera</strong></td>
                    </tr>
                    <tr bgcolor="white">
                        <td><strong>Kuota:</strong></td>
                        <td><strong>200 Keluarga (Masih tersedia 71 slot)</strong></td>
                    </tr>
                </table>
                <br>
                <p><strong>⚠ PERSYARATAN WAJIB:</strong></p>
                <ul>
                    <li>Membawa KTP asli dan fotocopy</li>
                    <li>Membawa Kartu Keluarga (KK) asli dan fotocopy</li>
                    <li>Membawa bukti pendaftaran (nomor antrian)</li>
                    <li>Menggunakan masker dan menjaga protokol kesehatan</li>
                </ul>
            </td>
        </tr>
    </table>
    
    <br>
    
    <!-- JAM PELAYANAN -->
    <table border="2" width="100%" cellpadding="15">
        <tr bgcolor="gray">
            <td align="center">
                <h3> JAM PELAYANAN</h3>
            </td>
        </tr>
        <tr>
            <td>
                <table border="1" width="100%" cellpadding="8">
                    <tr>
                        <td width="50%">Senin - Jumat</td>
                        <td><strong>08.00 - 16.00 WIB</strong></td>
                    </tr>
                    <tr>
                        <td>Sabtu</td>
                        <td><strong>08.00 - 12.00 WIB</strong></td>
                    </tr>
                    <tr>
                        <td>Minggu & Hari Libur</td>
                        <td><strong>TUTUP</strong></td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>
    
    <br>
    
    <!-- TOMBOL DAFTAR UTAMA -->
    <table border="3" width="100%" cellpadding="25" bgcolor="white">
        <tr>
            <td align="center">
                <a href="index.html">
                    <button style="font-size: 24px; padding: 15px 30px; background-color: rgb(199, 199, 199); border: 3px solid red;">
                         DAFTAR ANTRIAN SEMBAKO SEKARANG
                    </button>
                </a>
                <br><br>
                <p><em>Pastikan data yang Anda masukkan benar dan lengkap</em></p>
                <p><em>Proses pendaftaran hanya membutuhkan waktu 3-5 menit</em></p>
            </td>
        </tr>
    </table>
    
    <hr>
    
    <footer>
        <center>
            <small>
                © 2025 Sistem Antrian Sembako - Desa Makmur Sejahtera<br>
                Dikembangkan untuk melayani masyarakat dengan lebih baik<br>
                <strong>Waktu Server:</strong> <span id="waktu-sekarang"></span>
            </small>
        </center>
    </footer>
    
    <script>
        // Fungsi untuk menampilkan waktu saat ini
        function tampilkanWaktu() {
            const sekarang = new Date();
            const waktu = sekarang.toLocaleString('id-ID');
            document.getElementById('waktu-sekarang').innerHTML = waktu;
        }
        
        // Update waktu setiap detik
        setInterval(tampilkanWaktu, 1000);
        
        // Tampilkan waktu pertama kali
        tampilkanWaktu();
    </script>
    
</body>
</html>
