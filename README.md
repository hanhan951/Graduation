# Graduation
chatbot(multifungsi)

Features
AI Chat (LLM)
Menggunakan model Qwen2-1.5B-Instruct
Can answer with natural response
Support english and indonesian

There is a specific command to which y
Command:
$translate <language_code> <text>
Contoh:
$translate id Hello world
🌦️ Weather Information
Mengambil data cuaca dari API

Command:

$weather <city>

Output:

Suhu
Kondisi
Kelembapan
Kecepatan angin
🎲 Fun Commands
$coinflip → Lempar koin
$dice → Lempar dadu
$meme → Meme random
$dog → Gambar anjing random
$duck → Gambar bebek random
🧮 Math & Utility
$calc <operation> <a> <b>
$bmi <weight> <height>
$prime <number>
$factorial <number>
$gcd <a> <b>
$lcm <a> <b>
$floor <number>
$ceil <number>
📁 File Management
$simpan → Simpan file upload
$listfiles → Lihat daftar file
$showfile <filename> → Tampilkan file
$deletefile <filename> → Hapus file
♻️ Waste Sorting (Edukasi)
Mengklasifikasikan jenis sampah

Command:

$pilah <nama barang>
🔐 Password Generator
$pass <length>
🔁 Repeat Message
$repeat <jumlah> <pesan>
🎮 Game
TicTacToe multiplayer
⚙️ How It Works
1. AI System
build_ai_prompt() → Membentuk prompt natural
generate_ai_reply() → Generate response dari model AI
2. Event Handler
on_ready() → Bot aktif
on_message() → Handle semua pesan
3. Image Processing
predict_image() → Preprocessing + prediction
4. API Integration
Weather API → data cuaca
Translation API → terjemahan teks
🛠️ Installation
1. Clone Repository
git clone https://github.com/yourusername/your-repo.git
cd your-repo
2. Install Dependencies
pip install -r requirements.txt
3. Setup Token Discord

Tambahkan token bot di file:

bot.run("YOUR_DISCORD_TOKEN")
📦 Dependencies
discord.py
transformers
torch
tensorflow
numpy
pillow
requests
⚠️ Notes
Model AI cukup besar → butuh RAM/GPU
Koneksi internet diperlukan untuk:
Weather API
Translation API
Pastikan file berikut tersedia:
keras_model2.h5
labels2.txt
🚀 Future Improvements
Voice command
Music player enhancement
Dashboard web
Database integration
