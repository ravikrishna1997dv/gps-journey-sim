# GPS Journey Simulator

Interactive road trip simulator. Enter source, destination, departure time, and average speed to see a moving vehicle marker, simulated clock, and estimated arrival times at towns.

## Run

```bash
python3 -m http.server 8000
```

Visit http://localhost:8000. Static HTML app; no build required. Can deploy to Vercel.

## Features

- Driving route with OpenStreetMap and Leaflet
- Moving car marker, simulated clock, arrival estimate
- Town milestones with estimated times
- Play, pause, reset, scrub, replay speed

## Notes

Requires internet access for map tiles, Nominatim geocoding, and public OSRM routing. Public endpoints are for light demos, not production workloads. Time estimates assume constant average speed, without stops or traffic. This is not live GPS tracking or Google Maps.
