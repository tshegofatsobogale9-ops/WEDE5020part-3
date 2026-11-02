# Segwaelana Fresh Basket - Bakery Website
### WEDE5020 Part 3 Final Project | Segwaelane, Rustenburg



## 1. Project Overview
Segwaelana Fresh Basket is a local bakery website built for a real business in Segwaelane, Rustenburg. We bake fresh bread daily at 5AM. The site is optimized for local SEO "bakery Rustenburg" and "fresh bread Segwaelane near me".

**Business Goal:** Attract customers searching "bakery Rustenburg" and allow them to enquire about costs and availability.

**Products:**
- Brown Bread - R18
- White Bread - R16 (image fixed with brightness filter)
- Whole Wheat - R20
- Cupcakes - R25 for 6
- Birthday Cakes - R350

Open: Mon-Sat 6AM-6PM, Sun 7AM-1PM

## 2. Part 3 Features Implemented

### Technical SEO (Marks)
- `sitemap.xml` with all 5 pages
- `robots.txt` allowing all pages
- Meta tags: description, keywords, author, viewport on all pages
- Alt attributes: "Brown Bread R18 Segwaelana Bakery Rustenburg" (local keywords)
- `loading="lazy"` on all images
- Single external CSS `style.css` and JS `script.js`
- Semantic HTML5: header, nav, main, footer, hero
- Google Maps backup embedded for Technical SEO

### JavaScript Enhancements (Part 3)
- **Dynamic Content:** Product list loaded from `productsData` array in JS (not hardcoded in HTML)
- **Search Filter:** `searchProducts()` on services.html
- **Animations:** `fadeIn` keyframes, `card:hover` scale, accordion slide
- **Interactivity:** 
    - Lightbox for images (click to enlarge)
    - Modal for Today's Offer
    - Accordion FAQ
    - Dynamic greeting based on time of day
- **Form Enhancements:**
    - HTML5: required, type=email, pattern=[0-9]{10}, minlength
    - JavaScript validation: name 3+ chars, message 15+ chars, phone 10 digits
    - AJAX simulation with setTimeout
    - Compiled email: `To: info@segwaelana.co.za` logged to console for POE page 17
    - **Loop + Back:** After sending, buttons appear: Loop (reset form) and Back to Home / Back to previous page

### Forms
1. **contactUs.html:** General Message to Mrs Dlamini - Sends to info@segwaelana.co.za - Email compilation + AJAX + Loop + Back + Google Map
2. **enquiry.html:** Cost & Availability - Asks for Product type, Quantity, Delivery date - Validates phone 10 digits

## 3. File Structure
