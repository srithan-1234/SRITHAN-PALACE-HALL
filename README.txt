=============================================================
 SRITHAN GRAND PALACE HALL - ONLINE BOOKING WEBSITE
 Kurnool | Wedding Hall Booking Management System
=============================================================

HOW TO RUN
----------
1. Unzip this file.
2. Open "index.html" in any web browser (Chrome recommended).
   No server or installation needed - it works offline.
3. Bookings are saved in the browser (localStorage) like a demo database.

PAGES
-----
- index.html       : Home page with hall showcase, gallery and photos
- halls.html       : View halls, capacity, price, facilities, live availability
- book.html        : Booking form (checks double-booking automatically,
                     takes 25% advance payment record)
- my-bookings.html : Customer enters email -> sees bookings + payment details
- admin.html       : Admin panel
                     Username: admin
                     Password: admin123
                     -> confirm / cancel reservations
                     -> set hall maintenance
                     -> revenue report

DATABASE
--------
database/schema.sql  : Full MySQL schema (customers, halls, bookings,
                       payments tables) with sample data for Kurnool venue.
                       Import into MySQL/XAMPP when moving to production.

FEATURES
--------
- Real wedding hall photos (8 images included)
- Availability checking by date & time slot
- Double-booking prevention
- Advance payment (25%) + balance tracking
- Admin confirmation workflow (Pending -> Confirmed / Cancelled)
- Mobile responsive design

IMAGES
------
Photos are for demonstration purposes only. Replace images/
with actual photos of Srithan Grand Palace Hall before going live.

(c) 2026 Srithan Grand Palace Hall, Kurnool
