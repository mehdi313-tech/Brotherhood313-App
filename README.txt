BROTHERHOOD 313 — WEBSITE + INSTALLABLE ANDROID STARTER

Included: store homepage, sample products, category filters, cart, quantity controls, subtotal, WhatsApp order-message builder, contact links, PWA install files.

IMPORTANT: This is a first starter, not yet a complete online store backend. Product names/prices are examples. The WhatsApp and Instagram links need configuring in app.js. Keep a personal phone number private unless you deliberately want it public; a separate business number is safer.

Not connected yet: customer accounts, shared order history, secure admin panel, live inventory, notifications, online payments. These require a secure backend and more setup. Never collect/store card numbers yourself.

GITHUB PAGES SETUP:
1. Extract this ZIP.
2. Upload ALL files from this folder into the ROOT of your GitHub repository, replacing the old index.html and adding styles.css, app.js, manifest.json, service-worker.js and icon.svg.
3. Commit changes.
4. Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Wait a few minutes, then open your GitHub Pages URL.
6. On Android Chrome, open the site, tap the three-dot menu, and choose Install app or Add to Home screen if available.

To set WhatsApp: in app.js change whatsappNumber:"" to your business number in digits only, e.g. "91XXXXXXXXXX".
To set Instagram: change instagramUrl:"" to the full profile URL.
To edit sample products/prices: change the products array in app.js.
Keep all files together. Do not upload only the ZIP file to GitHub Pages.
