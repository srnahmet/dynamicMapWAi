# 🗺️ AI-Powered GIS Application Prototype

**"What if a GIS application had built-in AI?"**

This project is a small prototype exploring how **artificial intelligence** can be integrated into **Geographic Information System (GIS)** applications for enhanced search and data exploration experiences.

---

## 🚀 Features

### 🔹 1. SearchAddress (Smart Address Search)
- Users can:
  - Search for addresses via **Nominatim API**, or
  - Ask AI questions in natural language.
- Example query:  
  `"Can you recommend a good museum to visit in Istanbul?"`
- The AI responds (e.g., *"Istanbul Archaeology Museum"*),  
  and the application visualizes the location using **Esri Public Basemap**.

> ✅ AI provides the suggestion.  
> 📍 Nominatim handles geocoding and mapping.

---

### 🔹 2. ChatExplore (Data Exploration & Analysis)
- The backend connects to a **PostgreSQL/PostGIS** database.
- AI (via **DeepSeek API**) knows the database structure (tables & columns).
- Users can type natural queries like:


Show me the top 5 provinces with the highest population.

- AI generates the corresponding SQL query.
- Backend executes it and returns:
- Spatial results (shown on the map)
- Tabular and chart-based data visualization (bar/pie/line)
- The executed SQL query is also visible to users for transparency.

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | ReactJS + OpenLayers |
| Backend | Python (Flask) |
| Database | PostgreSQL + PostGIS |
| AI | DeepSeek API |
| Address Search | Nominatim |
| Basemap | Esri Public Basemap |
| Data | OpenStreetMap (OSM) datasets |

---

## 🧱 Demo Version

This repository hosts a **frontend-only** demo version.  
Since the backend is not publicly deployed, pre-defined queries and analysis results are loaded from static JSON files.

You can still:
- Explore the **interface**
- Test the **search and visualization features**
- View **mock analysis results**

---

## ⚖️ License & Data Usage

- Source code is distributed under the **MIT License** (see [LICENSE](./LICENSE)).
- Base maps and geospatial data:
- © [Esri Public Basemap](https://www.esri.com/en-us/arcgis/products/basemap/overview)
- © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright)
- Address data via [Nominatim API](https://nominatim.org)
- AI features powered by [DeepSeek API](https://www.deepseek.com)

> This is an experimental, non-commercial project for research and educational purposes.

---

## 👨‍💻 Author

**Ahmet [Your Surname]**  
Fullstack GIS Developer  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/your-profile)  
📧 Contact: [your.email@example.com]

---

## 🧠 Future Improvements
- Real-time backend integration (Flask + PostgreSQL/PostGIS)
- More advanced spatial analytics
- Support for multilingual AI queries
- Integration with routing and navigation APIs

---

## ⭐ Acknowledgements
Special thanks to:
- [Esri](https://www.esri.com)
- [OpenStreetMap Community](https://www.openstreetmap.org)
- [DeepSeek](https://www.deepseek.com)
- [Nominatim](https://nominatim.org)

---

> *“Bringing AI closer to GIS — because maps can think too.”*
