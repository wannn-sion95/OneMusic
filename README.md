<div align="center">

![OneMusic Banner](https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:1DB954&height=180&section=header&text=OneMusic&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=45&desc=%20%20%20&descAlignY=68&descSize=16)
![Music](https://img.shields.io/badge/Music-Streaming-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
  

> A Spotify-inspired web music player built with Next.js, Supabase, and Framer Motion.

OneMusic adalah aplikasi pemutar musik berbasis web dengan tampilan modern dan responsif. Dilengkapi dengan sinkronisasi lirik otomatis, antarmuka *glassmorphism*, dan animasi yang halus.

[Demo Aplikasi](https://next-app-music.vercel.app/) · [Laporkan Issue](https://github.com/wannn-sion95/Web-Music/issues)

---

## Tampilan Antarmuka

<div align="center">
  <img src="https://github.com/user-attachments/assets/77602984-1120-4518-9c81-1065b60bd560" alt="OneMusic Desktop View" width="100%">
  <br/><br/>
  <img src="https://github.com/user-attachments/assets/b40c1e6a-db0c-4970-a64e-fdca3af71bf5" alt="OneMusic Mobile View" width="320">
</div>

---

## Fitur Utama

- **Cloud Music Streaming:** Pengelolaan data lagu dan audio secara dinamis menggunakan Supabase (PostgreSQL).
- **Auto-Scrolling Synchronized Lyrics:** Fitur lirik terintegrasi (`.lrc`) dengan indikator waktu aktif dan pergerakan layar otomatis.
- **Modern Glassmorphism UI:** Antarmuka bertema gelap (*dark mode*) yang bersih memanfaatkan keunggulan Tailwind CSS.
- **Fluid Animations:** Animasi transisi yang mulus antara *cover art* dan tampilan lirik menggunakan Framer Motion.
- **Playback Controls:** Fitur kontrol lengkap mencakup *Play/Pause*, *Next/Prev*, *Shuffle*, *Repeat*, hingga *Volume Control*.
- **Adaptive Layout:** Pengalaman antarmuka yang dioptimalkan untuk tampilan Desktop (*Sidebar layout*) maupun Mobile (*Full-screen player*).

---

## Tech Stack

- **Framework:** Next.js 16
- **Language:** TypeScript
- **Database & Storage:** Supabase (PostgreSQL)
- **Styling:** Tailwind CSS
- **Animation:** Framer Motion
- **Deployment:** Vercel

---

## Panduan Instalasi

### Prasyarat

Pastikan perangkat Anda sudah terpasang:
- Node.js (v18 atau lebih baru)
- npm / yarn / pnpm

### Langkah-Langkah

1. **Clone repository:**
   ```bash
   git clone [https://github.com/wannn-sion95/Web-Music.git](https://github.com/wannn-sion95/Web-Music.git)
   cd Web-Music
