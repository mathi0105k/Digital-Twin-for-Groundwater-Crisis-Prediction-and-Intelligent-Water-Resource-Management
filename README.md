# ◈ AquaTwin – Groundwater Digital Twin

AI-assisted groundwater crisis prediction dashboard (academic prototype for SIH 2026).

> ⚠️ **Demo only.** All readings, risk levels and forecasts are **simulated**. No real sensors, government data or trained ML model is connected.

## Features
- Monitoring for 5 Tamil Nadu locations: Chennai, Coimbatore, Salem, Madurai, Tirunelveli
- Live simulated readings: groundwater depth, rainfall, recharge, extraction
- Water Availability Index and Crisis Risk (Low / Medium / High)
- Groundwater level trend chart (HTML canvas)
- 7-day illustrative outlook
- Illustrative Tamil Nadu risk map
- Auto-generated early-warning alerts
- Pause / resume simulation, responsive layout

## Tech Stack
HTML, CSS, JavaScript (no libraries, no build step)

## Run Locally
1. Download or clone this repo
2. Open `index.html` in any browser

```bash
git clone https://github.com/<your-username>/aquatwin.git
cd aquatwin
```

## Live Demo
Enabled via GitHub Pages: `https://<your-username>.github.io/aquatwin/`

## Project Structure
```
aquatwin/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## Future Scope
- Connect real IoT well sensors
- Integrate a trained ML model (e.g., LSTM / Random Forest) for forecasting
- Use official CGWB / India-WRIS data
- Real district map (GeoJSON + Leaflet)

## Author
**Kishore** – College student | Electronics, Web Development, AI/ML

## License
MIT License – see [LICENSE](LICENSE)
