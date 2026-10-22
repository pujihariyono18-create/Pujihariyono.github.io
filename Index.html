<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aplikasi Data Siswa</title>
<style>
  * { box-sizing: border-box; }
  body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #eef2f7;
    margin: 0;
    padding: 20px;
  }
  .container { max-width: 900px; margin: auto; }
  h1 { text-align: center; color: #1e3a5f; margin-bottom: 5px; }
  .subtitle { text-align: center; color: #666; margin-bottom: 25px; font-size: 14px; }

  .card {
    background: #fff;
    border-radius: 12px;
    padding: 25px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    margin-bottom: 20px;
  }
  .card h2 {
    font-size: 18px;
    color: #1e3a5f;
    margin-top: 0;
    border-bottom: 2px solid #eef2f7;
    padding-bottom: 10px;
  }

  .form-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
  }
  .form-group { display: flex; flex-direction: column; }
  .form-group.full { grid-column: 1 / -1; }

  label {
    font-size: 13px;
    font-weight: 600;
    color: #444;
    margin-bottom: 6px;
  }
  input, textarea {
    padding: 10px 12px;
    border: 1px solid #ccd5e0;
    border-radius: 8px;
    font-size: 14px;
    font-family: inherit;
    transition: border 0.2s;
  }
  input:focus, textarea:focus {
    outline: none;
    border-color: #3b82f6;
    box-shadow: 0 0 0 3px rgba(59,130,246,0.15);
  }
  textarea { resize: vertical; min-height: 60px; }

  .btn-row {
    display: flex;
    gap: 10px;
    margin-top: 20px;
    flex-wrap: wrap;
  }
  button {
    padding: 12px 22px;
    border: none;
    border-radius: 8px;
    font-size: 14px;
    font-weight: 600;
    cursor: pointer;
    transition: transform 0.1s, opacity 0.2s;
  }
  button:active { transform: scale(0.98); }
  button:disabled { opacity: 0.6; cursor: not-allowed; }
  .btn-primary { background: #1e3a5f; color: #fff; }
  .btn-primary:hover { opacity: 0.9; }
  .btn-secondary { background: #e2e8f0; color: #333; }
  .btn-secondary:hover { background: #d1dae6; }
  .btn-save { background: #16a34a; color: #fff; }
  .btn-save:hover { opacity: 0.9; }

  #hasil {
    background: #fff;
    padding: 30px 35px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    display: none;
  }
  #hasil h2 {
    font-size: 18px;
    color: #1e3a5f;
    margin-top: 0;
    border-bottom: 2px solid #eef2f7;
    padding-bottom: 10px;
  }
  .data-table {
    width: 100%;
    border-collapse: collapse;
    margin: 15px 0;
  }
  .data-table td {
    padding: 10px 8px;
    vertical-align: top;
    font-size: 15px;
    border-bottom: 1px solid #f0f3f7;
  }
  .data-table td:first-child {
    width: 230px;
    font-weight: 600;
    color: #555;
  }
  .data-table td:last-child { color: #111; }

  .status {
    margin-top: 12px;
    font-size: 14px;
    padding: 10px 14px;
    border-radius: 8px;
    display: none;
  }
  .status.success { background: #dcfce7; color: #166534; display: block; }
  .status.error   { background: #fee2e2; color: #991b1b; display: block; }

  @media (max-width: 600px) {
    .form-grid { grid-template-columns: 1fr; }
    #hasil { padding: 20px; }
    .data-table td:first-child { width: 140px; font-size: 14px; }
    .data-table td:last-child { font-size: 14px; }
  }
</style>
</head>
<body>
<div class="container">
  <h1>Data Siswa SMAN 1 Gambiran</h1>
  <p class="subtitle">Isi data siswa di bawah ini, lalu klik <b>Tampilkan Data</b>.</p>

  <!-- FORM -->
  <div class="card" id="formCard">
    <h2>Form Data Siswa</h2>
    <div class="form-grid">
      <div class="form-group full">
        <label>Nama Lengkap</label>
        <input type="text" id="nama" value="" placeholder="Nama siswa">
      </div>
      <div class="form-group">
        <label>Tempat Lahir</label>
        <input type="text" id="tempatLahir" value="" placeholder="Tempat lahir">
      </div>
      <div class="form-group">
        <label>Tanggal Lahir</label>
        <input type="text" id="tanggalLahir" value="" placeholder="Tanggal lahir">
      </div>
      <div class="form-group">
        <label>Kelas</label>
        <input type="text" id="kelas" value="" placeholder="Kelas">
      </div>
      <div class="form-group">
        <label>NIS / NISN</label>
        <input type="text" id="nis" value="" placeholder="NIS / NISN">
      </div>
      <div class="form-group full">
        <label>Nama Orang Tua / Wali</label>
        <input type="text" id="orangTua" value="" placeholder="Nama orang tua">
      </div>
      <div class="form-group full">
        <label>Alamat</label>
        <textarea id="alamat" placeholder="Alamat lengkap"></textarea>
      </div>

      <div class="form-group full">
        <label>Keperluan</label>
        <input type="text" id="keperluan" value="">
      </div>
      <div class="form-group">
        <label>Tanggal Mulai Kegiatan</label>
        <input type="date" id="tglMulai">
      </div>
      <div class="form-group">
        <label>Tanggal Akhir Kegiatan</label>
        <input type="date" id="tglAkhir">
      </div>
      <div class="form-group full">
        <label>Tempat Kegiatan</label>
        <input type="text" id="tempatKegiatan" placeholder="">
      </div>
    </div>

    <div class="btn-row">
      <button class="btn-primary" onclick="tampilkanData()">📋 Tampilkan Data</button>
      <button class="btn-secondary" onclick="resetForm()">↺ Reset</button>
    </div>
  </div>

  <!-- HASIL: HANYA DATA TERISI -->
  <div id="hasil">
    <h2>Data Siswa</h2>
    <table class="data-table">
      <tr><td>Nama</td><td id="outNama"></td></tr>
      <tr><td>Tempat, Tanggal Lahir</td><td id="outTTL"></td></tr>
      <tr><td>Kelas</td><td id="outKelas"></td></tr>
      <tr><td>NIS / NISN</td><td id="outNis"></td></tr>
      <tr><td>Nama Orang Tua / Wali</td><td id="outOrangTua"></td></tr>
      <tr><td>Alamat</td><td id="outAlamat"></td></tr>
      <tr><td>Keperluan</td><td id="outKeperluan"></td></tr>
      <tr><td>Tanggal Mulai Kegiatan</td><td id="outTglMulai"></td></tr>
      <tr><td>Tanggal Akhir Kegiatan</td><td id="outTglAkhir"></td></tr>
      <tr><td>Tempat Kegiatan</td><td id="outTempatKegiatan"></td></tr>
    </table>

    <div id="status" class="status"></div>

    <div class="btn-row">
      <button class="btn-save" onclick="simpanKeSheets()" id="btnSimpan">Kirim</button>
      <button class="btn-secondary" onclick="kembaliKeForm()">← Edit Data</button>
    </div>
  </div>
</div>

<!-- Iframe tersembunyi untuk menerima respons form -->
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;"></iframe>

<script>
  const bulan = ['Januari','Februari','Maret','April','Mei','Juni',
                 'Juli','Agustus','September','Oktober','November','Desember'];

  function formatTanggalID(dateStr) {
    if (!dateStr) return '-';
    const d = new Date(dateStr);
    if (isNaN(d)) return dateStr;
    return d.getDate() + ' ' + bulan[d.getMonth()] + ' ' + d.getFullYear();
  }

  function tampilkanData() {
    const nama           = document.getElementById('nama').value.trim();
    const tempat         = document.getElementById('tempatLahir').value.trim();
    const tanggal        = document.getElementById('tanggalLahir').value.trim();
    const kelas          = document.getElementById('kelas').value.trim();
    const nis            = document.getElementById('nis').value.trim();
    const orangTua       = document.getElementById('orangTua').value.trim();
    const alamat         = document.getElementById('alamat').value.trim();
    const keperluan      = document.getElementById('keperluan').value.trim();
    const tglMulai       = document.getElementById('tglMulai').value;
    const tglAkhir       = document.getElementById('tglAkhir').value;
    const tempatKegiatan = document.getElementById('tempatKegiatan').value.trim();

    if (!nama || !tempat || !tanggal || !kelas || !nis || !orangTua || !alamat || !keperluan) {
      alert('⚠️ Mohon lengkapi semua data siswa & keperluan terlebih dahulu!');
      return;
    }
    if (!tglMulai || !tglAkhir) {
      alert('⚠️ Mohon isi tanggal mulai dan tanggal akhir kegiatan!');
      return;
    }
    if (new Date(tglAkhir) < new Date(tglMulai)) {
      alert('⚠️ Tanggal akhir tidak boleh lebih awal dari tanggal mulai!');
      return;
    }
    if (!tempatKegiatan) {
      alert('⚠️ Mohon isi tempat kegiatan!');
      return;
    }

    document.getElementById('outNama').textContent           = nama;
    document.getElementById('outTTL').textContent            = tempat + ', ' + tanggal;
    document.getElementById('outKelas').textContent          = kelas;
    document.getElementById('outNis').textContent            = nis;
    document.getElementById('outOrangTua').textContent       = orangTua;
    document.getElementById('outAlamat').textContent         = alamat;
    document.getElementById('outKeperluan').textContent      = keperluan;
    document.getElementById('outTglMulai').textContent       = formatTanggalID(tglMulai);
    document.getElementById('outTglAkhir').textContent       = formatTanggalID(tglAkhir);
    document.getElementById('outTempatKegiatan').textContent = tempatKegiatan;

    const btn = document.getElementById('btnSimpan');
    btn.disabled = false;
    btn.textContent = 'Kirim';

    const st = document.getElementById('status');
    st.className = 'status';
    st.textContent = '';

    document.getElementById('formCard').style.display = 'none';
    document.getElementById('hasil').style.display = 'block';
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  function kembaliKeForm() {
    document.getElementById('hasil').style.display = 'none';
    document.getElementById('formCard').style.display = 'block';
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  function resetForm() {
    if (confirm('Reset semua data ke nilai awal?')) {
      document.getElementById('nama').value           = 'Puji Hariyono';
      document.getElementById('tempatLahir').value    = 'Banyuwangi';
      document.getElementById('tanggalLahir').value   = '5 Agustus 2009';
      document.getElementById('kelas').value          = 'XI 1';
      document.getElementById('nis').value            = '8003 / 0097993319';
      document.getElementById('orangTua').value       = 'Mulyono';
      document.getElementById('alamat').value         = 'Dusun Kampung Baru RT 01 RW 03 Desa Jajag, Kecamatan Gambiran, Kabupaten Banyuwangi';
      document.getElementById('keperluan').value      = 'Administrasi pendaftaran beasiswa';
      document.getElementById('tempatKegiatan').value = '';
      setDefaultTanggal();
    }
  }

  function setDefaultTanggal() {
    const today = new Date();
    const next  = new Date();
    next.setDate(today.getDate() + 7);
    const iso = d => d.toISOString().split('T')[0];
    document.getElementById('tglMulai').value = iso(today);
    document.getElementById('tglAkhir').value = iso(next);
  }

  // ====== URL WEB APP ANDA ======
  var WEB_APP_URL = "https://script.google.com/macros/s/AKfycbzW15PWkWwwBEHB57yRPrPf3HWIyH_19LweRJjLYRaOqKVN-ncZ-F97Uev5xrG3euxAww/exec";

  function simpanKeSheets() {
    const btn = document.getElementById("btnSimpan");
    const st  = document.getElementById("status");
    btn.disabled = true;
    btn.textContent = "⏳ Mengirim...";
    st.className = "status";
    st.textContent = "";

    // Buat form sementara untuk submit (metode paling stabil, bebas CORS)
    const form = document.createElement('form');
    form.method = 'POST';
    form.action = WEB_APP_URL;
    form.target = 'hidden_iframe';
    form.style.display = 'none';

    const fields = {
      nama:           document.getElementById("outNama").textContent,
      tempatLahir:    document.getElementById("tempatLahir").value.trim(),
      tanggalLahir:   document.getElementById("tanggalLahir").value.trim(),
      kelas:          document.getElementById("outKelas").textContent,
      nis:            document.getElementById("outNis").textContent,
      orangTua:       document.getElementById("outOrangTua").textContent,
      alamat:         document.getElementById("outAlamat").textContent,
      keperluan:      document.getElementById("outKeperluan").textContent,
      tglMulai:       document.getElementById("outTglMulai").textContent,
      tglAkhir:       document.getElementById("outTglAkhir").textContent,
      tempatKegiatan: document.getElementById("outTempatKegiatan").textContent,
      nomorSurat:     ""
    };

    for (const key in fields) {
      const input = document.createElement('input');
      input.type = 'hidden';
      input.name = key;
      input.value = fields[key];
      form.appendChild(input);
    }

    document.body.appendChild(form);
    form.submit();
    document.body.removeChild(form);

    // Karena respons masuk ke iframe tersembunyi, tampilkan pesan sukses setelah delay
    setTimeout(function() {
      st.className = "status success";
      st.textContent = "✅ Data berhasil dikirim! Silakan Konfirmasi Ke Pak Puji.";
      btn.textContent = "✅ Terkirim";
    }, 2000);
  }

  setDefaultTanggal();
</script>
</body>
</html>