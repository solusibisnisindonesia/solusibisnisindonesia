# Muhammad Noor Hasan Siregar

Pengembang aplikasi AI berbahasa Indonesia untuk usaha kecil. Indonesia.

Saya membangun perangkat lunak yang dipakai orang non-teknis untuk pekerjaan nyata: alur yang mudah diikuti, data yang tetap di komputer sendiri, dan hasil yang bisa ditinjau sebelum dipakai.

## Karya utama · Solusi Bisnis

[**SolusiBisnis.com**](https://solusibisnis.com/) — merek dan kanal saya untuk membantu UMKM memakai AI dan teknologi digital: artikel, panduan, dan roadmap belajar. Dari kanal itu lahir aplikasi yang bisa dipakai hari ini: Kantor Sobis.

### Kantor Sobis — asisten usaha untuk UMKM

[Kantor Sobis](https://github.com/solusibisnisindonesia/kantor-sobis) membantu pemilik usaha menyusun naskah promosi dari informasi usahanya sendiri: pesan WhatsApp, caption Instagram, dan deskripsi produk toko online. Alurnya tiga langkah — kenalkan usaha, buat promosi, tinjau lalu ekspor.

- **Berjalan lokal.** Satu instalasi untuk satu usaha, tanpa akun pelanggan, tanpa langganan. Data tersimpan di SQLite di komputer Anda.
- **Bisa dicoba gratis.** Mode contoh simulasi tidak memanggil AI dan tidak memerlukan kunci API. Biaya AI hanya muncul setelah Anda mengisi kunci sendiri dan menyetujui penggunaan berbayar.
- **Hasil harus disetujui.** Revisi disimpan sebagai versi baru; tombol salin dan unduh baru aktif setelah naskah disetujui. Profil usaha saat dibuat ikut tersimpan, jadi mengubah profil tidak mengubah pekerjaan lama.

[**Coba di Windows**](https://github.com/solusibisnisindonesia/kantor-sobis#mulai-di-windows) — unduh ZIP, klik `install.bat`, lalu `run.bat`. Butuh Python 3.12+.

## Cara saya bekerja

- **Tinjau sebelum pakai.** Fitur yang menyentuh uang atau data pelanggan harus punya langkah persetujuan yang jelas, bukan tersembunyi di pengaturan.
- **Data milik pengguna.** Aplikasi lokal, database lokal, tanpa akun. Berkas rahasia dan data pelanggan tidak pernah ikut terunggah ke repositori publik.
- **Uji dulu, rilis kemudian.** Kantor Sobis 1.2.0 dirilis dengan 44 tes Python, 25 pemeriksaan integrasi, dan 33 tes JavaScript yang lulus, serta catatan perubahan di [CHANGELOG](https://github.com/solusibisnisindonesia/kantor-sobis/blob/main/CHANGELOG.md).
- **Batas disebut terang-terangan.** Belum ada panggilan AI berbayar sungguhan yang diuji, dan aplikasi ini belum ditujukan untuk akses internet publik. Batas itu ditulis di README, bukan disembunyikan.

## Teknologi

Python · FastAPI · SQLite · JavaScript tanpa proses build · Server-Sent Events · integrasi LLM melalui OpenRouter · pengujian otomatis backend dan frontend.

## Sedang dikerjakan

Dukungan tim dan pemisahan ruang untuk usaha yang mengelola beberapa merek, setelah alur promosi satu usaha selesai.

## Kontak

- Situs: [solusibisnis.com](https://solusibisnis.com/)
- GitHub: [@solusibisnisindonesia](https://github.com/solusibisnisindonesia)
- Proyek terbuka: [Kantor Sobis](https://github.com/solusibisnisindonesia/kantor-sobis) — lisensi MIT, silakan dipakai dan diubah.
