# Daywell

A private, single-device day planner. It runs as a static website and stores its settings and plan in this browser's local storage.

## How planning works

- Add/edit activity types, session length ranges, and daily minimum/maximum counts.
- Add the time windows in which sessions may be booked. An end time earlier than its start crosses midnight.
- Set sleep, leisure, and Pomodoro focus/rest preferences.
- **Build my day** places the minimum required sessions first, then adds optional sessions while respecting maximum counts, free windows, sleep, and the leisure minimum. It reports when the current combination cannot fit.
- Start a session for a live focus/rest timer; completed and skipped sessions update the daily progress.

The planner intentionally doesn't assume that time outside your free windows is available for work. Adjust the windows as your day changes, then rebuild to adapt the remaining plan.
