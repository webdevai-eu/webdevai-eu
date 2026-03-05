# 🚀 WebDevAI Ecosystem

Witaj w głównym repozytorium **WebDevAI** – autorskiego ekosystemu narzędzi SaaS budowanych w modelu Hybrid AI Architect. Nasza architektura opiera się na centralnym hubie zarządzania i dedykowanych aplikacjach specjalistycznych.

## 🌐 Adresy Ekosystemu
- **Strona Główna:** [webdevai.eu](https://webdevai.eu) – Portal marki i wizytówka.
- **Główny Portal:** [app.webdevai.eu](https://app.webdevai.eu) – Centralny Dashboard, zarządzanie kontem i subskrypcjami.
- **mAIstro:** [maistro.webdevai.eu](https://maistro.webdevai.eu) – Generator treści multi-modalnych (Tekst/Audio/Video).
- **Inne:** Kolejne narzędzia (Argus AI, Velo AI) będą wdrażane na dedykowanych subdomenach.

---

## 🎵 mAIstro - Projekt Priorytetowy (Sprint 32h)

mAIstro to narzędzie typu "Boxed AI", które pozwala na błyskawiczne tworzenie treści przy użyciu najpotężniejszych modeli Google Vertex AI.

### 🛠️ Stack Technologiczny
- **Frontend:** React (Aura Build) + Tailwind CSS (SPA Architecture)
- **Navigation:** Mobile-first Bottom Navigation 📱
- **Platform:** PWA (Progressive Web App)
- **Backend/DB:** Firebase (Portable configuration)
- **AI:** Gemini 2.0 via Vertex AI
- **Payments:** Stripe (Models: Free, Standard, Pro)

- ## 📂 Project Structure (Monorepo)
```text
webdevai-eu/
├── apps/                   # Subdomain Applications
│   ├── app-hub/            # app.webdevai.eu (Central Portal)
│   └── maistro/            # maistro.webdevai.eu (Priority AI Tool)
├── packages/               # Shared Resources
│   ├── aura-ui/            # Common UI Components
│   ├── config/             # Shared Lint/Prettier Rules
│   └── firebase/           # Portable Firebase Logic
└── README.md               # Main Roadmap

### 📈 Mapa Drogowa (MVP)
- [ ] **UI/UX:** Implementacja SPA Shell z Bottom Navigation.
- [ ] **Dashboard:** Magic Input Bar dla "One-click generation".
- [ ] **Auth:** Integracja z centralnym systemem WebDevAI.
- [ ] **Payments:** Logika subskrypcyjna i limity generacji.

---

## 📧 Kontakt & Współpraca
- **E-mail:** [office@webdevai.eu](mailto:office@webdevai.eu)
- **Autor:** WebDevAI
