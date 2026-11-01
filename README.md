# SwasthLink 🏥 | Connecting Bharat to Healthcare 🇮🇳

<p align="center">
  <a href="https://harshverse-svg.github.io/Swast-.link-/"><img src="https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-4F5BD5?style=for-the-badge&logo=github" alt="Live Demo" /></a>
  <img src="https://img.shields.io/badge/Focus-Zero--App%20WhatsApp%20Booking-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Integration" />
  <img src="https://img.shields.io/badge/Coverage-28%2B%20States%20%7C%20100%2B%20Cities-0D9488?style=for-the-badge" alt="Pan-India Coverage" />
  <img src="https://img.shields.io/badge/Architecture-100%25%20Client--Side-10B981?style=for-the-badge" alt="Client Side" />
  <a href="https://github.com/harshverse-svg/Swast-.link-"><img src="https://img.shields.io/badge/License-MIT-gray?style=for-the-badge" alt="License" /></a>
</p>

<p align="center">
  <strong>"Stop waiting. Break the line."</strong><br>
  <em>A friction-free, zero-app-download healthcare gateway enabling patients across India to schedule doctor appointments and locate nearby pharmacies directly through WhatsApp.</em>
</p>

---

## 🌐 Live Web Portal

Access the portal directly from any smartphone or desktop:  
👉 **[https://harshverse-svg.github.io/Swast-.link-/](https://harshverse-svg.github.io/Swast-.link-/)**

---

## 💡 The Problem & The Solution

- **The Problem**: Traditional OPD hospital lines and complex medical booking apps require high smartphone storage, fast 5G data, multi-step registrations, and complex OTP verifications—disenfranchising tier-2, tier-3, and rural patients.
- **The Solution**: **SwasthLink** eliminates friction by meeting users where they already are: **WhatsApp**. With zero downloads, users choose their state and city to immediately connect with verified local healthcare booking coordinators and see essential neighborhood pharmacy details.

---

## 🌟 Key Capabilities

- 📲 **Instant WhatsApp Deep-Linking**: Dynamically builds pre-filled, localized WhatsApp intent URLs (`wa.me/91...`) containing the patient's state and city for one-tap booking.
- 🇮🇳 **Comprehensive Pan-India Directory**: Pre-mapped directory encompassing 28+ Indian States and Union Territories and over 100+ cities (from Tier-1 metros like Delhi, Mumbai, and Bengaluru to regional hubs like Gorakhpur, Siliguri, Guntur, and Jhansi).
- 💊 **Localized Pharmacy Finder**: Instantaneously presents verified local pharmacies (e.g., Apollo Pharmacy, MediCare, Wellness, HealthFirst) corresponding to the selected jurisdiction.
- ⚡ **Ultra-Lightweight & Resilient**: Weighs under 50 KB, executes completely client-side in vanilla JavaScript, and loads smoothly on low-bandwidth 2G/3G connections.
- 🔒 **Zero Telemetry & Private**: Does not collect, track, or persist sensitive patient medical history on external servers.

---

## 🔄 User Workflow

```
┌──────────────────┐       ┌──────────────────┐       ┌──────────────────┐
│  Select State &  │ ────► │ View Booking No. │ ────► │  One-Tap "Book   │
│   Target City    │       │  & Pharmacies    │       │  via WhatsApp"   │
└──────────────────┘       └──────────────────┘       └────────┬─────────┘
                                                               │
                                                               ▼
                                                      ┌──────────────────┐
                                                      │ WhatsApp Chat    │
                                                      │ Opens with Query │
                                                      └──────────────────┘
```

---

## 📂 Repository Structure

```text
Swast-.link-/
└── index.html         # Complete responsive portal, CSS styling, city mapping & WhatsApp bridge
```

---

## 🛠️ Quick Start & Local Run

No build tools or Node packages required.

### 1. Clone
```bash
git clone https://github.com/harshverse-svg/Swast-.link-.git
cd Swast-.link-
```

### 2. Launch
Double-click `index.html` in your file explorer, or serve via Python:

```bash
python -m http.server 8000
```
Open `http://localhost:8000` in your mobile or desktop browser.

---

## 📄 License

Distributed under the [MIT License](LICENSE).
