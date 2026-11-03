<h1 align="center">GaŤe Parking</h1>

<p align="center"><b>Corporate parking made simple: find a free spot, reserve it and park, all in the browser.</b></p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white">
  <img alt="Express" src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white">
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white">
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white">
  <img alt="Render" src="https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=black">
</p>

We are **team 3**, a student team building GaŤe Parking as our UUN semester project: a web app for a private company parking lot used by employees and administrators.

## What it does

- **Live availability**: see free, reserved and occupied spots per parking lot before you travel.
- **Vehicles**: register your car with its plate, engine type (combustion / electric) and size.
- **Reservations**: book a spot that fits your vehicle (EV and size rules apply), view, edit or cancel it.
- **Parking sessions**: start and end parking, see your history and pay (mock payment, no real money).
- **Notifications**: in-app reminders before a reservation starts or ends, or when it is cancelled.
- **Administration**: manage parking spots, edit or delete any reservation, review the audit log.

Automatic gate access with license plate recognition, live EV charger status and tariffs, and occupancy analytics are planned as stretch goals ([scope decision](https://github.com/gate-parking-team3/GaTe-parking/blob/main/docs/SCOPE.md)).

**Live demo:** coming soon.

## Explore the project

| | |
| --- | --- |
| Code | [gate-parking-team3/GaTe-parking](https://github.com/gate-parking-team3/GaTe-parking) |
| Overview, user stories, setup | [README](https://github.com/gate-parking-team3/GaTe-parking#readme) |
| How we work | [CONTRIBUTING](https://github.com/gate-parking-team3/GaTe-parking/blob/main/CONTRIBUTING.md) |
| Docs (scope, work breakdown, deployment) | [docs/](https://github.com/gate-parking-team3/GaTe-parking/tree/main/docs) |

## Tech stack

React + TypeScript (Vite) frontend, Node.js + Express + TypeScript backend, MongoDB with Mongoose. Tested with Vitest, Testing Library and Supertest; CI on GitHub Actions. Hosted on Vercel (frontend), Render (backend) and MongoDB Atlas (database).

## Team

| User story | Owner |
| --- | --- |
| 1. Display available parking spots | Vojta |
| 2. History of parking records | Matěj |
| 3. Start and end active parking | Šimon |
| 4. Reserve a parking spot | Honza Hubal |
| 5. Register vehicle | Andrej |
| 6. Deletion of reservation | Ludmila |
| 7. View active parking reservation | Jan Heller |
| 8. Notifications | Leo |
| 9. Pay for a parking session | Daniel Artur Hüttl |
| 10. Create a new parking spot with audit log | Rayhon |
| 11. Edit an upcoming reservation | Oleg Cingarski |

<p align="center"><sub>MIT licensed · Built by team 3</sub></p>
