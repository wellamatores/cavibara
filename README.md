```markdown
# 🗺️ Cavibara Cartógrafa

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Deployed-black)](https://cavibara.vercel.app)
[![GitHub stars](https://img.shields.io/github/stars/wellamatores/cavibara)](https://github.com/wellamatores/cavibara/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

**Professional GIS Platform with 3D Earth-Moon Visualization** — integrated mapping, drawing tools, NDVI analysis, and real-time geospatial intelligence.

---

## ✨ Features

### 🗺️ Core GIS
- MapLibre GL JS — free, no API keys required
- Satellite, streets, and terrain layers
- 24 zoom levels with smooth pan/zoom
- Full vector tile support

### 📐 Drawing & Analysis
- Polygon, rectangle, circle drawing
- Distance and area measurement (Turf.js)
- NDVI vegetation health index
- Carbon footprint estimation (t/ha CO₂)
- Real-time weather (temperature, wind speed)
- Land cover detection (forest, agriculture, urban)

### 🌍 3D Visualization
- Interactive Earth with atmospheric clouds
- Orbiting Moon with realistic texture
- Starfield background with depth
- Bloom post-processing effect (glow)
- Orbit controls (rotate, zoom, pan)

### 🌐 Multi-language Support
| Language | Code |
|----------|------|
| Русский | ru |
| English | en |
| Português | pt |
| Español | es |
| العربية | ar |
| 中文 | zh |

### 📊 Analytics & Charts
- Historical NDVI trends (2022-2026)
- Reforestation tracking
- Real-time metrics dashboard
- Interactive data visualization

---

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for map tiles

### Installation

```bash
# Clone repository
git clone https://github.com/wellamatores/cavibara.git

# Navigate to project
cd cavibara

# Open directly in browser
open index.html

# Or use live server for development
npx live-server --port=3000
```

---

## 🎮 Live Demo

**https://cavibara.vercel.app**

---

## 📁 Project Structure

```
cavibara/
├── index.html          # Main application (GIS + 3D)
├── README.md           # Documentation
├── LICENSE             # MIT License
├── .gitignore          # Git ignore rules
├── vercel.json         # Vercel deployment config
└── .github/
    └── workflows/      # GitHub Actions (CI/CD)
```

---

## 🛠️ Technologies

| Technology | Version | Purpose |
|------------|---------|---------|
| MapLibre GL JS | 4.7.0 | Vector/raster map rendering |
| Turf.js | 7.0.0 | Geospatial analysis & calculations |
| Three.js | 0.128.0 | 3D Earth/Moon visualization |
| Chart.js | 4.4.0 | Trend charts & data visualization |
| Open-Meteo API | — | Real-time weather data |
| Overpass API | — | Land cover detection (OSM) |

---

## 📊 GIS Capabilities

### NDVI Analysis
- **Values:** -1 to 1 (healthy vegetation: >0.6)
- **Use cases:** Crop monitoring, deforestation detection, drought assessment
- **Carbon conversion:** NDVI × 180 t/ha for forests

### Measurement Tools
| Tool | Unit | Precision |
|------|------|-----------|
| Polygon Area | Hectares (ha) | ±0.01 ha |
| Rectangle Area | Hectares (ha) | ±0.01 ha |
| Circle Area | Hectares (ha) | ±0.01 ha |
| Linear Distance | Kilometers (km) | ±0.01 km |

### Real-time Data Sources
- **Weather:** Open-Meteo API (current conditions)
- **Land cover:** OpenStreetMap Overpass API
- **Map tiles:** Esri World Imagery, OpenStreetMap, Stamen Terrain

---

## 🎯 Tactical Edition (Restricted Access)

For military, emergency services, and special operations:

- MIL-STD-2525D tactical symbols
- MGRS coordinate grid system
- Line of sight (LOS) analysis
- Encrypted geodata layers (AES-256)
- Stealth route planning
- Offline operation mode

**Contact:** tactical@wellamatores.world  
**Requires security clearance verification**

---

## 🤝 Contributing

We welcome contributions from the community!

### How to Contribute

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/amazing-feature

# 3. Commit your changes
git commit -m 'Add amazing feature'

# 4. Push to the branch
git push origin feature/amazing-feature

# 5. Open a Pull Request
```

### Reporting Issues

Use GitHub Issues with:
- Description of the problem
- Steps to reproduce
- Browser/OS information
- Screenshots (if applicable)

---

## 📄 License

**MIT License** — Free for commercial and private use.

You are free to:
- ✅ Use commercially
- ✅ Modify and adapt
- ✅ Distribute copies
- ✅ Use privately

Under conditions:
- 📌 Include copyright notice
- 📌 Include license text

---

## 🌟 Acknowledgments

- [MapLibre Contributors](https://github.com/maplibre/maplibre-gl-js/graphs/contributors)
- [Turf.js Team](https://github.com/Turfjs/turf/graphs/contributors)
- [Three.js Authors](https://github.com/mrdoob/three.js/graphs/contributors)
- [OpenStreetMap](https://openstreetmap.org)
- [Open-Meteo](https://open-meteo.com)
- [Esri](https://esri.com)

---

## 📞 Contact

| Channel | Link |
|---------|------|
| Website | https://cavibara.vercel.app |
| GitHub | @wellamatores |
| Email | contact@wellamatores.world |

---

## 🗺️ Roadmap

### Completed ✅
- [x] Core mapping functionality
- [x] Drawing and measurement tools
- [x] NDVI and carbon analysis
- [x] 3D Earth-Moon visualization
- [x] Multi-language support (6 languages)
- [x] Responsive design

### In Progress 🔄
- [ ] PWA offline support
- [ ] User authentication
- [ ] Data persistence layer

### Planned 📅
- [ ] Backend API with PostGIS
- [ ] Multi-agent AI integration
- [ ] AR/VR mode
- [ ] Blockchain geodata verification

---

## 📈 Repository Stats

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/wellamatores/cavibara)
![GitHub repo size](https://img.shields.io/github/repo-size/wellamatores/cavibara)
![GitHub last commit](https://img.shields.io/github/last-commit/wellamatores/cavibara)

---

## 🐗 About the Name

**Cavibara** (Capivara in Portuguese) is the capybara — the world's largest rodent, native to South America.

Known for being:
- 🌿 **Adaptable** — thrives in diverse environments
- 🤝 **Social** — lives in harmony with other species
- 🧠 **Intelligent** — highly aware of its surroundings
- 🌎 **Native to the Amazon** — symbol of the region we help protect

> *"Cavivara, que entende do assunto"* — The capybara who knows what's up.

---

**Made with 🐗 by Wellamatores | Innovating cartography, one leaf at a time**
```
