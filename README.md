# 6-Week Bootcamp Tracker

A shared tracker for a 6-week challenge where everyone eats clean and gets at least 30 minutes of intentional movement a day.

Live app: https://claude.ai/artifact/WyFuqsVnZ8HBgTyuhDTjoV

## What it does
- **Log**: each person logs meals (with an optional photo) and workouts (type, minutes, notes). They can also go back and fill in an earlier day.
- **Squad**: standings ranked by full days, current streaks, total minutes, a 42-day grid for each person, and a live feed of everyone's entries.
- **Recap**: a summary of any day, with a **Copy recap** button that gives you text ready to paste into the group chat.

A day counts as **full** when lunch and dinner are logged and the workouts add up to at least 30 minutes.

## Setup
1. The owner opens the app, goes to **Squad → Challenge setup**, and sets Day 1.
2. **Share** → invite each friend by email as an **Editor**. Don't turn on a public link.
3. Each friend opens the link while signed in to claude.ai and taps **Join**.

`index.html` is the page source. It runs on Claude Artifacts' shared `db`, `user` and `assets` capabilities.
