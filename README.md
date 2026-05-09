<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6c5ce7,50:a29bfe,100:00cec9&height=200&section=header&text=Muhammad%20Umer%20Qureshi&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Computer%20Systems%20Engineer%20·%20Full-Stack%20Developer%20·%20Security%20Researcher&descAlignY=56&descAlign=50&descSize=14" width="100%" />

<br/>

<a href="https://github.com/umerqureshi409"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/umer-qureshi-526118259/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="mailto:umerq7743@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
&nbsp;
<a href="https://umerqureshi.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-6c5ce7?style=flat-square&logo=vercel&logoColor=white"/></a>
&nbsp;
<a href="https://gitlab.com/umerqureshi409"><img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white"/></a>
&nbsp;
<a href="https://www.youtube.com/@code-withumer"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white"/></a>

<br/><br/>

<img src="https://img.shields.io/badge/CGPA-3.70%2F4.00-6c5ce7?style=flat-square"/>
&nbsp;
<img src="https://img.shields.io/badge/Infra%20Cost-%240%2Fmonth-00cec9?style=flat-square"/>
&nbsp;
<img src="https://img.shields.io/badge/Role-Official%20Web%20Dev%20%40%20MUET-6c5ce7?style=flat-square"/>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=umerqureshi409&style=flat-square&color=6c5ce7&label=views"/>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=800&color=6C5CE7&center=true&vCenter=true&random=false&width=700&height=50&lines=Official+Web+Dev+%40+Mehran+UET+as+a+2nd-year+undergrad;Building+cs.muet.edu.pk+%2B+iict.muet.edu.pk+at+%240%2Fmonth;Co-Founder+%40+Voidium+%E2%80%94+6-member+dev+startup;Roadmap%3A+Security%2B+%E2%86%92+eJPT+%E2%86%92+OSCP;Code%2C+Debug%2C+Innovate%2C+Repeat." />

</div>

---

## `$ whoami`

```json
{
  "name":       "Muhammad Umer Qureshi",
  "university": "Mehran UET, Jamshoro — CSE, Semester 4 (CGPA: 3.70/4.00)",
  "roles":      ["Official Web Dev @ CS Dept", "Official Web Dev @ IICT", "Co-Founder @ Voidium"],
  "live_sites": ["https://cs.muet.edu.pk", "https://iict.muet.edu.pk"],
  "infra_cost": "$0/month (Neon + Vercel free tier)",
  "target":     "CompTIA Security+ → eJPT → OSCP",
  "location":   "Jamshoro, Sindh, Pakistan",
  "quote":      "Security isn't a feature — it's the foundation."
}
```

> Only undergraduate in the department formally commissioned to build **two live production university websites simultaneously** — both running at **$0/month** and surviving real exam-day traffic spikes.

---

## ⚡ At a Glance

| | |
|---|---|
| 🎓 **Education** | B.E. Computer Systems Engineering · Mehran UET · CGPA **3.70 / 4.00** |
| 🌐 **Production** | [`cs.muet.edu.pk`](https://cs.muet.edu.pk) + [`iict.muet.edu.pk`](https://iict.muet.edu.pk) — both at $0/month |
| 🏢 **Startup** | Co-Founder & Lead Dev @ **Voidium** — 6-member student-led tech startup |
| 🔐 **Security** | Active self-study: Linux · OWASP · Burp Suite → Security+ → eJPT → OSCP |
| 🔬 **Research** | Adaptive Bloom Trie — phishing URL detection at edge scale (Java, ongoing) |
| 📋 **Accreditation** | KernelViz + CS MUET Website — CEP submissions satisfying all 9 MUET characteristics |

---

## 💼 Experience

### 🌐 Official Web Developer — CS Department, Mehran UET
**`Dec 2025 – Present`** · [cs.muet.edu.pk](https://cs.muet.edu.pk)

Commissioned after a security compromise to rebuild the entire department website from scratch. The system serves **6 stakeholder groups** (students, faculty, alumni, industry, accreditation bodies) daily.

- **Schema:** 25-table Neon PostgreSQL across 6 modules — FYP batches (19–25BSCS), announcements, timetables, events, gallery, industry linkages; strategic JSONB denormalization for read-hot tables; strict 3NF for all transactional/security tables; soft-delete preserves full audit history
- **Security:** `bcrypt` · `JWT sessions` · `reCAPTCHA v2` · `CSP headers` · IP brute-force lockout (15-min) · full audit log on every admin mutation · SQL injection architecturally impossible via Drizzle ORM
- **Performance:** Next.js 15 App Router + Vercel edge CDN + Neon free tier → **<2s page loads, 99%+ uptime** through exam-day spikes at **$0/month**
- **Scale:** 12 admin API modules · scoped announcement routing · atomic delete+audit transactions

`Next.js 15` `TypeScript` `Drizzle ORM` `Neon PostgreSQL` `Vercel` `Tailwind CSS` `JWT` `bcrypt`

---

### 🏛️ Official Web Developer — IICT Institute, Mehran UET
**`Jan 2026 – Present`** · [iict.muet.edu.pk](https://iict.muet.edu.pk)

Sole developer of the official portal for **6+ IICT departments**.

- Full-stack CMS: faculty profiles, research groups, publications, events, institutional announcements
- Full **WCAG 2.1** color compliance overhaul; custom CSS/JS navbar with mobile slide-in drawer, programs accordion
- Resolved ModSecurity-blocked imports, rogue `.htaccess` 500 errors, hardcoded path bugs; DNS migration via A/CNAME

`PHP` `MySQL` `cPanel` `Custom CSS/JS` `WCAG 2.1`

---

### 🚀 Co-Founder & Lead Developer — Voidium
**`Jan 2025 – Present`**

Student-led tech startup delivering freelance web, AI, and IoT solutions. Leading a **6-member team** building open-source and commercial SaaS products across web, mobile, and embedded domains.

---

## 🛠️ Tech Stack

<details open>
<summary><b>Languages</b></summary>

`Python` `TypeScript` `JavaScript` `Java` `C` `C++` `SQL` `PHP`

</details>

<details open>
<summary><b>Frontend & Backend</b></summary>

`Next.js 15` `React` `Tailwind CSS` `Framer Motion` `Node.js` `Express.js` `Flask` `Spring Boot` `WebSocket` `REST API`

</details>

<details open>
<summary><b>Databases & ORMs</b></summary>

`PostgreSQL` `Neon (serverless)` `MongoDB` `MySQL` `Firebase` `Redis` `Drizzle ORM`

</details>

<details>
<summary><b>DevOps & Cloud</b></summary>

`Docker` `Vercel` `AWS` `DigitalOcean` `Terraform` `GitHub Actions` `Nginx` `cPanel` `Linux`

</details>

<details>
<summary><b>Security</b></summary>

`JWT` `bcrypt` `CSP Headers` `reCAPTCHA v2` `OWASP` `Burp Suite` `WebRTC/ICE` `Parameterized SQL`

</details>

<details>
<summary><b>IoT & Hardware</b></summary>

`ESP32` `ESP32-CAM` `Arduino` `AD8232 (ECG)` `MAX30105 (SpO2)` `DS18B20` `I2C/SPI` `SPIFFS/SD`

</details>

<details>
<summary><b>Systems & AI</b></summary>

`Linux /proc programming` `C shared libs (GCC/ctypes)` `OpenCV` `face_recognition` `TensorFlow` `PyTorch`

</details>

---

## 🚀 Projects

### `KernelViz OS` — Operating System Simulator · [Source](https://github.com/umerqureshi409)
`C (gcc shared lib)` · `Python` · `WebSocket` · `HTML/CSS/JS Canvas` · `psutil` · `ctypes FFI`

CEP submission for CS-261 OS, satisfying all 9 MUET accreditation characteristics.

- **C core (`libkernelviz.so`):** Round Robin & Priority schedulers, First-Fit allocator with block coalescing, inode-based VFS, pipes, message queues, DFS-based deadlock detection
- **Python bridge** merges simulation with live `/proc/sys` data via `psutil`; WebSocket at 1 Hz
- **10-tab browser dashboard:** Gantt chart, memory map, process Kill table, Real Stats — pure DOM/Canvas, zero frameworks
- **Dual-mode:** LIVE+SIM on Linux; REAL-ONLY (psutil) on Windows/Mac

---

### `Nexus Ecosystem v2` — Offline LAN Platform · [Source](https://github.com/umerqureshi409)
`Node.js` · `Express` · `WebSocket` · `WebRTC` · `Embedded TURN` · `PWA`

- Zero-internet LAN ecosystem: file transfer (up to **2 GB**), screen sharing, voice calls, clipboard sync, messaging
- **Embedded TURN relay (RFC 5766)** resolves mDNS ICE failures on plain HTTP
- UDP LAN discovery on port 7524; 6-digit PIN pairing; QR mobile onboarding; auto-TLS; PWA offline install; 48-hour auto-cleanup

---

### `MediTrack` — IoT Real-Time Health Monitor · [Source](https://github.com/umerqureshi409/MediTrack)
`ESP32` · `C++` · `AD8232 ECG` · `MAX30105 SpO2` · `DS18B20` · `WebSocket` · `Chart.js`

- ESP32 tracking ECG waveform + cardiac rhythm, heart rate (dual-source), SpO2, body temp, humidity
- Responsive WiFi dashboard, intelligent alerts, SPIFFS/SD historical logging, visual + audio notifications

---

### `Adaptive Bloom Trie` — Security Research · [Source](https://github.com/umerqureshi409/Adaptive-Bloom-Trie)
`Java` · *Ongoing*

- Novel phishing URL detector: Bloom filter pre-screening + compressed Trie → sub-millisecond lookups
- Optimized for resource-constrained and embedded environments; targets large evolving phishing datasets

---

### `Chatrix (U-Chat)` — Full-Stack Comms · [Source](https://github.com/umerqureshi409)
`Next.js` · `Firebase` · `Agora SDK` · `TypeScript` · `Google OAuth`

- Real-time text + voice/video calls (Agora), AI voice diary, push notifications, Google sign-in, Firestore sync

---

### `Face Detection Attendance System` · [Source](https://github.com/umerqureshi409/CPP-Face-Detection-Attendance-System)
`Python` · `OpenCV` · `face_recognition` · `Flask` · `ESP32-CAM`

- Haar Cascade detection + face encoding comparison; CSV timestamped logging; Flask portal; ESP32-CAM IoT variant

---

## 🏆 Achievements

- **Youngest commissioned dev @ MUET** — Only 2nd-year undergrad formally tasked with two simultaneous live production university systems
- **Zero-cost production** — Both `cs.muet.edu.pk` + `iict.muet.edu.pk` at **$0/month** sustaining real exam-day traffic
- **CEP accreditation** — KernelViz (CS-261) + CS MUET Website (CS-253) satisfy all 9 complex engineering problem characteristics
- **Security roadmap** — Active: Linux hardening, Burp Suite, Python security tooling → Security+ → eJPT → OSCP
- **All projects open-sourced** at [github.com/umerqureshi409](https://github.com/umerqureshi409)

---

## 🔐 Cybersecurity Roadmap

```
[ NOW  ]  Linux Hardening ──► OWASP Top 10 ──► Burp Suite / Python Tooling
[ NEXT ]  CompTIA Security+
[ THEN ]  eJPT  (eLearnSecurity Junior Penetration Tester)
[ GOAL ]  OSCP  (Offensive Security Certified Professional)
```

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=umerqureshi409&theme=tokyonight" width="100%" />

<img src="https://github-readme-stats.vercel.app/api?username=umerqureshi409&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0D1117&title_color=6c5ce7&icon_color=00cec9" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com?user=umerqureshi409&theme=tokyonight&hide_border=true&background=0D1117&ring=6c5ce7&fire=fd79a8&currStreakLabel=6c5ce7" width="49%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=umerqureshi409&theme=tokyonight" width="31%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=umerqureshi409&theme=tokyonight" width="31%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=umerqureshi409&theme=tokyonight" width="31%" />

</div>

---

## 📬 Contact

<div align="center">

| | |
|---|---|
| 💼 LinkedIn | [umer-qureshi-526118259](https://www.linkedin.com/in/umer-qureshi-526118259/) |
| 📧 Email | [umerq7743@gmail.com](mailto:umerq7743@gmail.com) |
| 🌐 Portfolio | [umerqureshi.vercel.app](https://umerqureshi.vercel.app/) |
| 🐙 GitHub | [github.com/umerqureshi409](https://github.com/umerqureshi409) |
| 🦊 GitLab | [gitlab.com/umerqureshi409](https://gitlab.com/umerqureshi409) |
| 📺 YouTube | [@code-withumer](https://www.youtube.com/@code-withumer) |
| 📸 Instagram | [@umerqureshi409](https://www.instagram.com/umerqureshi409/) |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00cec9,50:6c5ce7,100:fd79a8&height=120&section=footer" width="100%" />

**`Security isn't a feature — it's the foundation.`**

*Ship real things. Learn deeply. Build for the long term.*

</div>
