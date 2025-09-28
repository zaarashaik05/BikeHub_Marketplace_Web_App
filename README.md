# BikeHub_Marketplace_Web_App
BikeHub by Team Shenergy_Five is a smart two-wheeler marketplace where users can explore bikes, scooters, and EVs, apply smart filters, and compare models. Its uniqueness lies in a dedicated EV section, integrated showroom booking and Test drive, and direct seller inquiry, making buying and selling seamless and transparent.

1. Problem Statement:
Buying or selling a two-wheeler can be stressful:
Information is scattered across multiple websites.
Comparing models and calculating costs is confusing.
Dealers and individual sellers struggle to reach genuine buyers.
Personal Connection:
I’ve personally faced the hassle of browsing multiple sites, manually calculating EMI, and still not knowing if I was getting the right deal. BikeHub was born from this frustration — to make buying and selling
two-wheelers as simple and reliable as booking a cab.

2. Solution Overview
BikeHub is a web platform where users can browse, compare, and book two-wheelers while sellers manage inventory easily.
Core Features:
Listings with images, names, and prices.
Search & Filters: brand, price, mileage, fuel type.
Product Page: specifications, images, offers.
Compare Models: side-by-side comparison.
Finance Tools: EMI & fuel cost calculators.
Used Bikes: buy/sell options.
user accounts and favourites.
Upcoming Launches info.
Test Ride bookings
Extra Features: Favorites, reviews, price alerts, dealer dashboard.

3. System Architecture
Architecture Overview (Netlify Deployment)
Flow Summary:
Users interact with the Netlify-hosted frontend.
Frontend sends API requests to the Django REST backend.
Backend handles logic, database queries, and sends responses.


4. Technology Stack
Frontend: React + Tailwind CSS
Backend: Django REST Framework
Database: PostgreSQL
Deployment: Netlify (Frontend) + Backend API hosted on cloud platform (Render/Heroku)
Note: Netlify ensures fast and simple hosting for the frontend, while the backend APIs remain scalable and maintainable.

5. Core Logic
Search & Filters: Optimized database queries for fast results.
Comparison: Fetches specs from DB and aligns them in a side-by-side table.
EMI Calculator:
EMI = P × r × (1+r)^n / ((1+r)^n – 1)
Fuel Cost Calculator:
Annual Cost = (Distance ÷ Mileage) × Fuel Price

6. Data Handling
Input: Dealer/seller entries, manufacturer feeds, user uploads.
Storage: PostgreSQL for structured data.
Processing: Validation and indexing for fast search and accurate results.

7. Implementation Plan
1.Day 1: Setup environment, DB schema, user authentication.
2.Day 2: Listings, product pages, calculators.
3.Day 3: Compare tool, test ride booking, dealer dashboard.
4.Final Day: Testing, UI polish, prepare demo.

8. Performance & Validation
Testing: Unit tests + end-to-end flow.
Metrics: Page load time <1s, search response <1s, EMI/fuel calculations accuracy.
Validation: Pilot with a small set of dealers and users.

9. Deployment & Scalability
Frontend Deployment: Hosted on Netlify for fast, reliable access.
Backend Deployment: Django API hosted on cloud (Render/Heroku) with REST endpoints.
Scalability:
API scaling as user base grows.
Database indexing + caching for fast queries.
CDN for static assets.
Future: Mobile app, analytics dashboard, push notifications.
Conclusion
BikeHub addresses a real, relatable problem: simplifying how people buy, compare, and sell two-wheelers. It’s not just a marketplace — it’s a smoother, smarter experience for riders and sellers alike.
10. This is our front-end mvp prototype and you can check it's functionalities with the demo credentials which are at the bottom of the login page
    https://bikehub-marketplace.web.app

