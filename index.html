<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infaq Harian dan Tabungan Qurban Kelompok Baitul Ihsan</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-white text-slate-800 font-sans antialiased pb-24">

    <!-- TAMPILAN DEPAN: JUDUL UTAMA -->
    <header class="bg-emerald-700 text-white shadow-sm sticky top-0 z-50">
        <div class="max-w-5xl mx-auto px-4 py-4 text-center">
            <h1 class="text-base sm:text-xl font-bold tracking-wide">
                Infaq Harian dan Tabungan Qurban Kelompok Baitul Ihsan
            </h1>
        </div>
    </header>

    <!-- NAVIGASI ROOM TERPISAH -->
    <nav class="max-w-5xl mx-auto px-4 mt-4">
        <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 bg-slate-100 p-1.5 rounded-xl border border-slate-200">
            <button onclick="switchTab('input')" id="tab-input" class="tab-btn py-2.5 px-3 text-xs sm:text-sm font-bold rounded-lg bg-emerald-600 text-white shadow-sm transition">
                <i class="fa-solid fa-pen-to-square mr-1"></i> Input Data
            </button>
            <button onclick="switchTab('infaq')" id="tab-infaq" class="tab-btn py-2.5 px-3 text-xs sm:text-sm font-bold rounded-lg text-slate-600 hover:bg-white transition">
                <i class="fa-solid fa-hand-holding-heart mr-1"></i> Rekap Infaq
            </button>
            <button onclick="switchTab('qurban')" id="tab-qurban" class="tab-btn py-2.5 px-3 text-xs sm:text-sm font-bold rounded-lg text-slate-600 hover:bg-white transition">
                <i class="fa-solid fa-cow mr-1"></i> Rekap Qurban
            </button>
            <button onclick="switchTab('all')" id="tab-all" class="tab-btn py-2.5 px-3 text-xs sm:text-sm font-bold rounded-lg text-slate-600 hover:bg-white transition">
                <i class="fa-solid fa-layer-group mr-1"></i> Keseluruhan
            </button>
        </div>
    </nav>

    <!-- FILTER TANGGAL ACUAN REKAP -->
    <div class="max-w-5xl mx-auto px-4 mt-4">
        <div class="bg-slate-50 border border-slate-200 rounded-xl p-3 flex flex-col sm:flex-row items-center justify-between gap-2">
            <div class="text-xs sm:text-sm font-semibold text-slate-700">
                <i class="fa-solid fa-calendar-day text-emerald-600 mr-1.5"></i> Tanggal Acuan Rekap & Ceklist:
            </div>
            <div class="flex items-center gap-2 w-full sm:w-auto">
                <input type="date" id="filter-tanggal" onchange="renderSemua()" class="w-full sm:w-auto bg-white border border-slate-300 rounded-lg px-3 py-1.5 text-xs sm:text-sm font-semibold text-slate-700 focus:outline-none focus:ring-2 focus:ring-emerald-500">
                <button onclick="setFilterHariIni()" class="bg-emerald-100 text-emerald-800 px-3 py-1.5 rounded-lg text-xs font-bold hover:bg-emerald-200 whitespace-nowrap">
                    Hari Ini
                </button>
            </div>
        </div>
    </div>

    <main class="max-w-5xl mx-auto px-4 mt-4 space-y-6">

        <!-- ROOM 1: INPUT DATA -->
        <section id="room-input" class="tab-content space-y-4">
            <div class="bg-white p-5 rounded-2xl border border-slate-200 shadow-sm">
                <h2 class="text-sm sm:text-base font-bold text-slate-800 mb-4 pb-2 border-b border-slate-100">
                    Input Transaksi Warga (Integrasi Otomatis)
                </h2>
                <form id="form-transaksi" onsubmit="simpanTransaksi(event)" class="space-y-4">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-600 mb-1">Pilih Nama KK</label>
                            <select id="input-kk" required class="w-full bg-slate-50 border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none"></select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-600 mb-1">Jenis Setoran</label>
                            <select id="input-jenis" required class="w-full bg-slate-50 border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                                <option value="Infaq Harian">Infaq Harian</option>
                                <option value="Tabungan Qurban">Tabungan Qurban</option>
                            </select>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-600 mb-1">Nominal (Rp)</label>
                            <input type="number" id="input-nominal" min="500" step="500" required placeholder="Contoh: 5000" class="w-full bg-slate-50 border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-600 mb-1">Tanggal Transaksi (Bisa Custom)</label>
                            <input type="date" id="input-tanggal" required class="w-full bg-slate-50 border border-slate-300 rounded-xl p-2.5 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-600 mb-1">Waktu Jam (Real-Time)</label>
                            <input type="text" id="input-waktu" readonly class="w-full bg-slate-100 border border-slate-300 rounded-xl p-2.5 text-sm font-mono text-slate-600">
                        </div>
                    </div>

                    <button type="submit" id="btn-simpan" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-3 rounded-xl text-sm shadow-sm transition">
                        <i class="fa-solid fa-floppy-disk mr-1.5"></i> Simpan Transaksi
                    </button>
                </form>
            </div>

            <div class="bg-slate-50 p-4 rounded-xl border border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs">
                <span class="text-slate-600 font-medium">Uji coba data atau simulasi rekap:</span>
                <div class="flex gap-2">
                    <button type="button" onclick="muatDataContoh()" class="bg-blue-600 text-white px-3 py-1.5 rounded-lg font-bold hover:bg-blue-700">
                        Isi Contoh Data
                    </button>
                    <button type="button" onclick="hapusSemuaData()" class="bg-red-100 text-red-700 px-3 py-1.5 rounded-lg font-bold hover:bg-red-200">
                        Reset Kosong
                    </button>
                </div>
            </div>
        </section>

        <!-- ROOM 2: REKAP INFAQ HARIAN & TRACKER 30 HARI -->
        <section id="room-infaq" class="tab-content hidden space-y-5">
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3">
                <div class="bg-emerald-50 border border-emerald-200 p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-emerald-800 uppercase">Infaq Hari Ini (Semua KK)</div>
                    <div id="infaq-all-hari" class="text-base sm:text-lg font-extrabold text-emerald-700 mt-1">Rp 0</div>
                </div>
                <div class="bg-emerald-50 border border-emerald-200 p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-emerald-800 uppercase">Infaq Minggu Ini (Semua KK)</div>
                    <div id="infaq-all-minggu" class="text-base sm:text-lg font-extrabold text-emerald-700 mt-1">Rp 0</div>
                </div>
                <div class="bg-emerald-50 border border-emerald-200 p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-emerald-800 uppercase">Infaq Bulan Ini (Semua KK)</div>
                    <div id="infaq-all-bulan" class="text-base sm:text-lg font-extrabold text-emerald-700 mt-1">Rp 0</div>
                </div>
                <div class="bg-slate-800 text-white p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-slate-300 uppercase">Total Seluruh Infaq</div>
                    <div id="infaq-all-total" class="text-base sm:text-lg font-extrabold text-emerald-400 mt-1">Rp 0</div>
                </div>
            </div>

            <div class="bg-white p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm">
                <div class="flex flex-col sm:flex-row justify-between sm:items-center mb-3 pb-2 border-b border-slate-100 gap-1">
                    <h2 class="text-sm sm:text-base font-bold text-slate-800">
                        Tracker Ceklist Infaq Harian, Persentase 30 Hari & Rekap Per KK
                    </h2>
                    <span id="info-ceklist-infaq" class="text-xs font-bold text-emerald-700 bg-emerald-50 px-2.5 py-1 rounded-full"></span>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-slate-100 text-slate-700 border-b border-slate-200">
                                <th class="p-2.5">No</th>
                                <th class="p-2.5">Nama KK</th>
                                <th class="p-2.5 text-center">Ceklist Tgl Ini</th>
                                <th class="p-2.5 text-center">Tracker 30 Hari (%)</th>
                                <th class="p-2.5 text-right">Per Hari</th>
                                <th class="p-2.5 text-right">Per Minggu</th>
                                <th class="p-2.5 text-right">Per Bulan</th>
                                <th class="p-2.5 text-right">Total Infaq</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-infaq-kk" class="divide-y divide-slate-100"></tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- ROOM 3: REKAP TABUNGAN QURBAN -->
        <section id="room-qurban" class="tab-content hidden space-y-5">
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3">
                <div class="bg-blue-50 border border-blue-200 p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-blue-800 uppercase">Qurban Hari Ini (Semua KK)</div>
                    <div id="qurban-all-hari" class="text-base sm:text-lg font-extrabold text-blue-700 mt-1">Rp 0</div>
                </div>
                <div class="bg-blue-50 border border-blue-200 p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-blue-800 uppercase">Qurban Minggu Ini (Semua KK)</div>
                    <div id="qurban-all-minggu" class="text-base sm:text-lg font-extrabold text-blue-700 mt-1">Rp 0</div>
                </div>
                <div class="bg-blue-50 border border-blue-200 p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-blue-800 uppercase">Qurban Bulan Ini (Semua KK)</div>
                    <div id="qurban-all-bulan" class="text-base sm:text-lg font-extrabold text-blue-700 mt-1">Rp 0</div>
                </div>
                <div class="bg-slate-800 text-white p-3.5 rounded-xl">
                    <div class="text-[11px] font-bold text-slate-300 uppercase">Total Seluruh Qurban</div>
                    <div id="qurban-all-total" class="text-base sm:text-lg font-extrabold text-blue-400 mt-1">Rp 0</div>
                </div>
            </div>

            <div class="bg-white p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm">
                <h2 class="text-sm sm:text-base font-bold text-slate-800 mb-3 pb-2 border-b border-slate-100">
                    Rekapitulasi Tabungan Qurban Per KK (Harian, Mingguan, Bulanan)
                </h2>
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-slate-100 text-slate-700 border-b border-slate-200">
                                <th class="p-2.5">No</th>
                                <th class="p-2.5">Nama KK</th>
                                <th class="p-2.5 text-right">Per Hari</th>
                                <th class="p-2.5 text-right">Per Minggu</th>
                                <th class="p-2.5 text-right">Per Bulan</th>
                                <th class="p-2.5 text-right">Total Tabungan Qurban</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-qurban-kk" class="divide-y divide-slate-100"></tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- ROOM 4: KESELURUHAN & DATA PER HARI -->
        <section id="room-all" class="tab-content hidden space-y-6">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div class="bg-emerald-50 border border-emerald-200 p-4 rounded-2xl">
                    <span class="text-xs font-bold text-emerald-800 uppercase">Total Keseluruhan Infaq Harian</span>
                    <div id="all-box-infaq" class="text-2xl font-extrabold text-emerald-700 mt-1">Rp 0</div>
                    <div id="all-sub-infaq" class="text-xs text-emerald-700 mt-2">Hari ini: Rp 0 | Minggu ini: Rp 0 | Bulan ini: Rp 0</div>
                </div>
                <div class="bg-blue-50 border border-blue-200 p-4 rounded-2xl">
                    <span class="text-xs font-bold text-blue-800 uppercase">Total Keseluruhan Tabungan Qurban</span>
                    <div id="all-box-qurban" class="text-2xl font-extrabold text-blue-700 mt-1">Rp 0</div>
                    <div id="all-sub-qurban" class="text-xs text-blue-700 mt-2">Hari ini: Rp 0 | Minggu ini: Rp 0 | Bulan ini: Rp 0</div>
                </div>
            </div>

            <!-- Data Per Tanggal -->
            <div class="bg-white p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm">
                <h2 class="text-sm sm:text-base font-bold text-slate-800 mb-1">
                    Data Harian Per Tanggal: <span id="label-tanggal-harian" class="text-emerald-700"></span>
                </h2>
                <p class="text-xs text-slate-500 mb-3">Menampilkan semua KK yang mengisi Infaq Harian maupun Tabungan Qurban pada tanggal acuan di atas.</p>
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-slate-100 text-slate-700 border-b border-slate-200">
                                <th class="p-2.5">Tanggal</th>
                                <th class="p-2.5">Jam Input</th>
                                <th class="p-2.5">Nama KK</th>
                                <th class="p-2.5 text-right">Infaq Harian</th>
                                <th class="p-2.5 text-right">Tabungan Qurban</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-per-tanggal" class="divide-y divide-slate-100"></tbody>
                    </table>
                </div>
            </div>

            <!-- Tabel Utama Keseluruhan -->
            <div class="bg-white p-4 sm:p-5 rounded-2xl border border-slate-200 shadow-sm">
                <h2 class="text-sm sm:text-base font-bold text-slate-800 mb-3 pb-2 border-b border-slate-100">
                    Tabel Utama Keseluruhan (Nama KK, Infaq Harian, Tabungan Qurban)
                </h2>
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-slate-100 text-slate-700 border-b border-slate-200">
                                <th class="p-2.5">No</th>
                                <th class="p-2.5">Nama KK</th>
                                <th class="p-2.5 text-right">Total Infaq Harian</th>
                                <th class="p-2.5 text-right">Total Tabungan Qurban</th>
                            </tr>
                        </thead>
                        <tbody id="tbody-utama-all" class="divide-y divide-slate-100"></tbody>
                    </table>
                </div>
            </div>
        </section>

    </main>

    <script>
        const daftarKK = [
            "KK 01 - Bpk. H. Ahmad", "KK 02 - Bpk. Budi Santoso", "KK 03 - Bpk. Cipto Wibowo", "KK 04 - Bpk. Dedi Supriadi", "KK 05 - Bpk. Eko Prasetyo",
            "KK 06 - Bpk. Fajar Sidik", "KK 07 - Bpk. Gunawan", "KK 08 - Bpk. Haryanto", "KK 09 - Bpk. Irfan Hakim", "KK 10 - Bpk. Joko Susilo",
            "KK 11 - Bpk. Kasimin", "KK 12 - Bpk. Lukman Hakim", "KK 13 - Bpk. M. Rasyid", "KK 14 - Bpk. Nurhadi", "KK 15 - Bpk. Ony Supono",
            "KK 16 - Bpk. Purnomo", "KK 17 - Bpk. Qomarudin", "KK 18 - Bpk. Rahmat Hidayat", "KK 19 - Bpk. Slamet Riyadi", "KK 20 - Bpk. Taufik Hidayat",
            "KK 21 - Bpk. Untung S.", "KK 22 - Bpk. Wahyu Hidayat", "KK 23 - Bpk. Yanto", "KK 24 - Bpk. Yusuf", "KK 25 - Bpk. Zainal Arifin"
        ];

        const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbxN-EiNAMiobY51ZjQYKJrrOeaalJ4xC7Y4_TcwgP5-5sZrQZeGxvHu5R_sKGWEsDf7Zw/exec";

        let dataTransaksi = JSON.parse(localStorage.getItem('db_baitul_ihsan_v2')) || [];

        function getTodayLocal() {
            const d = new Date();
            const offset = d.getTimezoneOffset() * 60000;
            return new Date(d.getTime() - offset).toISOString().split('T')[0];
        }

        function updateJamRealtime() {
            const now = new Date();
            const jamStr = now.toLocaleTimeString('id-ID', { hour: '2-digit', minute: '2-digit', second: '2-digit' });
            const el = document.getElementById('input-waktu');
            if (el) el.value = jamStr;
        }

        document.addEventListener("DOMContentLoaded", () => {
            const today = getTodayLocal();
            document.getElementById('input-tanggal').value = today;
            document.getElementById('filter-tanggal').value = today;

            const selectKK = document.getElementById('input-kk');
            daftarKK.forEach(kk => {
                const opt = document.createElement('option');
                opt.value = kk;
                opt.textContent = kk;
                selectKK.appendChild(opt);
            });

            updateJamRealtime();
            setInterval(updateJamRealtime, 1000);
            renderSemua();
        });

        function setFilterHariIni() {
            document.getElementById('filter-tanggal').value = getTodayLocal();
            renderSemua();
        }

        function switchTab(tab) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.querySelectorAll('.tab-btn').forEach(el => {
                el.classList.remove('bg-emerald-600', 'text-white', 'shadow-sm');
                el.classList.add('text-slate-600');
            });
            document.getElementById('room-' + tab).classList.remove('hidden');
            const active = document.getElementById('tab-' + tab);
            active.classList.add('bg-emerald-600', 'text-white', 'shadow-sm');
            active.classList.remove('text-slate-600');
        }

        function formatRp(num) {
            return 'Rp ' + Number(num || 0).toLocaleString('id-ID');
        }

        function isSameWeek(dateStr, refDateStr) {
            const d = new Date(dateStr + 'T00:00:00');
            const ref = new Date(refDateStr + 'T00:00:00');
            const dayRef = (ref.getDay() + 6) % 7;
            const monday = new Date(ref);
            monday.setDate(ref.getDate() - dayRef);
            monday.setHours(0,0,0,0);
            const sunday = new Date(monday);
            sunday.setDate(monday.getDate() + 6);
            sunday.setHours(23,59,59,999);
            return d >= monday && d <= sunday;
        }

        function isSameMonth(dateStr, refDateStr) {
            return dateStr.substring(0, 7) === refDateStr.substring(0, 7);
        }

        function simpanTransaksi(e) {
            e.preventDefault();
            const kk = document.getElementById('input-kk').value;
            const jenis = document.getElementById('input-jenis').value;
            const nominal = parseFloat(document.getElementById('input-nominal').value);
            const tanggal = document.getElementById('input-tanggal').value;
            const waktu = new Date().toLocaleTimeString('id-ID', { hour: '2-digit', minute: '2-digit', second: '2-digit' });

            const trx = { id: Date.now(), tanggal, waktu, kk, jenis, nominal };
            dataTransaksi.push(trx);
            localStorage.setItem('db_baitul_ihsan_v2', JSON.stringify(dataTransaksi));

            document.getElementById('filter-tanggal').value = tanggal;
            document.getElementById('input-nominal').value = '';

            renderSemua();
            kirimKeSheet(trx);
            alert(`Berhasil disimpan untuk ${kk} pada tanggal ${tanggal} (${waktu})!`);
        }

        function kirimKeSheet(trxBaru) {
            if (!SCRIPT_URL.startsWith("http")) return;
            const payload = {
                transaksiBaru: trxBaru,
                semuaTransaksi: dataTransaksi,
                daftarKK: daftarKK
            };
            fetch(SCRIPT_URL, {
                method: 'POST',
                mode: 'no-cors',
                headers: { 'Content-Type': 'text/plain' },
                body: JSON.stringify(payload)
            }).catch(err => console.log("Gagal sinkron:", err));
        }

        function renderSemua() {
            const refDate = document.getElementById('filter-tanggal').value || getTodayLocal();
            document.getElementById('label-tanggal-harian').textContent = refDate;

            let rekap = {};
            daftarKK.forEach(kk => {
                rekap[kk] = {
                    infaqHari: 0, infaqMinggu: 0, infaqBulan: 0, infaqTotal: 0,
                    hariUnikInfaqBulanIni: new Set(),
                    qurbanHari: 0, qurbanMinggu: 0, qurbanBulan: 0, qurbanTotal: 0
                };
            });

            let totalInfaq = { hari: 0, minggu: 0, bulan: 0, semua: 0 };
            let totalQurban = { hari: 0, minggu: 0, bulan: 0, semua: 0 };

            dataTransaksi.forEach(t => {
                if (!rekap[t.kk]) return;
                const samaHari = (t.tanggal === refDate);
                const samaMinggu = isSameWeek(t.tanggal, refDate);
                const samaBulan = isSameMonth(t.tanggal, refDate);

                if (t.jenis === 'Infaq Harian') {
                    rekap[t.kk].infaqTotal += t.nominal;
                    totalInfaq.semua += t.nominal;
                    if (samaHari) {
                        rekap[t.kk].infaqHari += t.nominal;
                        totalInfaq.hari += t.nominal;
                    }
                    if (samaMinggu) {
                        rekap[t.kk].infaqMinggu += t.nominal;
                        totalInfaq.minggu += t.nominal;
                    }
                    if (samaBulan) {
                        rekap[t.kk].infaqBulan += t.nominal;
                        totalInfaq.bulan += t.nominal;
                        rekap[t.kk].hariUnikInfaqBulanIni.add(t.tanggal);
                    }
                } else if (t.jenis === 'Tabungan Qurban') {
                    rekap[t.kk].qurbanTotal += t.nominal;
                    totalQurban.semua += t.nominal;
                    if (samaHari) {
                        rekap[t.kk].qurbanHari += t.nominal;
                        totalQurban.hari += t.nominal;
                    }
                    if (samaMinggu) {
                        rekap[t.kk].qurbanMinggu += t.nominal;
                        totalQurban.minggu += t.nominal;
                    }
                    if (samaBulan) {
                        rekap[t.kk].qurbanBulan += t.nominal;
                        totalQurban.bulan += t.nominal;
                    }
                }
            });

            document.getElementById('infaq-all-hari').textContent = formatRp(totalInfaq.hari);
            document.getElementById('infaq-all-minggu').textContent = formatRp(totalInfaq.minggu);
            document.getElementById('infaq-all-bulan').textContent = formatRp(totalInfaq.bulan);
            document.getElementById('infaq-all-total').textContent = formatRp(totalInfaq.semua);

            document.getElementById('qurban-all-hari').textContent = formatRp(totalQurban.hari);
            document.getElementById('qurban-all-minggu').textContent = formatRp(totalQurban.minggu);
            document.getElementById('qurban-all-bulan').textContent = formatRp(totalQurban.bulan);
            document.getElementById('qurban-all-total').textContent = formatRp(totalQurban.semua);

            document.getElementById('all-box-infaq').textContent = formatRp(totalInfaq.semua);
            document.getElementById('all-sub-infaq').textContent = `Hari ini: ${formatRp(totalInfaq.hari)} | Minggu ini: ${formatRp(totalInfaq.minggu)} | Bulan ini: ${formatRp(totalInfaq.bulan)}`;
            document.getElementById('all-box-qurban').textContent = formatRp(totalQurban.semua);
            document.getElementById('all-sub-qurban').textContent = `Hari ini: ${formatRp(totalQurban.hari)} | Minggu ini: ${formatRp(totalQurban.minggu)} | Bulan ini: ${formatRp(totalQurban.bulan)}`;

            const tbodyInfaq = document.getElementById('tbody-infaq-kk');
            tbodyInfaq.innerHTML = '';
            let jumlahSudahCeklist = 0;

            daftarKK.forEach((kk, idx) => {
                const r = rekap[kk];
                const sudahIsi = r.infaqHari > 0;
                if (sudahIsi) jumlahSudahCeklist++;

                const jmlHari = Math.min(r.hariUnikInfaqBulanIni.size, 30);
                const persen = Math.round((jmlHari / 30) * 100);

                tbodyInfaq.innerHTML += `
                    <tr class="hover:bg-slate-50">
                        <td class="p-2.5 text-slate-500">${idx + 1}</td>
                        <td class="p-2.5 font-semibold text-slate-800">${kk}</td>
                        <td class="p-2.5 text-center">
                            ${sudahIsi 
                                ? '<span class="inline-flex items-center px-2 py-0.5 rounded-full text-[11px] font-bold bg-emerald-100 text-emerald-700"><i class="fa-solid fa-square-check mr-1"></i> Sudah</span>' 
                                : '<span class="inline-flex items-center px-2 py-0.5 rounded-full text-[11px] text-slate-400 bg-slate-100"><i class="fa-regular fa-square mr-1"></i> Belum</span>'}
                        </td>
                        <td class="p-2.5 text-center">
                            <div class="flex flex-col items-center">
                                <div class="w-20 bg-slate-200 h-2 rounded-full overflow-hidden">
                                    <div class="bg-emerald-600 h-2 rounded-full" style="width:${persen}%"></div>
                                </div>
                                <span class="text-[11px] font-bold text-slate-700 mt-0.5">${jmlHari}/30 Hari (${persen}%)</span>
                            </div>
                        </td>
                        <td class="p-2.5 text-right font-semibold text-emerald-700">${formatRp(r.infaqHari)}</td>
                        <td class="p-2.5 text-right text-slate-700">${formatRp(r.infaqMinggu)}</td>
                        <td class="p-2.5 text-right text-slate-700">${formatRp(r.infaqBulan)}</td>
                        <td class="p-2.5 text-right font-bold text-slate-900">${formatRp(r.infaqTotal)}</td>
                    </tr>
                `;
            });
            document.getElementById('info-ceklist-infaq').textContent = `Terisi: ${jumlahSudahCeklist} dari ${daftarKK.length} KK (${refDate})`;

            const tbodyQurban = document.getElementById('tbody-qurban-kk');
            tbodyQurban.innerHTML = '';
            daftarKK.forEach((kk, idx) => {
                const r = rekap[kk];
                tbodyQurban.innerHTML += `
                    <tr class="hover:bg-slate-50">
                        <td class="p-2.5 text-slate-500">${idx + 1}</td>
                        <td class="p-2.5 font-semibold text-slate-800">${kk}</td>
                        <td class="p-2.5 text-right font-semibold text-blue-700">${formatRp(r.qurbanHari)}</td>
                        <td class="p-2.5 text-right text-slate-700">${formatRp(r.qurbanMinggu)}</td>
                        <td class="p-2.5 text-right text-slate-700">${formatRp(r.qurbanBulan)}</td>
                        <td class="p-2.5 text-right font-bold text-slate-900">${formatRp(r.qurbanTotal)}</td>
                    </tr>
                `;
            
