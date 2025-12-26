# Campus Connect

A smart and interactive campus navigation and accessibility reporting system built using **React**, **Vite**, **Supabase**, **Tailwind CSS**, and **Google Maps API**.

Campus Connect helps students and staff:
- Report accessibility and infrastructure issues
- Navigate the campus efficiently
- Provide real-time visibility for administrators

---

## 🚀 Features

- Interactive campus map
- Issue reporting with file upload
- Issue dashboard and tracking
- Supabase backend (database + storage)
- Clean UI using Tailwind CSS

---

## 📌 Prerequisites

Before running this project, make sure you have:

- Node.js (v14 or newer)
- npm (comes with Node)
- A Supabase account + project
- A Google Maps API key

---

## 📥 Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/Kamal-Raj-A/mini_project_R2W1.git
cd mini_project_R2W1
```

### 2️⃣ Install dependencies
```
npm install
```

### 🔐 Environment Variables

Create a file called .env.local in the root folder:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

You can find your Supabase keys here:

Supabase → Settings → API

### 🗄️ Database Setup (Supabase)

Run the SQL files inside:
```
supabase/migrations/
```

Paste each file into the Supabase SQL Editor and execute.

This will create:

Issues table

Policies

Storage bucket for images

### ▶️ Running the Project

Start development server:
```
npm run dev
```

Then open:
```
http://localhost:5173
```

### 📦 Build for Production
```
npm run build
npm run preview
```

### 🧩 Project Structure
```
src/
 ├── components/        # UI components
 ├── data/              # Static campus data
 ├── lib/               # Supabase config + helpers
 ├── main.tsx
 └── App.tsx

supabase/
 └── migrations/        # Database SQL scripts
```

### 🌱 Tech Stack

React + TypeScript

Vite

Supabase

Tailwind CSS

Google Maps API

### ⚠️ Notes

Do NOT commit your .env.local file

Google Maps key must be restricted

Supabase database rules should be configured carefully

### 📜 License

This project is licensed under GPL-3.0.
See the LICENSE file for details.
