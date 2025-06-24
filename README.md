<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bandwidth Manager Pro</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Bandwidth Manager Pro</h1>
            <p>Dasbor untuk memonitor dan mengoptimalkan jaringan Anda</p>
        </header>
        <main>
            <section id="dashboard">
                <div class="card speed-test">
                    <h2>Tes Kecepatan Real-Time</h2>
                    <div class="speed-indicators">
                        <div class="indicator download">
                            <div class="value" id="download-speed">--</div>
                            <div class="unit">Mbps</div>
                            <div class="label">Download</div>
                        </div>
                        <div class="indicator upload">
                            <div class="value" id="upload-speed">--</div>
                            <div class="unit">Mbps</div>
                            <div class="label">Upload</div>
                        </div>
                        <div class="indicator ping">
                            <div class="value" id="ping-value">--</div>
                            <div class="unit">ms</div>
                            <div class="label">Ping</div>
                        </div>
                    </div>
                    <button id="start-test">Mulai Tes Kecepatan</button>
                </div>

                <div class="card connected-devices">
                    <h2>Perangkat Terhubung</h2>
                    <ul id="device-list">
                        <li>
                            <span class="device-icon">📱</span> 
                            <span class="device-name">Smartphone Anda</span>
                            <span class="bandwidth-usage high">Tinggi</span>
                        </li>
                        <li>
                            <span class="device-icon">💻</span> 
                            <span class="device-name">Laptop Kerja</span>
                            <span class="bandwidth-usage medium">Sedang</span>
                        </li>
                        <li>
                            <span class="device-icon">📺</span> 
                            <span class="device-name">Smart TV</span>
                            <span class="bandwidth-usage low">Rendah</span>
                        </li>
                    </ul>
                </div>

                <div class="card recommendations">
                    <h2>Rekomendasi Cerdas</h2>
                    <ul id="recommendation-list">
                        <li>Jalankan tes kecepatan untuk mendapatkan rekomendasi awal.</li>
                    </ul>
                </div>
            </section>
        </main>
        <footer>
            <p>&copy; 2025 Bandwidth Manager Pro</p>
        </footer>
    </div>
    <script src="script.js"></script>
</body>
</html>
