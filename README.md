# Brandon Photography — 50-photo gallery

## What is included

- 36 Unedited, 7 Lightly Edited, and 7 Fully Edited photos.
- Category filters, search by photo ID or original filename, and an order request form.
- Portrait and landscape images display without cropping. Original and edited versions have separate IDs.
- The supplied images are copied unchanged into `images/`. `photo-catalog.json` lists each ID, category, and original filename for reference. The displayed catalog is embedded in `index.html`.
- No online payments. Pricing is confirmed directly by email; no sample prices are advertised.

## Connect order requests

Order requests are configured for **brandonbyron624@icloud.com**.

After publishing, submit a test order. FormSubmit sends an activation email to this address the first time. Open it and activate the form, then submit another test and confirm it arrives. Email delivery has not been activated or tested against your mailbox yet.

Submissions are delivered through FormSubmit, which shows its own response page and may ask visitors to complete a CAPTCHA. See https://formsubmit.co/ for its service details and privacy information.

## Upload to GitHub Pages

1. Extract this ZIP.
2. Create a public GitHub repository, for example `brandon-photography`.
3. Upload `index.html`, `photo-catalog.json`, and the entire `images` folder to the repository root. Keep the folders together exactly as supplied. Do not upload only the ZIP.
4. Go to repository Settings → Pages. Choose Deploy from a branch, `main`, and `/ (root)`, then save.
5. Open the website link GitHub provides after deployment.
6. Test the form and activate it using the email described above.

You can also preview the site by opening `index.html` in your browser after extracting the ZIP. Keep the images folder next to it.

## Customize

- Name and text: search for `Brandon` in `index.html` and change the visible text as needed.
- Main image: edit `STORE.heroImage`. Currently it shows the lightly edited team-banner photo, IMG_8419.
- Photos: edit `STORE.photos` in `index.html`. The separate JSON catalog is a reference, not a live data source. For a new picture, copy it into the relevant images folder, add an entry with a unique ID, and set its width and height.
- Prices: optionally replace the null values in `PRICES` with dollar amounts. The order form then calculates an estimate. Final shipping and arrangements still happen directly with the customer.
- Print sizes: edit the format dropdown and corresponding keys in `PRICES` together.

Each email request includes the photo ID, category, original filename, format, quantity, customer email, preferred delivery, and notes. Contact the customer yourself to confirm pricing and delivery. Files placed in the published images folder will be publicly accessible; these are the images you uploaded, so keep any separate full-resolution delivery files private.
