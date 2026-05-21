# ✈️ Aircraft Maintenance Checklist

A lightweight, web-based aircraft maintenance checklist tool built to replace paper technical logs and manual Excel tracking in day-to-day aviation maintenance operations.

🔗 **Live demo:** https://slippelydia.github.io/Aircraft-Maintenance-Checklist/

---

## Background

As an aircraft maintenance technician, I experienced firsthand how most tasks were managed manually technical logs, fuel records, inspection sign-offs, and job tracking were all done on paper and entered into the Excel one by one. While this process was functional, it was time-consuming and prone to errors.

This project is my attempt to explore what a simple, accessible, web-based alternative could look like and to gather feedback from technicians in the field on what they actually need.

---

## Features

- **Multi-aircraft support** — Narrowbody (A320/B737), widebody (B777/A330/B787), regional jet (E145/CRJ/ATR), helicopter (AS350/Bell/Sikorsky), turboprop (DHC-8/King Air), and general aviation
- **Multiple inspection types** — Pre-departure, post-flight, turnaround, transit check, weekly/A-check, and general maintenance
- **Digital sign-off** — Each completed task is timestamped and attributed to the technician
- **Audit trail** — Every action is logged in a full session audit trail
- **Technician notes** — Add notes to any task directly in the checklist
- **Filters & search** — Filter by priority (critical/medium/routine), status (open/completed), or search by keyword
- **Export** — Download a full maintenance log as a `.txt` file for record-keeping
- **No installation required** — Runs entirely in the browser, no login or setup needed

---

## How to Use

1. Select your **aircraft type** and **inspection type** from the dropdowns
2. Enter the **aircraft registration** and **technician name**
3. Work through the checklist — check off tasks as they are completed
4. Add technician notes to any task by clicking **Add note**
5. Monitor progress via the stats bar and progress indicator
6. Export the completed log at any time using the **Export log** button

---

## Project Status

This is an early-stage project, actively under development. I am seeking feedback from maintenance technicians, MRO engineers, and quality inspectors on what features would make this genuinely useful in real operations.

**Open questions I'd love input on:**
- What information is most critical to capture per task?
- Would deferred defect tracking be useful?
- Should part numbers and serial numbers be loggable per task?
- Is offline functionality important for your work environment?
- What does your current paper or Excel process look like?

Feel free to open an [Issue](../../issues) or connect with me on [LinkedIn](https://www.linkedin.com/in/lydia-slippe).

---

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- No frameworks, no dependencies, no backend
- Deployable as a single `index.html` file

---

## Relevant Context

Enterprise maintenance management systems (AMOS, RAMCO, TRAX) already exist for large airlines, but they are expensive, complex, and out of reach for many smaller operators particularly in developing aviation markets. This project explores what a simple, accessible alternative could look like for technicians who still rely on paper and spreadsheets.

---

## Author

**Lydia Slippe**  
M.S. Electrical Engineering · Ohio University

B.Eng. Avionics · National Aerospace University ("Kharkiv Aviation Institute")

[LinkedIn](https://www.linkedin.com/in/lydia-slippe)

---

*Feedback from people in the field are welcome and actively sought. Every comment helps build something that actually solves real problems.*
