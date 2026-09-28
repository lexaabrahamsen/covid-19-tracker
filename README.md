# COVID-19 Tracker

A dashboard of global and per-country COVID-19 cases, with summary cards and charts.

> **Status: archived.** The data source, [covid19.mathdro.id](https://github.com/mathdroid/covid-19-api), is no longer online, so the app can't load data today. The code is kept as a reference project.

## Features

- **Summary cards** for infected, recovered, and deaths, with animated counters
- **Country picker** to switch from global totals to a single country
- **Charts:** a daily line chart for global cases and deaths, and a bar chart for the selected country

## Built with

React · Material UI · Chart.js (react-chartjs-2) · Axios · react-countup

## Run locally

```sh
npm install
NODE_OPTIONS=--openssl-legacy-provider npm start
```

`NODE_OPTIONS=--openssl-legacy-provider` is needed on Node 17 and later, because this project uses Create React App 3 (webpack 4). The command above is for macOS and Linux.

---

Built by [Lexa Wong](https://www.lexawong.dev/)
