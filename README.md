# 🎮 GIMJAM 2026 – Project Preparation & Execution Guide

Dokumen ini berfungsi sebagai **panduan utama tim** selama mengikuti GIMJAM 2026.  
Seluruh anggota tim **WAJIB membaca dan mematuhi isi README ini**.

---

## 📌 Hal Penting dari Guidebook (Yang Harus Dipatuhi Sekarang)

**Registrasi:**  
7 Jan – 21 Jan 2026. Daftar sekarang kalau belum.

**Durasi Jam:**  
Jam berlangsung 22 Jan – 29 Jan 2026  
(Opening night 22 Jan; pengumpulan di itch.io setelah jam dimulai).

**Output yang Dikumpulkan:**  
- .exe / .apk / WebGL  
- Video highlight  
- Halaman itch.io dengan credits  

Semua aset non-kreasi sendiri **WAJIB** dicantumkan creditnya.

**Aturan Umum:**  
- Engine bebas  
- Karya harus orisinal dan dibuat selama jam  
- **AI-Generated Art DILARANG**  
- Catat dan patuhi seluruh aturan

**Fokus Penilaian:**  
- Game Design (Innovation, Synergy, Execution)  
- Visual  
- Writing  
- Audio  

Fokus utama ada pada **execution (implementasi)**.

---

## 🚀 Prioritas Langsung (Hari Ini — Sebelum Opening)

1. Daftar & buat tim di situs penyelenggara kalau belum.  
   Deadline: 21 Jan 2026.

2. Buat Discord + channel tim dan pastikan semua bergabung.

3. Buat repo Git (GitHub/GitLab) dan branch utama;  
   semua anggota harus paham cara commit & pull.

4. Putuskan engine & build target (Unity / Godot / Construct).  
   Siapkan template project dengan build settings untuk WebGL  
   (paling aman untuk itch.io).

5. Siapkan folder Aset Placeholder:  
   placeholder art, placeholder SFX, placeholder music  
   agar programmer bisa implementasi lebih dulu.

6. Pilih 1–2 prototype templates (small core loop)  
   yang bisa diadaptasi ke tema apa pun.

7. Tetapkan pemimpin tim (PM) & lead untuk:  
   Programming, Art, Audio, dan QA.

---

## 📚 Apa yang Harus Dipelajari (Fundamentals)

Fokus belajar **intensif**, bukan teori panjang.  
Latihan 1–3 jam tiap item untuk anggota relevan.

---

### 👨‍💻 Untuk Programmer

- Versi kontrol Git  
  (clone, branch, merge, pull request) — **wajib**

- Basic engine workflow  
  - Unity + C# crash course  
    (scene, prefab, input, build WebGL)  
  - Atau Godot + GDScript  
    (lebih ringan, mudah export Web)

- Core gameplay scripting  
  input → game loop → states → collisions → simple UI

- Optimasi & build  
  how to make small WebGL build, remove unused assets

---

### 🧠 Untuk Designer (Game Design + Writer)

- Core loop & feedback  
  (player goal, action, reward)

- Level / flow design  
  scope minimal — 1 level atau endless with variation

- Narrative basics  
  3–4 lines of story atau contextual hooks  
  untuk peluang score “Best Story”

---

### 🎨 Untuk Artist

- Quick asset pipelines  
  2D sprites (PNG), sprite sheets, UI mockups  
  Tools: Aseprite / Photoshop / Krita

- Consistency & clarity  
  (penilaian Visual sangat menilai hal ini)

---

### 🎵 Untuk Audio

- Basic SFX creation  
  (Bfxr; minimal) + loopable BGM  
  (LMMS, GarageBand)

- Integrasi audio ke engine  
  (trigger, mixer)

---

### 👥 Untuk Semua Anggota

- Playtesting / bug reporting workflow

- Itch.io upload & credits process  
  (page + screenshots + video)  
  Guidebook menuntut credits yang jelas

---

## 🛠️ Pilih Engine — Rekomendasi Singkat

- **Unity (C#)**  
  Kuat untuk WebGL / Windows / Android  
  Banyak tutorial  
  Pilih jika ada 1–2 orang paham C#

- **Godot**  
  Lebih ringan  
  Cepat untuk prototype  
  Mudah export WebGL  
  Cocok untuk tim pemula

- **Construct / GDevelop**  
  No-code / visual  
  Cepat untuk non-programmer  
  Namun memiliki batasan tertentu

Pilih **SATU** engine dan **commit**.  
Jangan gonta-ganti engine saat jam berlangsung.

---

## 🎮 Ide Game Kecil yang Realistis untuk Jam

Kunci utama: **sederhana + deep polish**  
Jangan membuat game 3D open world.

1. Single-screen arcade (avoid / collect / rhythm)  
   Cepat, replayable, cocok untuk gameplay polish  
   → potensi skor tinggi

2. Puzzle (match / physics puzzle)  
   Tujuan jelas  
   Level kecil dengan banyak variasi  
   Mudah dikombinasikan dengan narasi ringan

3. Minimal platformer (1 level demo)  
   Realistis jika ada artist yang paham

4. Top-down shooter (arena, few enemy types)  
   Membutuhkan balancing & enemy AI  
   Risiko lebih tinggi

5. Narrative walking sim (short)  
   Cocok untuk fokus Best Story  
   Programming ringan, writing & art dominan

6. Endless runner  
   Mudah level generation  
   Mobile-friendly

Pilih archetype yang **memaksimalkan kekuatan tim**.  
Kombinasi puzzle + estetika kuat = peluang  
Best Visual + Best Gameplay.

---

## 🗓️ Rencana Sprint Harian

**Durasi Jam:** 22 Jan – 29 Jan 2026

- **22 Jan (Opening Day)**  
  Terima tema & wildcards  
  Tentukan scope final (MUST / HAVE / NICE)  
  Buat storyboard 1 halaman  
  Assign tasks  
  Mulai project template

- **23 Jan (Day 1)**  
  Implement core loop minimal (playable)  
  Placeholder art & audio  
  Fokus mekanik utama

- **24 Jan (Day 2)**  
  Expand mechanics  
  Basic UI  
  First playable level  
  Integrasi art pertama

- **25 Jan (Day 3)**  
  Polishing mechanics  
  Tambah SFX & BGM basic  
  Iterasi gameplay  
  Mulai record gameplay untuk highlight video

- **26 Jan (Day 4)**  
  Extra features (menu, settings)  
  Tambah level / variasi  
  Mulai polishing  
  QA menemukan & mencatat bug

- **27 Jan (Day 5)**  
  Polish visual clarity  
  Improve audio  
  Optimasi build size  
  Internal playtest & balancing

- **28 Jan (Day 6)**  
  Final bugfixing  
  Performance check  
  Final visual & credits  
  Render highlight video (1–2 menit)

- **29 Jan (Final Day)**  
  Build .exe / .apk / WebGL  
  Upload ke itch.io  
  Lengkapi page + screenshots + credits + video  
  Submit

**Catatan:**  
Sisihkan 1 hari penuh sebelum deadline  
untuk upload, dokumentasi, dan trailer.

---

## 👥 Pembagian Tugas (7 Orang)

1. **Team Lead / Producer**  
   - Pendaftaran  
   - Komunikasi dengan panitia  
   - Jadwal  
   - Itch.io upload  
   - Credits  
   - Daily standup  
   **Deliverable:** submission & dokumentasi

2. **Lead Programmer**  
   - Setup project  
   - Build pipeline  
   - Main gameplay loop  
   - Export build  
   **Deliverable:** stable build, WebGL tested

3. **Gameplay Programmer**  
   - AI / enemy  
   - Level logic  
   - UI interactions  
   - Bug fixing

4. **Lead Artist / Animator**  
   - Visual style guide  
   - Character / tiles / sprites  
   - Animations  
   - UI assets  
   **Deliverable:** final art sheet & sprites

5. **UI / VFX Artist**  
   - HUD  
   - Menu  
   - Particle effects  
   - Icons  
   - Screenshots untuk itch.io

6. **Sound Designer / Composer**  
   - BGM loops  
   - SFX library  
   - Audio integration  
   **Deliverable:** mastered audio & in-game audio

7. **Game Designer / Writer / QA / Marketing**  
   - Mini design doc  
   - Level design  
   - Writing / narrative  
   - Playtesting  
   - Highlight video  
   - Social media promo  
   **Deliverable:** design doc, video, promo

Distribusi bisa disesuaikan jika ada anggota kuat di satu bidang  
atau jika perlu QA full-time di akhir sprint.

---

## ✅ Checklist Teknis Sebelum Jam

- [ ] Akun & tim terdaftar di situs penyelenggara
- [ ] Git repo + branch convention + contribution rules
- [ ] Engine template project (WebGL tested)
- [ ] Placeholder assets (art & audio)
- [ ] Google Sheet / Trello / Notion untuk backlog & bug list
- [ ] Screen recording tool & simple video editor
- [ ] Itch.io account + page outline + credits template

---

## 🎯 Tips Strategis (Blak-blakan)

- Jangan membuat 2 fitur besar sekaligus  
  Pilih 1 mekanik unik dan poles sampai maksimal  
  Execution > fitur

- Karena AI art dilarang, jangan tergoda generate art  
  Gunakan handmade atau aset berlisensi  
  Selalu cantumkan credit

- Fokus pada clarity  
  Pemain harus paham kontrol & tujuan dalam 10 detik

- Metric sukses internal:  
  **“core loop playable + 3 minutes fun”**  
  Jika membosankan, buang fitur sampingan

- Siapkan plan B  
  Versi sangat kecil yang tetap bisa disubmit  
  (misalnya single-screen demo)

---

## 📚 Sumber Belajar Singkat

- Unity: Unity Learn “Create with Code”  
- Godot: Official “Your First Game” tutorial  
- Git: GitHub Quickstart + basic commands  
- Art: Aseprite sprite sheet tutorial / Kenney assets  
- Audio: Bfxr, LMMS, BandLab  
- Itch.io: HTML5/Web build upload & game page setup
