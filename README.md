# 🌐 MAOU Bot VPN 

**⚡ Bot Otomatis Pembelian Layanan VPN - Cepat & Mudah!**  
Nikmati pengalaman ber-VPN yang mulus dengan bot otomatis kami!

---

## 🚀 Fitur Unggulan

| Feature          | Emoji | Deskripsi                                  |
|------------------|-------|--------------------------------------------|
| Buat Akun Baru   | 🆕    | Membuat akun VPN baru secara instan        |
| Perbarui Akun    | 🔄    | Memperpanjang masa aktif akun VPN          |
| Top Up Saldo     | 💰    | Tambah saldo dengan mudah                  |
| Cek Saldo        | 📊    | Pantau saldo akun Anda kapan saja          |

---

## 🛠️ Teknologi

<div align="center">
  
![Node.js](https://img.shields.io/badge/Node.js-14%2B-green?logo=node.js)
![SQLite](https://img.shields.io/badge/SQLite-3-blue?logo=sqlite)
![Telegraf](https://img.shields.io/badge/Telegraf-Bot%20API-yellow?logo=telegram)
![Axios](https://img.shields.io/badge/Axios-HTTP%20Client-purple)

</div>


## Installasi Otomatis
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update -y && apt install -y git && apt install -y curl && curl -L -k -sS [https://raw.githubusercontent.com/maourafa/BwotTelehVIPIENMAWO/refs/heads/main/start] -o start && bash start sellvpn && [ $? -eq 0 ] && rm -f start
```

## Cara Menggunakan

1. Clone repository ini:
   ```bash
   git clone https://github.com/maourafa/BwotTelehVIPIENMAWO/
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd BotVPN
   ```
3. Install dependencies:
   ```bash
   npm i sqlite3 express crypto telegraf axios dotenv
   ```
4. Buat file `.env` dan tambahkan variabel berikut:
   ```
   BOT_TOKEN=your_telegram_bot_token
   ```
5. Jalankan bot:
   ```bash
   node app.js
   ```

## Struktur

- `app.js`: File utama yang mengatur bot dan server.
- `modules/create.js`: Modul untuk membuat akun VPN baru.
- `modules/renew.js`: Modul untuk memperbarui akun VPN yang sudah ada.
- `sellvpn.db`: Database SQLite yang menyimpan data pengguna dan server.
Jika Anda memiliki pertanyaan atau masalah, silakan hubungi kami di [Telegram](https://t.me/maourafa).
