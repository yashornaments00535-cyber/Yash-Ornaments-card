# Yash Ornaments Digital Card (Vercel ready)

This is a simple, responsive one-page digital visiting card.

## Edit text and contacts
Open `src/data.js` in a text editor. Change the brand details, address, map link, Instagram URL and department contacts. Phone numbers should be in international format, digits only (example: `919876543210`). Put each department's number in `phone` and `whatsapp`.

## Add your jewellery photos
1. Put JPG/PNG/WebP photos into `public/gallery/`.
2. Add their exact filenames in the `gallery` list inside `src/data.js`, e.g. `gallery: ['necklace.jpg','ring.png']`.
3. Commit/push the changes to GitHub and Vercel will rebuild the website.

## Run locally
Install Node.js (LTS), then in this folder run:
- `npm install`
- `npm run dev`

## Publish on Vercel
1. Create/sign in to GitHub and create a repository.
2. Upload this project folder's files to the repository (or push using Git).
3. Sign in to Vercel using GitHub and click **Add New > Project**.
4. Import this repository. Vercel should detect Vite. Build command: `npm run build`; output directory: `dist`.
5. Click Deploy. The generated Vercel URL is the live digital visiting card.
6. To update, edit `src/data.js` or add gallery files, push to GitHub; Vercel redeploys automatically.

This starter does not include a secure online admin dashboard. Edits are made in the project files and published through GitHub. If a true browser-based editor is desired, a database/storage and admin authentication will need to be added.
