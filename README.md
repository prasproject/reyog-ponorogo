# Tabuh Reyog (Prototipe)

Gim ritme gamelan Reyog Ponorogo karya Hastaria Studio. Satu file HTML statis tanpa build dan tanpa server: font sudah tertanam, bunyi gamelan dibuat langsung di browser (Web Audio).

## Deploy ke Vercel

**Lewat dashboard**
1. Ekstrak zip ini.
2. Buka vercel.com → Add New → Project → pilih folder `tabuh-reyog` (atau unggah lewat repo GitHub berisi folder ini).
3. Framework Preset: **Other**. Build Command dan Output Directory dikosongkan.
4. Klik Deploy.

**Lewat terminal**
```
npm i -g vercel
cd tabuh-reyog
vercel --prod
```

## Isi
- `index.html` : seluruh gim (HTML, CSS, JS, font).
- `vercel.json` : pengaturan URL bersih dan cache.

## Sumber notasi lagu
Notasi lagu daerah disalin dari not angka di Sekitar Musik (sekitarmusik.com), dengan tautan sumber per lagu ditampilkan di popup "Siap Main". Lagu yang penciptanya tercatat dan haknya masih berlaku (Gambang Suling, Gundul-gundul Pacul, Suwe Ora Jamu, Jaranan, Ampar-ampar Pisang) sengaja dikunci sampai ada izin.

Font: Fredoka (SIL Open Font License).
