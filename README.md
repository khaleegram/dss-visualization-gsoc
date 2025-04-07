# DSS Analysis Visualizer

A web-based graph visualization tool for Distributed Summary Synthesis (DSS), built with Next.js + React.

This tool renders distributed block analyses of software verification tasks into interactive, layered visualizations  helping developers, researchers, and contributors better understand the performance and outcome of each DSS verification run.

## 🔍 Features

- 🔄 Real-time data fetching from DSS coordinator database
- 📊 Interactive graph visualizations (block-wise analysis)
- 🧠 Toggle visualization layers (runtime, block size, status)
- 🔍 Drill-down into individual blocks and statistics
- 🧪 Backend integration tests for API endpoints
- 📄 Extensive documentation and setup guide

## 🧱 Tech Stack

- Frontend: Next.js, React, Tailwind CSS, React Flow (or D3.js)
- Backend Integration: PostgreSQL or REST APIs from DSS
- Testing: Jest, React Testing Library
- CI/CD: GitHub Actions
- License: MIT

## 📦 Installation

```bash
git clone https://github.com/yourusername/dss-visualization-gsoc.git
cd dss-visualization-gsoc
npm install
npm run dev
