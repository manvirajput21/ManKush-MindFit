# ManKush-MindFit
# MindFit × MindFit AI

A cutting-edge, self-contained single-file personal wellness command center powered by **MindFit AI**—a behavioral pattern recognition and adaptive recommendation engine. Designed to help users track everyday wellness signals, understand lagged relationships in their health data, and discover personalized recovery actions.

## ✨ Core Features

* **MindFit AI Health Companion:** A natural language processing (NLP) chat interface that parses conversational check-ins into quantitative signals (`mood`, `stress`, `energy`, `sleep`) without tedious form fatigue.
* **Temporal Pattern Detection ($t \rightarrow t+1$):** Analyzes multi-day rolling windows and lagged relationships to surface hidden patterns (e.g., how sleep deficits cascade into next-day stress spikes or headaches).
* **Adaptive Recommendation Engine:** Recommends targeted activities and active recovery hobbies (such as chess, frontend prototyping, or nature walks) weighted dynamically against your real-time state and historical efficacy.
* **Closed-Loop Learning Matrix:** Tracks your mood and stress deltas before and after completing activities to continuously recalibrate personal recommendation weights.
* **Holistic Modular Trackers:** Includes mood/sleep/stress logging, interactive pattern charts (Chart.js), a menstrual health tracking module, a private client-side journal, and a 5-minute 4–2–6 breathing reset timer.

## 🛠️ Technology Stack

* **Frontend:** Pure HTML5, CSS3 (Custom Properties, Grid, Flexbox, Glassmorphic UI)
* **Scripting:** Vanilla JavaScript (ES6+), LocalStorage state persistence
* **Visualizations:** Chart.js (Line charts, scatter plots for multivariate sleep/energy analysis)
* **Assets:** FontAwesome 6.5.2, Google Fonts (DM Sans, Space Grotesk)

## 🚀 Getting Started

Since MindFit is engineered as a zero-dependency, single-file application, running it requires no complex build tools or backend server setup.

1. Save the application code into an HTML file (e.g., `index.html`).
2. Open the file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Click **"Launch Hackathon Demo"** to instantly populate 30 days of realistic temporal data and explore the AI command center, or begin logging your own check-ins.

## 🔒 Privacy & Data Architecture

* **Strictly Client-Side:** All wellness records, journal entries, and AI weight configurations are stored securely within your browser's `localStorage`.
* **No External Telemetry:** No personal data is transmitted to external cloud APIs or remote servers.
* **Scientific Safety Principles:** MindFit surfaces observable behavioral correlations in self-reported data. It is designed purely for personal self-awareness and is not a diagnostic medical device.
