# 🌍 SustainIQ – Climate & Sustainability Dashboard

SustainIQ is a full-stack climate and sustainability dashboard that aggregates real-time data on **weather, air quality, carbon emissions, and climate trends** to help users understand and reduce their environmental impact.  

🚀 Built with **Next.js, TailwindCSS, Node.js, PostgreSQL**, and powered by **OpenWeatherMap, Carbon Interface, and NASA APIs**.  

---

## ✨ Features
- 📊 **Interactive Dashboard** – Visualize climate metrics with real-time data.  
- 🌱 **Carbon Footprint Calculator** – Estimate emissions from daily activities (flights, energy, transport).  
- 🌍 **Global Climate Insights** – NASA/NOAA data on anomalies and sustainability trends.  
- 🗺️ **Air Quality Maps** – Interactive Leaflet.js maps with OpenWeather pollution data.  
- 👤 **User Profiles** – Save favorite cities, track footprint history, and compare against global averages.  
- ⚡ **Scalable Backend** – API aggregation, caching, and JWT authentication.  

---

## 🛠️ Tech Stack
**Frontend**
- [Next.js](https://nextjs.org/) (React framework for SSR & API routes)  
- [TailwindCSS](https://tailwindcss.com/) (utility-first styling)  
- [Recharts](https://recharts.org/en-US/) (data visualization)  
- [Leaflet.js](https://leafletjs.com/) (interactive maps)  

**Backend**
- [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/)  
- REST + GraphQL API  
- Redis caching (optional, for rate limits)  
- [NextAuth.js](https://next-auth.js.org/) for authentication  

**Database**
- PostgreSQL (via [Supabase](https://supabase.com/)) or MongoDB Atlas (free tier)  

**APIs Used**
- [OpenWeatherMap API](https://openweathermap.org/api) → weather & air quality  
- [Carbon Interface API](https://www.carboninterface.com/) → carbon footprint estimates  
- [NASA Earthdata API](https://earthdata.nasa.gov/) → climate & earth observation data  

---

## 📂 Project Structure
sustainiq/
│── frontend/ # Next.js frontend (UI, charts, maps)
│ ├── components/ # Reusable UI components
│ ├── pages/ # Next.js pages (dashboard, profile, insights)
│ ├── hooks/ # Custom React hooks (data fetching, auth, etc.)
│ └── styles/ # TailwindCSS configurations

│── backend/ # Node.js/Express backend
│ ├── routes/ # API endpoints
│ ├── services/ # External API services (OpenWeather, NASA, Carbon Interface)
│ ├── models/ # Database schemas
│ └── middleware/ # Auth, caching, logging

│── db/ # Database migrations and seed files
│── docs/ # Documentation and design files
│── README.md # Project overview
│── package.json # Dependencies and scripts
