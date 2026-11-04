WEDDING PLANNER — VERSI OFFLINE

Isi:
- index.html: aplikasi utama (juga dapat dibuka langsung secara offline).
- manifest.webmanifest dan sw.js: dukungan instalasi PWA dan cache offline.

CARA PALING MUDAH (offline lokal):
1. Ekstrak ZIP ini.
2. Buka folder, lalu klik dua kali index.html.
3. Aplikasi berjalan di browser. Data tersimpan di browser/perangkat tersebut.

CARA MENJADIKAN WEBSITE PWA:
1. Unggah isi folder ini ke hosting statis yang mendukung HTTPS (misalnya GitHub Pages atau Netlify).
2. Buka alamat HTTPS tersebut saat online sekali.
3. Tunggu halaman termuat, lalu pilih Install app / Add to Home Screen dari browser.
4. Setelah cache terbentuk, aplikasi dapat dibuka offline.

Catatan:
- Service worker PWA memerlukan HTTPS (localhost juga diizinkan). Karena itu, file index.html lokal tetap dapat dipakai offline, tetapi fitur instalasi PWA melalui service worker memerlukan hosting HTTPS.
- Data tersimpan lokal di browser/perangkat, tidak otomatis tersinkron antar HP/laptop. Jangan hapus data browser; buat cadangan secara berkala (fitur ekspor/impor belum disertakan).
- Data nama dan angka awal hanya contoh dan dapat diedit.
