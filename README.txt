CHIDIOGO UKWU PORTFOLIO: HOW TO USE
===================================

Upload the whole folder contents to your host (Netlify, Vercel, GitHub Pages, cPanel).
Keep this structure exactly:

  index.html                main page
  404.html                  page-not-found page
  work/                     four case study pages
  images/                   all photos (JPEG + WebP)
  og-image.jpg              link preview image (WhatsApp, LinkedIn, X)
  favicon.png, icon-192.png, icon-512.png, apple-touch-icon.png, site.webmanifest
  sitemap.xml, robots.txt

ADD YOUR CV
  Put your CV in the same folder as index.html and name it:  Chidiogo-Ukwu-CV.pdf
  (the Download CV buttons point to that name)

BEFORE YOU GO LIVE
  1. Replace YOURDOMAIN.com in sitemap.xml and robots.txt with your real domain.
  2. In index.html, change og:image and twitter:image from  og-image.jpg
     to the full address, e.g.  https://yourdomain.com/og-image.jpg
     (do the same in the four files inside work/, where it is ../og-image.jpg)
  3. Replace the placeholder "Kind words" quotes in index.html with real testimonials
     (search for "placeholder"), with each person's permission.
  4. Confirm these facts with Chidiogo: the $2K bi-monthly figure, Our Haven dates and
     the month of the promotion to Operations Manager.
  5. Check the photo captions in the "In the field" section (search for "Pyrich Group event").
  6. Optional: contact form service. In index.html find  var FORM_ENDPOINT=''
     and paste your Formspree link, e.g. https://formspree.io/f/xxxxxxxx
     Left empty, the form opens the visitor's email app with WhatsApp and copy fallbacks.

PHOTOS STILL TO REPLACE
  UburuHealth cards (Search adoption, Customer retention) use stock photos from Unsplash.

TEST LOCALLY
  Double-click index.html. Fonts and stock photos need an internet connection.
