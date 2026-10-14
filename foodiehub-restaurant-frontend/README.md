# FoodieHub — Restaurant Ordering Website (Frontend Only)

A responsive, polished restaurant ordering interface built with React + Vite. Created as a frontend-only Cloud Computing course project; no backend or database is required.

## Features
- Responsive desktop, tablet and mobile layouts
- Food categories and live dish search
- Food cards with ratings, prices, tags and prep times
- Add-to-cart, quantity controls, subtotal and demo checkout
- Favourite/heart toggle
- Promo offer, delivery highlights and footer sections
- Toast notifications and empty-search/empty-cart states
- Attractive warm orange theme and food photography

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`). To make a production build:

```bash
npm run build
npm run preview
```

## Cloud Computing connection
This project demonstrates the **frontend/client layer** of a cloud-hosted web application. The static frontend can be deployed using a cloud hosting platform such as Vercel, Netlify, or an object-storage static website service. The current project intentionally uses sample menu data in the React code and does not process real orders or payments.

## Customise
- Edit menu items in `src/main.jsx` in the `dishes` array.
- Change theme colours and responsive layout in `src/styles.css`.
- Food images load from Unsplash, so internet access is needed for those photos and Google Fonts.

## Academic note
Project title: **FoodieHub — Restaurant Ordering Website**  
Subject: **Cloud Computing**  
Scope: **Frontend / user interface only**
