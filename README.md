<div align="center">

# ⚡ AetherOps

**The Modern Cloud & Container Desktop Control Plane**

A minimalist, high-performance developer command center to orchestrate full-stack deployments, manage container workflows, automate environment cross-wiring, and stream live build telemetry.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Stack](https://img.shields.io/badge/Stack-React%2019%20%7C%20Electron%20%7C%20Node%20%7C%20MongoDB-cyan)](https://github.com/mausam-005/AetherOps)

</div>

---

## 🚀 Key Highlights

- **Desktop-First Orchestration**: Manage multi-service topologies (Frontend, Backend, Database) seamlessly from a single native dashboard.
- **Dynamic Environment Cross-Wiring**: Automatically resolve inter-service dependencies (e.g., inject dynamically assigned backend URLs directly into frontend build environments).
- **Live ANSI Build Streaming**: Stream real-time stdout/stderr compilation and container logs with interactive search, auto-scroll, and abort controls.
- **Automated Rollback & Audit Trail**: Chronological deployment history with instant one-click rollbacks powered by cloud telemetry.

---

## 🛠️ Architecture & Tech Stack

- **Frontend (Web Dashboard)**: React 19, TypeScript, Tailwind CSS, Framer Motion, Lucide React *(Target: Vercel)*
- **Desktop Shell**: Electron (Secure context isolation & IPC bridge)
- **Backend API**: Node.js, Express, TypeScript, WebSockets *(Target: Render)*
- **Database**: MongoDB Atlas via Mongoose ORM

---

## 📦 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or pnpm
- MongoDB Atlas connection URI

### Installation
```bash
# Clone the repository
git clone https://github.com/mausam-005/AetherOps.git

# Navigate to project directory
cd AetherOps

# Install dependencies
npm install
```

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
