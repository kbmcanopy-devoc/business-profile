# KBM Canopy — SEO & GA4 tahap 1

## Perubahan
- Mempertahankan GA4 Measurement ID yang sudah ada: `G-2EJ38X3309`.
- Memperluas event klik homepage: `click_whatsapp`, `click_phone`, `click_email`, `click_maps`, dan `view_portfolio`.
- Formulir penawaran homepage kini mengirim `generate_lead` dan `click_whatsapp`.
- Tidak mengirim nama, nomor WhatsApp, area, atau isi pesan formulir ke GA4.
- Mengubah schema homepage dari `Organization` menjadi `HomeAndConstructionBusiness`.
- Memperbarui `lastmod` sitemap untuk dua URL yang tersedia.
- Mempertahankan kedua meta `google-site-verification` karena kode yang aktif belum dikonfirmasi.

## Setelah deploy
1. Uji event WhatsApp, telepon, email, Maps, portofolio, dan formulir di GA4 DebugView/Realtime.
2. Tandai `generate_lead` sebagai key event di GA4 jika sesuai tujuan pengukuran.
3. Di Search Console, kirim ulang `https://kbm-canopy.netlify.app/sitemap.xml`.
4. Gunakan URL Inspection untuk homepage dan `/kanopi-depok/`.

## Catatan
- Sitemap hanya mencantumkan homepage dan halaman `/kanopi-depok/` yang tersedia.
- Event baru tidak otomatis menjadi key event/konversi; pengaturan dilakukan di GA4.
