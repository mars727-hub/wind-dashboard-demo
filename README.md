# Global Offshore Wind Farm Dashboard 🌍

A static, interactive demonstration of selected offshore wind projects. Filter by status and country to update the map, project table and summary cards.

[Open the live demo](https://mars727-hub.github.io/wind-dashboard-demo/)

## Run locally

Open `index.html` in a browser, or serve the directory with `python -m http.server 8000` and visit `http://localhost:8000`. The map, fonts and icons require an internet connection; filtering and the table remain available if the map library cannot load.

## Data limitations

The dataset is embedded in `index.html`. It is a selected, historical demonstration dataset, not a live feed or a complete global inventory. Project locations, statuses, capacity and ownership may be approximate or outdated; verify them against authoritative sources before use. Listed capacity includes planned and construction projects and is not equivalent to operating capacity. The operational count includes only projects labelled fully operational. The Formosa 4 polygon is illustrative and must not be used as an authoritative boundary.

## Interaction

Use the filters to narrow the results. Select a table row with a mouse or keyboard to move the map to that project. Map markers show project details without changing the filtered table. On desktop, drag the sidebar edge to resize it.
