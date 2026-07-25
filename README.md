# ⚽ Football Tracking Analytics Engine

A Python-based football tracking analytics engine built using SkillCorner's open tracking dataset.

This project transforms raw player and ball tracking data into live tactical, spatial, and physical performance insights through frame-by-frame analysis and interactive visualizations.

---

# 🚀 Features

## 📍 Live Tracking

- Animated player tracking
- Ball tracking
- Shirt numbers
- Team colours
- Player movement trails
- Match timeline

---

## 🏃 Physical Performance Analytics

- Fastest player
- Distance covered
- Sprint detection
- Sprint leader
- Player speed calculation

---

## 📐 Tactical Analytics

- Team possession
- Convex Hull
- Convex Hull Area
- Team Width
- Team Length
- Team Compactness

---

## 🗺️ Spatial Analytics

- Voronoi Diagrams
- Team Space Control
- Space Control Percentage

---

## ⚽ Passing Analytics

- Tracking-based pass extraction
- Passing Network (Inferred from tracking data)
- Player passing involvement
- Average player positions

---

## 📊 Match Dashboard

The live dashboard updates every frame with:

- Competition information
- Match clock
- Possession
- Fastest player
- Distance leader
- Sprint leader
- Team dimensions
- Convex Hull Area
- Space control

---

# 🛠 Technologies

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib
- mplsoccer
- Shapely
- JSON / JSONL

---

# 📂 Dataset

SkillCorner Open Tracking Data

- Match Metadata (.json)
- Tracking Frames (.jsonl)
- Player Metadata

---

# 📸 Project Screenshots

## Live Tracking Dashboard

<img width="510" height="340" alt="image" src="https://github.com/user-attachments/assets/6d9c2c23-0464-4d2c-970f-378b654daccf" />


---

## Team Shape (Convex Hull)

<img width="1500" height="1000" alt="image" src="https://github.com/user-attachments/assets/4c28028e-fadd-49e1-92f4-f9764f6e91e3" />


---

## Heat Map

<img width="681" height="460" alt="image" src="https://github.com/user-attachments/assets/73829c3e-f417-4f9f-93dc-76dbb7e30486" />

---

# 🎥 Demo

A frame-by-frame animation of the tracking engine is included.

**Tracking Animation**

`assets/tracking_analysis.mp4`

---

# 📈 Analytics Workflow

```text
Tracking Data
      │
      ▼
Frame Processing
      │
      ├── Player Tracking
      ├── Ball Tracking
      ├── Convex Hull
      ├── Team Width
      ├── Team Length
      ├── Compactness
      ├── Voronoi Diagram
      ├── Space Control
      ├── Sprint Detection
      ├── Distance Covered
      ├── Possession
      ▼
Match Analytics
      │
      ├── Passing Network
      ├── Tactical Analysis
      ├── Physical Metrics
      └── Spatial Analytics
```

---

# 🔮 Future Improvements

- Pressure Maps
- Defensive Line Height
- Team Centroid
- Stretch Index
- Passing Lanes
- Pressing Intensity
- Expected Threat (xT)
- Off-ball Run Detection
- Formation Detection
- Interactive Streamlit Dashboard

---

# 👨‍💻 Author

**Stephen Yaw Ayamah**

Data Scientist | Football Analytics | Python | Machine Learning | Sports Analytics
