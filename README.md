# kodexa

Situs resmi **Kodexa**, IDE JavaScript di Android: halaman unduh APK, daftar isi
aplikasi, tangkapan layar, dan cara pasang.

- Situs: <https://slice-code.github.io/kodexa/>
- Kode aplikasi: repo privat `slice-code/kodexa-app`
- Unduhan: aset rilis di repo ini (`kodexa-<versi>.apk`)

## Isi

| Berkas | Keterangan |
|---|---|
| `index.html` | satu halaman, bahasa Indonesia |
| `styles.css` | gaya halaman + stempel Hallmark (tema Terrazzo) |
| `tokens.css`, `base.css` | token tema dan aturan dasar dari scaffold |
| `fonts.css`, `assets/fonts/` | Syne 700, Onest 400/500, JetBrains Mono 500 (latin, self-hosted) |
| `assets/img/` | tangkapan layar asli aplikasi (webp) + ikon |
| `LICENSE.txt`, `NOTICE.txt` | Apache-2.0, atribusi pihak ketiga |

## Memperbarui

1. Tangkapan layar baru: taruh di `assets/img/`, jaga rasio (`editor.webp` 800x620,
   `agent.webp` 800x1000, `komponen.webp` 1340x800).
2. Versi baru: perbarui angka di `index.html` (versi, ukuran, tautan rilis), lalu
   unggah APK ke rilis dengan nama `kodexa-<versi>.apk`.
3. Periksa tampilan: `node <skill-hallmark>/scripts/sloplint.mjs index.html styles.css --genre modern-minimal --render`.

Halaman memakai font self-hosted, tanpa permintaan ke pihak ketiga.
