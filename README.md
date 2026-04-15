# 🪸 AQUA TRACE: AI-Powered Reef Monitoring & Conservation

> **"Protecting the 80% of the Unwatched Ocean."**

**AQUA TRACE** is a centralized, AI-driven platform designed to automate coral reef monitoring, predict bleaching events, and gamify conservation for divers and local communities. By combining **YOLOv8 Segmentation**, **Real-time SST Data**, **WhatsApp Integration**, and **Augmented Reality**, we turn every diver into a marine scientist and every image into actionable data.

---

## 🌍 The Problem

* **Massive Blind Spots:** 80% of global coral reefs remain unmonitored due to resource constraints.
* **Reactive vs. Proactive:** Current efforts react to bleaching *after* it happens. There is a lack of predictive capabilities.
* **Manual Bottlenecks:** Traditional surveys are labor-intensive, subjective, and slow.

## 🚀 Our Solution

AQUA TRACE automates the pipeline from data collection to insight:

1. **AI Vision:** Custom YOLOv8 models detect and segment coral species, calculating precise bleaching percentages.
2. **Predictive Analytics:** We correlate visual data with Sea Surface Temperature (SST) APIs to forecast bleaching events up to 60 days in advance.
3. **Accessible Tech:** A WhatsApp-first approach allows anyone to upload data without installing complex apps.

---

## ✨ Key Features

### 1. 🤖 AI-Powered Analysis Agent
* **Core:** A multi-agent system (built with CrewAI) that acts as a "Visual Analyst" and "Oceanographer."
* **Tech:** YOLOv8-Nano-Seg (Segmentation) for identifying coral species and calculating specific bleached surface area (%).
* **Output:** Structured reports on coral health, disease identification, and bleaching severity.

### 2. 📱 WhatsApp Bot Integration
* **Zero Friction:** Users send images directly to a WhatsApp bot.
* **Instant Feedback:** The bot replies instantly with the AI analysis ("⚠️ Severe Bleaching Detected") and awards points.
* **Location Awareness:** Captures geolocation tags to map reef health automatically.

### 3. 👓 Web AR Scanner (Real-Time)
* **Live Analysis:** A browser-based AR tool (TensorFlow.js / ONNX) that overlays health data on live camera feeds.
* **Usage:** Divers or snorkelers can point their phone at a coral to see real-time classification (Healthy vs. Bleached) and confidence scores.

### 4. 📊 The Dashboard & Leaderboard
* **Command Center:** An interactive map showing global reef health, pinned locations, and 10-day SST predictions.
* **Gamification:** A "Reef Guardian" leaderboard that rewards users with badges, NGO certificates, and sponsor coupons for high-quality data contributions.

---

## 🛠️ Technology Stack

* **Frontend:** React, Tailwind CSS, Framer Motion (Deep Ocean Aesthetic).
* **AI/ML:** Python, Ultralytics YOLOv8 (Segmentation), TensorFlow.js / ONNX Runtime (Web).
* **Agents:** CrewAI (Orchestration of Research, Vision, and Reporting agents).
* **Backend & Database:** Supabase (PostgreSQL), Python (Flask/FastAPI) for the WhatsApp webhook.
* **Integrations:** Twilio API (WhatsApp), RapidAPI (SST & Weather Data).

---

## 👥 Team & Contributions

**Suryansh Shah**
* **Core Ideation:** Conceptualized the entire project architecture, including the WhatsApp bot and all primary features.
* **AI Model & Research:** Developed the coral classification model and contributed to the foundational research paper.
* **Dashboard Visualization:** Designed and built the complete interactive dashboard and visualization pipeline.
* **AR Integration:** Spearheaded the ideation and technical integration of the real-time Web AR scanner.

**Team Members:** Aksh Modi, Sahil Kumar Singh, Agrim Gairola

---

## 🔮 Future Scope

* **Swarm Intelligence:** Deploying AUVs (Autonomous Underwater Vehicles) that communicate to map vast reef areas.
* **Satellite Fusion:** Integrating macro-level satellite imagery to correlate local findings with global trends.
* **3D Digital Twins:** Creating photogrammetric 3D models of reefs for immersive VR monitoring.

---

## 🤝 Contributing

We welcome marine biologists, data scientists, and developers!

1. Fork the repo.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

> **Built with 💙 for the Ocean.**
> 
