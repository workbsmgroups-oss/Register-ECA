ENJOY CREATOR ACADEMY™
3 HOURS AI VIDEO CREATION MASTER LIVE CLASS
Static Landing Page Package

FILES
-----
index.html
confirmation.html
README.txt
assets/logo.png
assets/certificate-1.png
assets/certificate-2.png
assets/certificate-3.png
assets/certificate-4.png

DEPLOYMENT
----------
This is a pure static website using HTML5, CSS3 and Vanilla JavaScript ES6.
No build step, Node.js, framework or package installation is required.

You can deploy the folder directly to:
- Vercel
- Netlify
- GitHub Pages
- Any standard static web host

The site entry point is:
index.html

The informational confirmation page is:
confirmation.html


LOGO
----
The uploaded ECA logo has been added as:
assets/logo.png

To replace it later, keep the same filename/path:
assets/logo.png

The certificate files use these exact paths:
assets/certificate-1.png
assets/certificate-2.png
assets/certificate-3.png
assets/certificate-4.png

The certificate images are displayed without editing their content.


RAZORPAY
--------
Every enrollment CTA points to:

https://pages.razorpay.com/pl_TbVih3zQLJcgIZ/view#

Each payment CTA opens in a new browser tab with:
target="_blank"
rel="noopener noreferrer"

If you ever change the payment page, search index.html for:
https://pages.razorpay.com/pl_TbVih3zQLJcgIZ/view#

and replace the URL everywhere.


HERO VIDEO
----------
The hero currently uses a premium 9:16 placeholder and does NOT load a random video.

Inside index.html, find:
HERO YOUTUBE SHORTS VIDEO — REPLACE VIDEO_ID LATER

Replace the placeholder content with your own iframe, for example:

<iframe
  src="https://www.youtube.com/embed/VIDEO_ID"
  title="ECA AI Video Creation Master Live Class"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
  loading="eager"></iframe>

Do not change the surrounding .video-shell unless you want to redesign the video area.


STUDENT REVIEW VIDEOS
---------------------
The four requested YouTube embeds are already included:

1. https://www.youtube.com/embed/Iom0uEn4AiY
2. https://www.youtube.com/embed/Ld6iSbZVHXE
3. https://www.youtube.com/embed/CZJgdfQBS98
4. https://www.youtube.com/embed/JDRdID_DXOQ

They use:
- 9:16 responsive cards
- loading="lazy"
- allowfullscreen
- descriptive title attributes


COURSE DETAILS
--------------
Date: 17 September 2026
Time: 8:00 PM – 11:00 PM
Duration: 3 Hours
Mode: Live Online
Access: Mobile or Laptop
Price: ₹199
Original price shown: ₹6,999

The page uses "LIMITED BATCH" and does not claim a fake number of seats remaining.


RESPONSIVE DESIGN
-----------------
Desktop:
- Two-column hero
- Four-column review grid where space allows
- Two-column certificate grid

Tablet:
- Reduced columns for cards

Mobile:
- Video appears before hero copy
- Single-column learning/review/certificate layouts
- Full-width sticky floating enrollment CTA


ACCESSIBILITY / MOTION
----------------------
The page includes:
- semantic headings and sections
- descriptive image alt text
- FAQ aria-expanded state
- keyboard-friendly FAQ buttons
- prefers-reduced-motion support
- IntersectionObserver scroll reveals with a fallback


CONFIRMATION PAGE NOTE
----------------------
confirmation.html is an informational page.

It must NOT be interpreted as payment verification. Actual payment verification would require a configured payment redirect/integration or a trusted Razorpay webhook/backend flow.

The page explicitly communicates this limitation.


CUSTOMIZATION
-------------
Main visual variables are at the top of the <style> block in index.html:

--bg
--bg-2
--card
--card-2
--yellow
--yellow-2
--white
--muted
--border

The page is intentionally built without Bootstrap, Tailwind, React, Vue, Angular, jQuery or other frontend frameworks.


FINAL CHECK BEFORE DEPLOYMENT
-----------------------------
1. Upload the entire folder, including the assets folder.
2. Confirm index.html opens at the root URL.
3. Confirm assets/logo.png loads.
4. Confirm all four certificate images load.
5. Test all enrollment buttons and the floating CTA.
6. Test the four YouTube review embeds.
7. Replace the hero placeholder with your own 9:16 video when ready.
8. If your final domain is different, update the Open Graph URL in index.html.
