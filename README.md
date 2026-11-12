# HackMate

Responsive React + Vite frontend concept for finding hackathon teammates and forming student project teams.

## Run locally
1. Install Node.js 18+.
2. In this folder run `npm install`.
3. Run `npm run dev` and open the localhost URL printed by Vite.

## Features
- Discover student builders by role, skills, interests, college and keywords.
- Filter by role, work mode and must-have skill.
- Profiles include branch, academic year, CGPA, skills, interests, project count, availability and weekly commitment.
- Save builders and send/withdraw interest; view saved and interested lists.
- Detailed profiles with collaboration preferences.
- Edit a builder profile with selectable skills, domains and availability.
- Publish local team openings with role, project description, skills needed, work mode, time commitment and target hackathon.
- Hackathon discovery cards with dates, formats, themes and prize pools.
- Responsive layout for desktop and mobile.

## Demo limitations
This is frontend-only. Profiles and hackathon listings are illustrative sample data. Saved profile and builder profile data are stored in browser localStorage; posted openings are held in current page state. There is no real authentication, backend, messaging, team membership, event registration, verification or live hackathon feed. Before production, add secure accounts, a database, consent/privacy controls, reporting/blocking, moderation and verified student identity.
