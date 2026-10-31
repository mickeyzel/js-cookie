# Roundabout Lab

A single-file web app (`index.html`, no dependencies) that simulates traffic through a
single-lane roundabout while you change its geometry live.

Open `index.html` in any phone or desktop browser.

- **Shape:** ellipse, race-track (stadium) or rounded square; size, elongation, rotation.
- **Roads:** 3–6 roads; per road: position around the ring (or drag the road on the map),
  approach angle (skewed / side entry), traffic volume.
- **Physics:** car-following (IDM), speed limited by bend curvature (lateral grip ≈ 0.22 g),
  gap acceptance at the give-way line that depends on how long the entry curve takes to drive.
- **Readouts:** throughput, average stopped time, queues, ring speed, tightest bend,
  trends over the last 6 minutes with markers where the layout changed.
