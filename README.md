# Little Lemon

A React restaurant website with menu highlights, testimonials, an about page, and a table reservation interface.

## Features

- Restaurant landing page with specials and testimonial carousels.
- Navigation between home, about, reservations, order, login, and confirmation pages.
- Reservation fields for date, party size, contact details, and seating preferences.
- Date-based sample availability generated locally.

## Project scope

This is a frontend demonstration. `src/bookingsAPI.js` generates sample time slots and its submit helper returns success without storing a reservation. The booking button routes to a confirmation page; there is no production reservation service or implemented login backend in this repository.

## Run locally

Install Node.js and npm, then:

```bash
git clone https://github.com/muhammadfirdous/little-lemon.git
cd little-lemon
npm ci
npm start
```

Open `http://localhost:3000`.

## Build

```bash
npm run build
```

Create React App writes the production files to `build/`. A deployment host must support the application's client-side routes.

## Stack

React, React Router, React Responsive Carousel, Create React App, and CSS.

## Project layout

| Path | Purpose |
| --- | --- |
| `src/components/pages/` | Top-level pages |
| `src/components/sections/` | Restaurant sections and reservation form |
| `src/components/Routing.js` | Route definitions |
| `src/bookingsAPI.js` | Local sample booking helpers |
| `src/assets/` | Food images, logos, and interface assets |
| `public/` | Static application shell |

[More projects by Muhammad Firdous](https://github.com/muhammadfirdous)
