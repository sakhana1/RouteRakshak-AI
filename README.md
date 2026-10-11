# 🚌 RouteRakshak AI

### Intelligent Campus Transportation & Student Safety Platform

RouteRakshak AI is a campus transportation management platform designed to simplify journey planning, bus discovery, booking management, and student travel safety through a unified web interface.

The project aims to make campus transportation more accessible, organized, and convenient for students and campus transport administrators.

## ✨ Key Features

- **Dashboard** — View transportation information and journey summaries.
- **Find a Bus** — Explore available campus transportation options.
- **Journey Planner** — Plan campus trips and review route information.
- **My Bookings** — Review and manage demo journey bookings.
- **Live Tracking** — Dedicated interface for journey tracking.
- **Journey Rescue** — Interface for travel assistance and rescue workflows.
- **Demand Pulse** — Explore transportation demand information.
- **Journey Safety** — Access journey safety-related features.
- **My Reports** — Review transportation reports.
- **Notifications** — View travel-related notifications.
- **Profile & Settings** — Manage demo profile and application preferences.
- **Help & Support** — Access support information.

> **Current status:** The frontend includes demo-oriented functionality. Live GPS tracking, real vehicle data, secure authentication, backend APIs, and production booking integrations require further implementation and integration.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | User interface |
| TypeScript | Type-safe application development |
| Vite | Development server and build tooling |
| Tailwind CSS | Interface styling |
| shadcn/ui components | Reusable UI components |
| Recharts | Data visualization |
| npm | Dependency management |

## 📁 Project Structure

```text
RouteRakshak-AI-Website/
├── .gitignore
├── README.md
└── frontend/
    ├── public/
    ├── src/
    │   ├── components/
    │   │   ├── ui/
    │   │   └── error-boundary.tsx
    │   ├── hooks/
    │   ├── lib/
    │   ├── pages/
    │   ├── services/
    │   ├── App.tsx
    │   ├── main.tsx
    │   ├── index.css
    │   └── types.ts
    ├── index.html
    ├── package.json
    ├── tsconfig.json
    └── vite.config.ts
```

## 🚀 Getting Started

### Prerequisites

- Node.js (a current supported LTS version is recommended)
- npm
- Git (optional, for version control)

### 1. Clone the repository

```bash
git clone https://github.com/sakhana1/RouteRakshak-AI.git
cd RouteRakshak-AI
```

### 2. Navigate to the frontend

```bash
cd frontend
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the local URL displayed in your terminal, usually:

`http://localhost:5173/`

### 5. Create a production build

```bash
npm run build
```

The generated production files will be placed in `frontend/dist/`.

## 🔐 Security Notes

- Never commit passwords, API keys, access tokens, or `.env` files.
- Use server-side authentication and authorization for protected operations.
- Validate bookings and other sensitive actions on the backend.
- Use HTTPS when deploying the application publicly.
- Do not treat browser-local demo data as secure or authoritative production data.

## 🗺️ Roadmap

- [ ] Implement a secure backend API.
- [ ] Integrate real user authentication and authorization.
- [ ] Connect live vehicle tracking and map services.
- [ ] Implement production-ready booking and cancellation workflows.
- [ ] Add verified transport schedules and availability.
- [ ] Implement notifications and journey safety workflows.
- [ ] Add automated testing and production deployment.
- [ ] Improve accessibility and mobile responsiveness.

## 🎯 Project Goal

To develop a practical campus transportation platform that helps students plan journeys, manage bookings, and access travel safety features from one place.

## 📌 Repository

GitHub: https://github.com/sakhana1/RouteRakshak-AI

---

**RouteRakshak AI** — Smarter Campus Journeys, Safer Travel.
