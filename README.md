# Chaos Walk Tracker

> A ritual-powered, data-informed personal observability project

Welcome to the **Chaos Walk Tracker**. This is a personal experiment where daily solo runs become more than fitness—they become rituals, symbol-making, and encounters with the strange. Inspired by shamanic traditions, quantified-self logging, and cloud observability principles, this project blends the mystical with the measurable.

## Goals
- Add meaning and structure to daily runs
- Log insect encounters, glitches, unusual observations
- Correlate personal "chaos signals" with Strava run data
- Track patterns over time using both symbolic and numeric input

## Repo Structure
```
chaos-walk-tracker/
├── README.md          # You're here
├── logs/              # Daily/weekly chaos ritual logs
├── strava-data/       # Exported run data from Strava (CSV/GPX/JSON)
├── sigils/            # Weekly symbolic drawings or notes
├── scripts/           # Helpers for formatting logs, parsing Strava data
└── meta.md            # Personal reflections, system thinking, and roadmap
```

## Getting Started
1. Begin a daily or weekly log under `/logs` (e.g., `2025-03-25.md`)
2. Record your ritual observations: insect encounters, odd events, thoughts
3. Export your Strava data for the same day (see instructions below)
4. Optionally: draw a sigil from that day's keywords or experience

## Exporting Data from Strava
**To manually export individual runs:**
1. Go to [strava.com](https://www.strava.com) and log in.
2. Navigate to **"My Activities"**.
3. Click on a specific activity.
4. Click the three-dot menu (top right of the map box), choose **"Export GPX"**.
5. Save the `.gpx` file and place it under `/strava-data/`

**To export a batch of activities:**
1. Go to [Strava Settings > My Account](https://www.strava.com/settings/profile)
2. Scroll to **"Download or Delete Your Account"**
3. Request your archive (takes a few minutes to hours)
4. You'll receive a `.zip` with `.csv` files containing all your activities
5. Extract and copy a selection to `/strava-data/`

## Suggestions & Next Steps
- Add a `log_template.md` for structured logging
- Visualize chaos frequency per week/month using a small chart
- Build a script to merge Strava data + chaos notes
- Create `sigils/` as images or ASCII art generated from keywords

## Example Entry
**Date**: 2025-03-25  
**Distance**: 6.1 mi — 54 minutes  
**Insect Encounter**: Tiny ant on inner elbow after run  
**Glitch**: Flash of bird shadow, but no bird seen  
**Thoughts**: Felt like I was being watched. Breathing heavy but smooth.  
**Sigil**: Created from words: watch, ant, flight, smooth

---

Stay weird. Stay aware.

> "I leave a part of me behind—so I may find more ahead."
