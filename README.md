# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

src/
|-- components/
|   |-- SearchBar.jsx      // Search city and add to watch list  
|   |-- WeatherCities.jsx     // Fetch and display weather for selected cities  
|   |-- Summary.jsx     // Daily summary (Avg/Max/Min temp + dominant weather)  
|   |-- VisualAnalysis.jsx       // Visual section for trends (using Chart.js)
|  
|-- utils/
|   |-- AlertConfig.js       // Check threshold breaches and display alerts 
|   |-- weatherApi.js  // Custom hook for fetching weather data periodically 
|-- App.jsx
|-- index.css

