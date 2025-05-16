# AbroadWork Malaysia

> 🇲🇾 A job portal designed to connect Malaysian employers with top talent from the Philippines, Indonesia, and other Southeast Asian countries — part of the AbroadWork global ecosystem.

---

## 🌏 Overview

AbroadWork Malaysia is a specialized platform focused on Malaysian labor market needs.  
It streamlines recruitment of domestic workers, caregivers, general laborers, and skilled professionals from Southeast Asia — with full support for document handling, interview scheduling, and AI-powered shortlisting.

Connected directly to the `abroadwork-core` backend, it ensures speed, compliance, and trust between Malaysian employers and verified workers.

---

## 🇲🇾 Key Features

- 🧹 Recruitment of housemaids, nannies, caregivers, helpers
- 🧑‍🔧 Hiring skilled workers from PH/ID (cooks, welders, drivers)
- 📋 Employer dashboard with shortlist + hiring status
- 📑 Auto-generated employment contract templates
- 📲 Twilio SMS/WhatsApp alerts to both parties
- 📅 Zoom integration for live screening interviews
- 🎥 Upload video resumes for candidate preview
- 📄 Work visa + permit checklist per nationality
- 🔐 Admin module to verify agency uploads/documents

---

## ⚙️ Tech Stack

- **Frontend:** Angular / React
- **Backend:** abroadwork-core (.NET API)
- **Database:** MongoDB (via abroadwork-core)
- **CDN/Media:** AWS S3 or Cloudinary
- **APIs:** Twilio, Zoom, OCR (passport scanner)

---

## 📁 Folder Structure
abroadwork-malaysia/
├── frontend/ # UI portal for employers + recruiters
├── public/ # Icons, language files (EN, MY, PH, ID)
├── docs/ # Contracts, visa steps, flowcharts
├── config/ # Core API endpoints
└── README.md

---

## 🔧 Setup Instructions

### 🔗 Prerequisites

- Node.js / Angular CLI
- Git & VS Code
- Connected to `abroadwork-core`

---

### ▶️ Run Locally

```bash
# Clone repo
git clone https://github.com/mahadgroup/abroadwork-malaysia.git

# Frontend setup
cd abroadwork-malaysia/frontend
npm install
ng serve
🧠 Smart Features Coming Soon
📷 Passport OCR scan + auto data entry

🔔 Candidate auto-reminder for missing documents

🧾 POEA/ID migration document templates

📊 Live dashboard of selected + hired workers

🧑‍💼 Maintained by
AbroadWork Malaysia Team
📍 Kuala Lumpur, Malaysia
🌐 www.abroadwork.my
📧 info@abroadwork.my 
