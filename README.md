# E85-Radar
E85 station locator with community ethanol content ratings. Built with the NREL Alternative Fuels API and Firebase.

**Live app → [fujikenwara-555.github.io/e85-radar](https://fujikenwara-555.github.io/e85-radar/)**

E85 station locator built for the flex fuel community. Find stations near you, see real ethanol content reported by other E85 drivers, and know what you're actually getting at the pump before you pull in.

## Why this exists

E85 ethanol content varies — sometimes significantly — by season, region, and supplier. The pump says E85 but you might be getting E51 in winter or E83 in summer. This app lets the community track and share actual ethanol percentages per station so you can tune accordingly.

## What it does

- Finds E85 stations near you via GPS or city search
- Shows every station on a map with the latest community-reported ethanol %
- Displays full rating history per station with dates so you can spot trends
- Sorts by distance or ethanol content
- Fuel blend calculator — enter your tank size, current E%, and target E% to get exact gallons of E85 and pump gas to add
- No account needed, no ads, free to use

## Community ratings

Ratings are submitted by real users after fueling up. Each report shows the ethanol percentage, date, and how long ago it was submitted. Reports are permanent so rate carefully — the history is the value.

## Built with

- [NREL Alternative Fuels Station API](https://developer.nrel.gov) — station location data
- [Firebase Realtime Database](https://firebase.google.com) — community ratings sync
- [Leaflet.js](https://leafletjs.com) + OpenStreetMap — map
- Vanilla HTML/CSS/JS — no framework, no build tools

---

*Independent beta tool. Not affiliated with any fuel brand or station.*