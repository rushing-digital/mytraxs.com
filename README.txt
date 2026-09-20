MYTRAXS.COM LANDING PAGE
=========================

This folder contains the complete static landing page for MyTraxs.com.

FILES
-----
index.html              Main landing page + acquisition contact form
css/styles.css          Site styling
assets/favicon.svg      Browser favicon
assets/og-image.svg     Social sharing image

CONTACT FORM
------------
The form currently posts through FormSubmit to:
    hello@mytraxs.com

If you want inquiries sent to a different address, change the form action in
index.html from:
    https://formsubmit.co/hello@mytraxs.com

and change the direct email link from hello@mytraxs.com to your preferred address.

The first submission to a new FormSubmit recipient may require an email
confirmation from FormSubmit before delivery is enabled.

The _next field currently points to:
    https://mytraxs.com/?submitted=1#inquire

Change that if the site will use a different production URL.

DEPLOYMENT
----------
This is a static HTML/CSS site and can be uploaded to most hosting providers,
Cloudflare Pages, Netlify, Vercel, GitHub Pages, or a standard web host.
