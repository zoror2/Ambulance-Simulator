# Ambulance Simulator v3

A real-time ambulance dispatch and routing simulator built with React and OpenStreetMap (Leaflet).

## Features

- 🗺️ **Real OpenStreetMap** - Uses actual Bangalore city map
- 🚑 **Autonomous Ambulances** - Navigate from hospital to patient and back
- 🚦 **Smart Traffic Signals** - Turn green when ambulance approaches
- 🚗 **Civilian Traffic** - Emoji-based vehicles that yield to ambulances
- 📊 **Real-time Dashboard** - Live status updates and event log
- 🎯 **Interactive Map** - Click ambulances to follow them

## Tech Stack

- React.js
- Leaflet / React-Leaflet
- OpenStreetMap tiles
- CSS3 Animations

## How to Run

1. Navigate to the project folder:
   ```bash
   cd ambulance-simulator-v3
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open http://localhost:3000 in your browser

## Project Structure

```
src/
├── components/
│   ├── AmbulanceMarker.jsx    # Ambulance icon with siren
│   ├── TrafficSignal.jsx      # Traffic light component
│   ├── HospitalMarker.jsx     # Hospital marker
│   ├── PatientMarker.jsx      # Patient pickup location
│   ├── CivilianVehicle.jsx    # Emoji-based traffic
│   ├── Sidebar.jsx            # Control panel
│   └── Sidebar.css
├── data/
│   └── locations.js           # Bangalore coordinates
├── pages/
│   ├── MainDashboard.jsx      # Main simulation page
│   └── MainDashboard.css
├── utils/
│   └── helpers.js             # Distance, movement utilities
├── App.js
└── index.js
```

## Future Enhancements

- [ ] Driver POV mode
- [ ] Road closures
- [ ] Weather effects
- [ ] Multiple hospitals
- [ ] OSRM real routing
