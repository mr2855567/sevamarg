# 🏛️ SevaMarg (சேவை மார்க்)

> **Never Waste a Trip to a Government Office Again.**  
> *அரசு அலுவலகங்களுக்கு வீண் அலைச்சல் இனி வேண்டாம்.*

[![Deploy to GitHub Pages](https://github.com/mr2855567/sevamarg/actions/workflows/deploy.yml/badge.svg)](https://github.com/mr2855567/sevamarg/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen)](https://mr2855567.github.io/sevamarg/)

**SevaMarg** is a voice-first, bilingual (Tamil & English) civic checklist and ground-reality navigator for essential Tamil Nadu Government certificates. Built as a 100% client-side, zero-PII Progressive Web Application (PWA).

---

## 🌟 Key Features

- **6 Core Tamil Nadu Service Blueprints**:
  - Community Certificate (ஜாதி சான்றிதழ்)
  - Income Certificate (வருமானச் சான்றிதழ்)
  - Nativity / Residence Certificate (இருப்பிடச் சான்றிதழ்)
  - First Graduate Certificate (முதல் பட்டதாரி சான்றிதழ்)
  - Legal Heir Certificate (வாரிசு சான்றிதழ்)
  - Ration Card Member Addition (குடும்ப அட்டை பெயர் சேர்த்தல்)
- **Lakshmi Ground-Reality Safeguards**: Unwritten requirements frequently demanded by field officers (extra self-attested copies, father's TC, unexpired rental agreements, stamp affidavits, blue pens/glue).
- **Voice-First Audio Guidance**: Fluent natural Tamil audio narration via Google TTS stream with browser SpeechSynthesis fallback.
- **Bilingual & Accessible**: Full English & Tamil (`I18N`) toggle with 100% parity across all workflows.
- **Adaptive Questionnaire Engine**: Customizes document checklists according to applicant role (Self, Child, Scholarship) and channel (Taluk Office, e-Sevai / CSC, Online Portal).
- **CSC / e-Sevai Operator Mode**: Dedicated kiosk interface with customer slip print generator for cyber cafes and common service centers.
- **TNeGA Portal Simulator**: Interactive walkthrough explaining CAN registration and tricky online form fields.
- **Offline PWA Support**: Service Worker (`sw.js`) offline caching with zero-PII persistence in `localStorage`.
- **System Diagnostics Modal**: In-app test suite running 8 real-time verification checks on audio streams, schemas, dictionary parity, and print formatting.

---

## 🚀 Live Demo

Access the live application hosted on GitHub Pages:  
👉 **[https://mr2855567.github.io/sevamarg/](https://mr2855567.github.io/sevamarg/)**

---

## 💻 Tech Stack

- **Frontend**: Vanilla HTML5, Modern CSS3 (Glassmorphism, CSS Custom Properties, Responsive Grid & Flexbox), Vanilla JavaScript (ES6+)
- **Typography**: Google Fonts (*Noto Sans Tamil*, *Plus Jakarta Sans*)
- **PWA**: Web App Manifest & Service Worker Cache Engine
- **Hosting**: GitHub Pages via GitHub Actions

---

## 🛠️ Local Development

To run SevaMarg locally on your machine:

```bash
# Clone the repository
git clone https://github.com/mr2855567/sevamarg.git
cd sevamarg

# Start any static HTTP server (e.g., using Node.js)
npx -y serve .
```

Open your browser at `http://localhost:3000`.

---

## 📄 License

This project is licensed under the MIT License.
