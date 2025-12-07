
Arundhati Threads - Netlify CMS enabled static site
--------------------------------------------------

Contents:
- index.html
- admin/index.html
- admin/config.yml
- images/ (placeholder model images + upiqr)
- content/products/... (sample product JSON files)

Important setup steps to enable Netlify CMS (admin panel):
1. Deploy this site to Netlify (you already have a site).
2. In Netlify dashboard -> Site settings -> Identity -> Enable Identity.
3. Under Identity settings, enable "Registration: Open" (or Invite users).
4. Then go to "Identity" -> Services -> Git Gateway -> Enable Git Gateway.
5. In Netlify -> Team -> Settings -> Access control, ensure your account has rights.
6. Back in the Netlify site, visit: https://<your-site>/admin to login with Netlify Identity.
7. Create new products using the CMS. New items will be saved to content/products and auto-deploy.

Contact:
- Admin email: contact@arundhatithreads.com

Notes:
- Replace placeholder images (images/model1.svg ...) with real product photos.
- Replace the UPI QR image in images/upiqr.jpg if needed.
- To enable direct Razorpay payment, add the Razorpay link into index.html where indicated.
