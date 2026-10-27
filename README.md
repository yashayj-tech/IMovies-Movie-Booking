# IMovies — College Demo

A ready-to-run **frontend-only** movie booking demonstration built with HTML, CSS and JavaScript.

## Run in PyCharm (Windows)

1. Download and extract `IMovies_College_Demo.zip`.
2. Open PyCharm → **File → Open** → select the extracted `imovies_demo` folder.
3. In the Project panel, right-click `index.html` → **Open in → Browser** (wording may differ by PyCharm version). Alternatively, open `index.html` directly in Chrome or Edge using File Explorer.
4. The movie website opens. **No pip, npm, Node.js, MongoDB or Python setup is required.**

## How to demonstrate

1. Browse or search the six sample movies.
2. Click **Book Now**, choose a date and showtime.
3. Select available seats, enter a name and email, and confirm.
4. See the confirmation and booking ID.
5. Open **My Bookings** to see the saved booking.
6. Refresh the page: the booking remains in this browser.
7. Try the same show again: reserved seats appear unavailable.
8. Cancel a booking to release its seats.

## Files

- `index.html`: page structure and booking dialog
- `style.css`: responsive dark theme
- `app.js`: movies, seat selection, booking logic and localStorage persistence

## Important limitations

- This is **not** the MERN application described in the original project specification.
- There is no React, Express, MongoDB, JWT, login, server or shared real-time inventory.
- Data is saved in **this browser's localStorage only**; clearing site data erases it. Other browsers/devices do not share bookings.
- Payments and ticket issuance are simulated; do not use it for real customers.
- Movie titles and showtimes are fictional sample data.

## Suggested viva explanation

“IMovies is a browser-based movie ticket booking demonstration. Users browse movies, select a showtime and seats, and receive a booking confirmation. JavaScript validates the booking and localStorage retains records across page refreshes in the same browser. This prototype can later be extended with a Node.js/Express backend and MongoDB for secure multi-user bookings.”
