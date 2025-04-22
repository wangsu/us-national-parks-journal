# US National Parks Journal

An interactive, shareable map of all 63 U.S. National Parks built with [Leaflet.js](https://leafletjs.com).  Click to mark parks as “visited,” double‑click or use the **Reset** button to unmark, and share your progress via a URL query string or reversible hash.

---

## 🗺️ Demo

🔗 Live demo: https://nationalparkjournal.wangsu.dev/

---

## 🚀 Features

- **All 63 U.S. National Parks** plotted by latitude/longitude  
- **White vs. green markers** for unvisited vs. visited parks  
- **Single‑click** toggles visited; **double‑click** clears  
- **Draggable, collapsible overlay** showing:
  - Visited count (`X / 63 visited`)
  - List of visited parks with checkboxes  
  - **Reset** button to clear all  
- **Persistent state** in `localStorage`  
- **Shareable URLs**:
  - Plain text: `?parks=acadia,yellowstone…`
  - Compact base64 hash: `?p=MCwyNjI…`  

---

## 📦 Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Edge, Safari)  
- (Optional) [Node.js](https://nodejs.org) & [npm](https://npmjs.com) for local HTTP server  

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/wangsu/us-national-parks-journal.git
   cd us-national-parks-journal
