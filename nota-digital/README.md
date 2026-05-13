# 🕌 KAFA Learn — Sistem Pembelajaran Digital

> Platform pembelajaran digital premium untuk pelajar KAFA berumur 8 tahun.  
> Gaya Fintech for Kids · Mesra Mobile & Desktop · Interaktif & Ceria

---

## 🌟 Ciri-Ciri Utama

- 🗺️ **Peta Minda Interaktif** — Navigasi topik dalam bentuk peta minda visual
- 📖 **Nota Digital** — Nota dalam gaya blog dengan kandungan kaya (jadual, kotak info, fakta menarik)
- 🏆 **Sistem Pencapaian** — Badge & mata ilmu untuk motivasi pelajar
- 📱 **Mesra Mobile & Desktop** — Responsive sepenuhnya
- 🌙 **Tema Gelap Premium** — Gaya fintech bertema langit malam & emas Islam

---

## 📁 Struktur Folder

```
kafa-learn/
│
├── index.html                  ← Dashboard Utama (3 Subjek)
├── subjek-sirah.html           ← Peta Minda Sirah
├── subjek-ibadah.html          ← Peta Minda Ibadah
├── subjek-jawi.html            ← Peta Minda Jawi
│
├── css/
│   └── style.css               ← Semua CSS (dashboard + nota + peta minda)
│
├── js/
│   └── main.js                 ← JavaScript utama (stars, animasi)
│
└── nota/
    ├── sirah/
    │   ├── biodata-nabi.html   ← Topik 1: Biodata Nabi Muhammad SAW
    │   ├── anak-nabi.html      ← Topik 2: Nama Anak-Anak Nabi SAW
    │   ├── ibu-susuan-1.html   ← Topik 3: Ibu Susuan Pertama
    │   └── ibu-susuan-2.html   ← Topik 4: Ibu Susuan Kedua
    │
    ├── ibadah/                 ← (Akan datang)
    │   └── README.md
    │
    └── jawi/                   ← (Akan datang)
        └── README.md
```

---

## 🚀 Cara Guna (GitHub Pages)

1. **Fork** atau **Upload** semua fail ke repo GitHub anda
2. Pergi ke **Settings → Pages**
3. Pilih branch `main` dan folder `/ (root)`
4. Klik **Save** — website anda akan aktif dalam beberapa minit!
5. URL: `https://[username].github.io/[repo-name]/`

---

## ➕ Cara Tambah Nota Baru (Tanpa Coding Tambahan)

### Langkah 1 — Salin templat nota
Buka mana-mana fail nota yang sedia ada (contoh: `nota/sirah/biodata-nabi.html`) dan **salin** ke fail baru.

### Langkah 2 — Tukar kandungan
Edit bahagian `<div class="nota-content">` sahaja. Gunakan blok HTML ini:

```html
<!-- Blok Nota Biasa -->
<div class="nota-block">
  <h2>🌟 Tajuk Bahagian</h2>
  <p>Teks penerangan di sini...</p>
</div>

<!-- Kotak Info -->
<div class="info-box">
  📌 <strong>Perkara penting:</strong> Penerangan di sini
</div>

<!-- Jadual -->
<table class="nota-table">
  <tr><th>Kolum 1</th><th>Kolum 2</th></tr>
  <tr><td>Data 1</td><td>Data 2</td></tr>
</table>

<!-- Fakta Menarik -->
<div class="fun-fact">
  <div class="ff-icon">💡</div>
  <p><strong>Tahukah Kamu?</strong> Fakta menarik di sini...</p>
</div>

<!-- Chip Warna -->
<div class="highlight-row">
  <div class="highlight-chip gold">Teks emas</div>
  <div class="highlight-chip">Teks hijau</div>
  <div class="highlight-chip purple">Teks ungu</div>
</div>
```

### Langkah 3 — Daftarkan di Peta Minda
Buka `subjek-sirah.html` (atau subjek berkenaan) dan tambah kad topik baru dalam `<div class="topics-grid">`:

```html
<div class="topic-card" style="animation-delay:0.5s">
  <div class="topic-card-header">
    <div class="topic-num">5</div>
    <div class="topic-card-title">Tajuk Topik Baru</div>
  </div>
  <div class="topic-card-body">
    <p>Penerangan ringkas topik ini.</p>
    <a href="nota/sirah/nama-fail-baru.html" class="btn-read">📖 Baca Nota →</a>
  </div>
</div>
```

### Langkah 4 — Commit & Push ke GitHub
```bash
git add .
git commit -m "Tambah topik baru: [nama topik]"
git push
```

---

## 📚 Subjek & Topik Semasa

### ✅ Sirah (4 Topik Aktif)
| # | Tajuk | Fail |
|---|-------|------|
| 1 | Biodata Nabi Muhammad SAW | `nota/sirah/biodata-nabi.html` |
| 2 | Nama Anak-Anak Nabi Muhammad SAW | `nota/sirah/anak-nabi.html` |
| 3 | Ibu Susuan Nabi Muhammad Yang Pertama | `nota/sirah/ibu-susuan-1.html` |
| 4 | Ibu Susuan Nabi Muhammad Yang Kedua | `nota/sirah/ibu-susuan-2.html` |

### 🔔 Ibadah (Akan Datang)
### 🔔 Jawi (Akan Datang)

---

## 🎨 Warna & Tema

| Warna | Kod | Guna |
|-------|-----|------|
| Emas | `#F5C842` | Aksen utama, tajuk, butang |
| Biru Gelap | `#0A0F2E` | Latar belakang |
| Hijau | `#2ECC8A` | Ibadah, chip aktif |
| Ungu | `#7C5FD4` | Jawi, fun fact |

---

Made with ❤️ for KAFA students · Dibina untuk generasi Muslim yang soleh 🌙
