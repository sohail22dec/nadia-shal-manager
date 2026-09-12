# 🧺 Nadia Shal Manager

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-16.3-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)
![Python](https://img.shields.io/badge/Python-3.12+-yellow?style=for-the-badge&logo=python)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css)

**A modern business management and digital data collection platform for Nadia Shal Dry Wash Clinic.**

[Overview](#-overview) • [Core Objectives](#-core-objectives) • [Tech Stack](#-tech-stack) • [Project Structure](#-project-structure) • [Getting Started](#-getting-started) • [Development Roadmap](#-development-roadmap)

</div>

---

## 📖 Overview

**Nadia Shal Dry Wash Clinic** is a traditional dry-cleaning and laundry family business in West Bengal, India. The business handles a diverse range of garments—including sarees, shirts, trousers, coats, sherwanis, blankets, and ethnic wear—and is run collaboratively by multiple family members/owners.

Historically, business operations have relied on paper receipt books with a unique rotational ownership system, where receipt books are cycled among 5–6 family partners.

**Nadia Shal Manager** is designed to modernize this workflow:
- Transition from physical receipt books to a centralized, reliable digital database.
- Preserve the rotational multi-owner accounting and operational model.
- Provide clean, structured data collection without overwhelming non-technical users.
- Lay the foundation for future inventory management, analytics, and an AI-powered business assistant.

---

## 🎯 Core Objectives

1. **Digital Customer Database**: Centralize customer records, contact information, order history, and preferences.
2. **Multi-Owner / Turn Tracking**: Accommodate the rotational receipt-book system so revenue and order ownership remain accurate and transparent.
3. **Simple, Frictionless UX**: Built for family members who are non-technical; fast order entry and minimal friction.
4. **Data Integrity & Scalability**: Clean data schema designed to scale into order lifecycle tracking, financial reports, and business intelligence.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **UI Library**: [React 19](https://react.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Package Manager**: [pnpm](https://pnpm.io/)

### **Backend**
- **Language**: Python 3.12+
- **Environment & Package Manager**: [uv](https://github.com/astral-sh/uv)
- **API Framework**: FastAPI / Python backend service

---

## 📁 Project Structure

```text
nadia-shal-manager/
├── backend/                  # Python backend service
│   ├── main.py               # Application entry point
│   ├── pyproject.toml        # Dependencies and project metadata
│   └── .python-version       # Python version specification
│
├── frontend/                 # Next.js web application
│   ├── app/                  # Next.js App Router (pages, layout, styles)
│   ├── public/               # Static assets & icons
│   ├── package.json          # Node dependencies & scripts
│   ├── tsconfig.json         # TypeScript configuration
│   └── next.config.ts        # Next.js configuration
│
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js**: `v20+`
- **pnpm**: `v9+` (or npm / yarn)
- **Python**: `v3.12+`
- **uv**: recommended for Python environment management

---

### 1. Setting Up the Frontend

Navigate to the `frontend` directory and install dependencies:

```bash
cd frontend
pnpm install
```

Start the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to view the application.

---

### 2. Setting Up the Backend

Navigate to the `backend` directory:

```bash
cd backend
```

Create a virtual environment and install dependencies using `uv`:

```bash
uv venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
uv pip install -r pyproject.toml
```

Run the backend application:

```bash
python main.py
```

---

## 🗺️ Development Roadmap

- [ ] **Phase 1: Customer Database** — Digitize customer directory, search, and contact details.
- [ ] **Phase 2: Orders & Garment Tracking** — Manage item intake (sarees, coats, etc.), status, and delivery.
- [ ] **Phase 3: Payments & Outstanding Balances** — Receipts, advance payments, and dues tracking.
- [ ] **Phase 4: Expenses & Multi-Owner Accounts** — Track shop expenses and rotational receipt-book revenue.
- [ ] **Phase 5: Business Analytics** — Revenue trends, top services, customer retention metrics.
- [ ] **Phase 6: Mobile / Android Application** — Fast on-the-counter access for shop operations.
- [ ] **Phase 7: WhatsApp & Customer Notifications** — Automatic pickup reminders and ready-for-delivery alerts.
- [ ] **Phase 8: AI Business Assistant** — Conversational analytics querying real shop data.

---

## 📄 License

Private repository for **Nadia Shal Dry Wash Clinic**. All rights reserved.
