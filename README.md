# The Eye: TechTitans Military Intelligence Dash

**The Eye** is a high-fidelity, military-focused evolution of the WorldMonitor platform. It is engineered for rapid situational awareness, strategic analysis, and real-time geopolitical monitoring.

---

## 👁️ Core Mission
To provide a unified, distraction-free intelligence picture for defense analysts, utilizing AI-powered synthesis and curated tactical data layers.

## 🛰️ Tactical Map Layers
The dashboard is strictly filtered to only show high-impact strategic layers:
- **Iran Attacks & Conflict Zones**: Real-time kinetic activity tracking.
- **Intel Hotspots**: Georegistered OSINT findings.
- **Military Bases & Nuclear Sites**: Global strategic infrastructure.
- **Military Activity**: Real-time flight (ADS-B) and naval (AIS) monitoring.
- **Strategic Waters & Trade Routes**: Chokepoint and maritime flow analysis.
- **GPS Jamming**: Global GNSS interference mapping.
- **Day/Night Overlay**: Real-time solar terminator tracking.

## 📰 Intelligence Feed
The "Live News" subsystem is optimized for high-authority, low-noise reporting from:
- **Sky News** (Global Breaking)
- **Euronews** (European/Geopolitical)
- **CNBC** (Macro-Economic & Industrial)

## 🤖 AI-Powered Analysis
- **Unified News Engine**: Proprietary subsystem fetching data from 100+ sources including Reuters, AP, Janes, and Defense One.
- **Intelligence Findings**: Automated headline analysis and threat ranking.
- **What-If Geopolitical Simulator**: Run strategic scenarios (e.g., "Middle East Escalation") to receive AI-generated impact briefs via **Groq**.
- **Ask the Dashboard**: Natural language query interface for the entire dataset.

---

## 🛠️ Technical Stack
- **Frontend**: TypeScript, Vite, Vanilla CSS.
- **Mapping Engine**: Deck.gl & MapLibre for high-performance WebGL rendering.
- **Intelligence Architecture**: Custom RSS intake, Groq LLM integration.

## 🚀 Getting Started

### 1. Requirements
- Node.js (v18+)
- A **Groq API Key** (Set in `.env`)

### 2. Installation
```powershell
# Clone the repository
git clone https://github.com/vignesh-poovanna/The-Eye-TechTitans.git
cd worldmonitor

# Install dependencies
npm install

# Configure environment
# Add your GROQ_API_KEY to the .env file
```

### 3. Usage
```powershell
npm run dev
```

---

## 📄 License
This project is for use by the TechTitans team for the AI Arena competition. All rights reserved.
