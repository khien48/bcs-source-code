# 🚌 BCS System - Multi-App Setup

This repository provides links and setup instructions for the different components of the BCS (Bus Control System) project.

---

## 🔗 Project Repositories & Installation Instructions

### 🛠️ Admin Portal
**Repository:** [bcs-admin-panel](https://github.com/NoobKodak/bcs-admin-panel.git)  
A web-based portal for admin-level operations and controls.

**Setup Instructions:**
```bash
git clone https://github.com/NoobKodak/bcs-admin-panel.git
cd bcs-admin-panel

# Install dependencies with legacy peer dependencies to satisfy react-day-picker
npm install --legacy-peer-deps

# Then run the regular install
npm install
# Then start the server
npm run dev

For bsc-website folder
-----
cd bsc-website

# Then run the regular install
npm install

# Then start the server
npm run dev

For tenant-mobile-app-main folder
-----
cd tenant-mobile-app-main

# Then run the regular install
npm install

# Then start the server
npm run dev
-----

For terminal-patrol-app folder
-----
cd terminal-patrol-app

# Then run the regular install
npm install

# Then start the server
npm run dev
