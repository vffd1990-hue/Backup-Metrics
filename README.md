# Backup Monitoring Dashboard

A lightweight, browser-based dashboard for monitoring backup executions using CSV files.  
It provides visual insights such as execution trends, data transferred, client distribution, and historical records — all without requiring any backend or installation.

## 🚀 Live Demo
This project is hosted using GitHub Pages.  
Simply open the link provided by the repository owner to access the dashboard.

## 📊 Features
- Upload one or multiple CSV files
- Filter by client and date range
- Key performance indicators (KPIs)
- Interactive charts:
  - Backups per day
  - Data transferred per day
  - Executions per client (pie chart, click to filter)
  - Average duration per client
- Full historical table view
- Unit conversion (MB / GB / TB)
- Fully client-side (no server required)

## 📁 CSV Requirements
The CSV files must contain the following columns:

- `Fecha`
- `Cliente`
- `BytesCopiados`
- `ArchivosCopiados`
- `Duracion`
- `Estado`
- `DiasSinCopia`

Dates should be in a format recognized by the browser (e.g. `YYYY-MM-DD`).

## 🛠 How to Use
1. Open the dashboard URL in any modern browser
2. Upload one or more CSV files
3. Apply filters as needed
4. Interact with charts to explore the data

No installation, login, or backend setup required.

## 🌐 Deployment
This project is deployed using **GitHub Pages**.

To deploy your own version:
1. Fork or clone the repository
2. Ensure the main file is named `index.html`
3. Enable GitHub Pages in repository settings
4. Use the generated URL to access the dashboard

## 🔐 Security & Privacy
- All data is processed locally in your browser
- No data is uploaded to any server
- Closing the browser clears the session

## 📄 License
This project is provided as-is for internal monitoring and visualization purposes.

---

