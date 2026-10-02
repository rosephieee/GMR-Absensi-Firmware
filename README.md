# GMR Absensi — firmware releases

Biner rilis resmi untuk alat GMR ABSENSI (sensor R558). Alat mengambil `R558/manifest.json` dan
`R558/firmware.bin` dari repo ini saat Admin mengirim `/update` di Telegram.

Setiap rilis ditandatangani (ECDSA P-256) dengan kunci privat GMR; alat menolak firmware yang
tanda tangan atau hash-nya tidak cocok. Repo ini tidak berisi kode sumber.
