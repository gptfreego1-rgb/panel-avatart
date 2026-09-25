Avatar Panel Web — separated files

index.html = struktur
style.css  = tampilan
app.js     = logic + API

API default: https://avatar.offc.web.id

Catatan keamanan:
Memisahkan JS dari HTML tidak menyembunyikan JS dari pengunjung. Browser tetap
menerima app.js dan user dapat melihatnya. Jangan menaruh API secret, password
database, JWT signing key, atau kredensial rahasia di frontend.

Keamanan akses harus tetap ditegakkan oleh backend/API.
