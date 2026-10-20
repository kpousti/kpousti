# Hi, I'm Kia 👋

Software developer in industrial IT in San Diego. UCSD Math–CS grad (2026). I build fast graph and routing systems in C++, and I'm applying AI to the unglamorous problems that keep heavy industry running.

- 🏭 **Now:** Software Developer, IT Rotational Program @ Solar Turbines (a Caterpillar company)
- 🤖 **Building:** [Industrial AI Notebook](https://github.com/kpousti/industrial-ai-notebook), a growing set of working AI prototypes for industrial IT
- 🧭 **Focus:** graph algorithms · performance engineering · applied ML
- 📫 [LinkedIn](https://linkedin.com/in/kiapousti) · kiapousti@gmail.com

---

## Featured work

### 🤖 [Industrial AI Notebook](https://github.com/kpousti/industrial-ai-notebook) · Python, scikit-learn
Short case studies showing how AI can fix real industrial-IT problems, each with runnable code, tests and an honest results table. All data synthetic.
- **001:** Equipment anomaly detection. A z-score baseline vs. Isolation Forest on sensor telemetry: the ML model caught ~2× the faults, including slow drift the baseline missed.

### 🗺️ [Route Engine](https://github.com/kpousti/route-engine-demo) · C++
Offline routing over real OpenStreetMap data (~1.2M nodes / ~2.5M edges).
- A* with a haversine heuristic over a cache-efficient CSR graph
- Lat/lon snapping, HTTP API serving GeoJSON, Leaflet map UI
- ~89% smaller route payloads via polyline simplification

### 📍 [Mini Maps](https://github.com/kpousti/mini-maps-cpp) · C++
A lightweight weighted shortest-path engine built for correctness and clarity.
- BFS (O(V + E)) and heap-based Dijkstra (O(E log V))
- Deterministic path reconstruction, modular Make build

### 🌐 Open source · [TheAlgorithms/C++](https://github.com/TheAlgorithms/C-Plus-Plus)
- Contributed a Tarjan's strongly-connected-components implementation (PR #2973)

---

## Toolbox
**Languages:** C++ · Python · JavaScript
**ML & data:** scikit-learn · pandas · NumPy
**Systems:** CSR graphs · cache-aware layout · REST APIs · Linux · Git · CMake
