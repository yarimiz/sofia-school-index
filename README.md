# Sofia Primary School Explorer

A lightweight, interactive web application designed to help parents explore and compare primary schools (1st-grade entry) in Sofia, Bulgaria.

## Overview

This tool provides a user-friendly interface to browse school data, visualize locations on a map, and compare tuition fees. It is built as a single-page application (SPA) with no external build requirements.

## Features

- **Interactive Map:** Visualizes school locations using [Leaflet.js](https://leafletjs.com/) with OpenStreetMap tiles.
- **Directory List:** A sortable table of schools showing name, district, tuition fees, and property badges (Type & Language).
- **Tuition Chart:** A bar chart comparing annual tuition fees for private schools (powered by [Chart.js](https://www.chartjs.org/)).
- **School Details:** Select a school to view detailed information including contact details, website links, and key features.
- **Responsive Design:** Fully responsive layout using [Tailwind CSS](https://tailwindcss.com/).

## Technologies Used

- **HTML5**
- **Tailwind CSS** (via CDN) for styling
- **Leaflet.js** (via CDN) for maps
- **Chart.js** (via CDN) for charts
- **Vanilla JavaScript** for logic and state management

## Setup & Usage

This project is a static HTML file with no build step required.

1.  Clone or download the repository.
2.  Open `index.html` directly in your web browser.
3.  Ensure you have an active internet connection to load the CDNs (Tailwind, Leaflet, Chart.js) and map tiles.

## Data Source

The school data is stored in `schools.js` as the `schoolsData` array. It includes **22 schools** with real names, addresses, coordinates, and tuition estimates for the 2024/25 school year.

**Schools include:**

- 18 Private/International schools (IB, British, American, Canadian, German, French curricula)
- 4 Public municipal schools (high-performing per NVO data)

**Sources used:**

- International Schools Database (https://international-schools-database.com)
- John Catt International School Search
- Danybon NVO rankings (https://danybon.com)
- Official school websites

_Note: Data is for demonstration and informational purposes. Please verify specific details with the respective schools._
