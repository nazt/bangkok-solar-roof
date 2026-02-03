# Bangkok Solar Roof

Interactive map showing **3.26 million building rooftops** in Bangkok with solar energy potential analysis.

## Stats

| Metric | Value |
|--------|-------|
| Total Buildings | 3,257,805 |
| Solar Ready (≥50m²) | 2,099,592 (64.4%) |
| Total Roof Area | 460.46 km² |
| Solar Potential | **117.65 TWh/year** |

## Data Source

- Building footprints: [Google Open Buildings V3](https://sites.research.google/open-buildings/)
- Downloaded via Google Earth Engine
- Viewer shows 50K sample (full dataset: 1.7GB)

## Deploy

### Vercel
```bash
vercel
```

### Netlify
```bash
netlify deploy --prod
```

### Local
```bash
python3 -m http.server 8080
open http://localhost:8080
```

## Structure

```
bangkok-solar-roof/
├── index.html          # Main viewer
├── data/
│   └── bangkok_viewer.json  # 50K building sample (26MB)
└── README.md
```

## License

Data: Google Open Buildings (CC BY 4.0)
Code: MIT
