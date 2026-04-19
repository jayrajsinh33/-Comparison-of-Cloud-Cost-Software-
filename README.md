# 🌿 EcoCloud - Sustainable Energy Cost Optimization System

## 🎯 Project Overview

A modern, responsive web platform that optimizes cloud computing costs using sustainable energy practices. This frontend-only application provides real-time cloud provider comparison, cost calculators, AI recommendations, and renewable energy integration.

## ✨ Features

### 🎬 Loading Animation
- EcoCloud logo with fade-in, scale, and glow effects
- 2-3 second animated transition

### 🏠 Home Page
- Hero section with animated background particles
- 3 feature cards: Cost Optimization, Cloud Comparison, Smart Analytics

### 📊 Cloud Comparison
- Compare AWS, Azure, and GCP pricing
- Interactive bar and line charts (Chart.js)
- Filter by cheapest or best performance

### 💰 Cost Calculator
- Dynamic pricing based on storage and compute usage
- Automatic best provider suggestion
- AI-powered recommendations

### 📡 Real-Time Dashboard
- Energy usage graph
- Cost trends visualization
- Animated charts updating in real-time

### 🛒 Compare & Shop Section
- Cloud service cards (AWS EC2, Azure VM, GCP Compute)
- Selection and comparison panel
- Dynamic graph showing selected services

### 🤖 AI & Smart Features
- Cost prediction simulation
- Smart provider switching recommendations
- Machine learning concept explanation

### 🌤️ IoT Integration
- Real-time weather data via OpenWeather API
- Solar and wind energy simulation
- Temperature, wind speed, and sunlight data

### 🌱 Carbon Footprint Tracker
- CO2 savings visualization
- Green score with circular progress
- Dynamic updates

### 📚 Additional Sections
- Real-life case studies
- Future scope
- Report export simulation

## 🎨 Color Theme

| Role | Color | Hex |
|------|-------|-----|
| Background | Dark Blue | `#0F172A` |
| Primary | Green | `#22C55E` |
| Secondary | Blue | `#3B82F6` |
| Accent | Yellow | `#FACC15` |
| Text | White/Light Gray | `#F1F5F9` |

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher) - optional, for live server
- Modern web browser

### Method 1: Direct Open
1. Download all files
2. Navigate to `frontend/` folder
3. Open `index.html` in your browser

### Method 2: Using Live Server (Recommended)
```bash
# Install dependencies
npm install

# Start live server
npm start

# Or run development server
npm run dev

The application will open at http://localhost:5500The application will open at http://localhost:5500

📁 Project Structure

ECO-CLOUD-PLATFORM/
├── frontend/
│   └── index.html          # Complete website (HTML/CSS/JS)
├── .env                    # Environment variables (API keys)
├── .gitignore              # Git ignore rules
├── package.json            # NPM dependencies
├── package-lock.json       # Locked dependencies
├── README.md               # Documentation
└── requirements.txt        # Python requirements (optional)

Configuration

OpenWeather API Key
The application uses a demo API key by default. For production:

Sign up at OpenWeatherMap

Get your free API key

Replace the apiKey variable in index.html (line ~550)

const apiKey = 'YOUR_API_KEY_HERE';

;
🎯 Features Demonstrated
✅ Responsive design (mobile + desktop)

✅ Smooth scrolling and animations

✅ Hover effects and card lifts

✅ Section transitions (fade/slide)

✅ Interactive charts (Chart.js)

✅ Real-time data updates

✅ Dynamic calculations

✅ API integration (OpenWeather)

✅ Professional SaaS dashboard UI


📱 Browser Support
Browser	Version
Chrome	90+
Firefox	88+
Safari	14+
Edge	90+

🔄 Real-time Features
Weather data updates every 45 seconds

Energy dashboard updates every 6 seconds

Carbon score updates every 9 seconds

Particle animation background

🧪 Testing
# Run with live server for best experience
npm run dev

# Test responsive design
# Use browser dev tools (F12) → Toggle device toolbar

🙏 Acknowledgments
Chart.js for beautiful charts

Font Awesome for icons

OpenWeatherMap for weather API

Google Fonts for Inter font

🐛 Known Issues
Weather API demo key has rate limits

PDF export is simulated (console alert only)

Currency conversion uses static rates

🚀 Future Enhancements
Backend integration with database

User authentication

Real PDF generation

More cloud providers

Historical data persistence

⭐ Star this repository if you find it useful!

📞 Support
For issues or questions, please open an issue on GitHub.

Built with ❤️ for sustainable cloud computing

---

## **6. requirements.txt** (Optional - for Python users)

```txt
# This file is for Python-based tools or static site generators
# Not required for this HTML/CSS/JS project

# If using Python HTTP server:
# python -m http.server 8000

# No Python dependencies needed for the frontend
# This file is kept for project structure completeness

