# Koreksi Lembar Jawab
Aplikasi web (PWA) untuk mengoreksi lembar jawab pilihan ganda dari foto HP. Semua pemrosesan terjadi di HP, tidak ada gambar yang dikirim ke mana pun.
Pembuat: Fakih Agnia, S.Pd · SMK Tri Sukses Depok (ubah nama di bagian footer index.html jika perlu).

## Unggah ke GitHub Pages
1. Buat repositori baru, unggah isi zip (index.html, sw.js, manifest.webmanifest, icons/).
2. Settings → Pages → Branch main, folder root → Save. Buka alamat yang muncul.

## Pasang di HP
Android (Chrome): menu ⋮ → Instal aplikasi. iPhone (Safari): Bagikan → Tambah ke Layar Utama.

## Tiga langkah
1. Pengaturan: buat ujian, isi kunci (ketuk, tempel teks, atau pindai lembar kunci).
2. Pindai: foto satu kertas utuh (3 lembar) atau satu lembar, isi nama, Simpan.
3. Hasil: lihat peringkat, analisis soal, ekspor CSV.

## Lembar jawab
Tata letak lembar ada di kode (konstanta W, H, CP, fungsi bp). Penanda: 4 kotak hitam padat ±20 satuan di sudut, gelembung dalam 2 kolom x 25 soal. PDF cetak belum disertakan.

## Keputusan & batas
- Soal ragu-ragu diberi bingkai putus-putus (cek ulang). Soal ganda dihitung salah.
- Belum diuji dengan HP sungguhan dan tulisan tangan nyata. Uji 5–10 lembar asli sebelum dipakai ujian.
