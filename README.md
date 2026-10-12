# FoodBridge — Surplus Food Redistribution Routing System

A responsive front-end hackathon prototype built with HTML, CSS, and vanilla JavaScript.

## Run it
1. Extract `FoodBridge_Prototype.zip`.
2. Open the `FoodBridge_Prototype` folder.
3. Double-click `index.html` to open it in Chrome or Edge.
   - Optional: open the folder in VS Code and use the Live Server extension.

No npm install or backend setup is required.

## Demo features
- Dashboard with impact stats and illustrative route map.
- Create surplus-food listings with quantity, category, donor, pickup area, deadline, storage condition, and notes.
- Search and filter donations.
- Claim available donations and mark claimed donations as delivered.
- Demo route recalculation prioritizing available donations.
- Impact report export to CSV.
- Responsive desktop/mobile layout.

## Important prototype limitations
- Donation records are stored in JavaScript memory and reset when the page is refreshed.
- The map and travel distances are illustrative, not live GPS/navigation.
- There is no real login, server, database, notification, or NGO integration.
- Environmental impact figures are demo estimates and should be labelled as such during the presentation.

## Suggested next steps
1. Add Node.js + Express backend and PostgreSQL/MySQL database.
2. Add donor, NGO, and volunteer accounts with role-based access.
3. Integrate OpenStreetMap + OSRM for real route estimates, with address/geocoding validation.
4. Add food-safety checks: preparation time, storage temperature, allergens, expiry/pickup deadline, and recipient confirmation.
5. Deploy the front end for judging and prepare a 2–3 minute demo script.
