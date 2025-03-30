# The Hari Raya - Digital THR

Ini adalah proyek sederhana untuk membuat amplop THR digital dengan efek animasi dan QR code.

## 📌 Fitur Utama
- Animasi amplop yang bisa diklik untuk membuka pesan THR.
- Efek emoji jatuh untuk mempercantik tampilan.
- QR Code yang bisa di-scan untuk menerima THR.

## 📂 Cara Menggunakan
1. **Buka file** `index.html` di browser.
2. **Klik amplop** untuk membuka pesan THR.
3. **Scan QR Code** untuk mengakses link THR.

## 🔧 Kustomisasi QR Code
Secara default, QR Code mengarah ke `https://link-thr-kamu.com`. Jika ingin mengubahnya:

1. Buka file `index.html`.
2. Temukan bagian berikut dalam script:

```html
<script>
    new QRCode(document.getElementById("qrcode"), {
        text: "https://link-thr-kamu.com",
        width: 128,
        height: 128
    });
</script>
```

3. Ganti `https://link-thr-kamu.com` dengan link yang diinginkan.
4. Simpan perubahan dan buka ulang file di browser.

## 🛠 Teknologi yang Digunakan
- **HTML**: Struktur halaman.
- **CSS (Tailwind CSS)**: Styling dan animasi.
- **JavaScript**: Interaksi amplop dan QR code.
- **QRCode.js**: Membuat QR Code otomatis.

## 🎉 Selamat Hari Raya!
Semoga proyek ini bermanfaat untuk berbagi kebahagiaan di hari raya! 🌙✨

