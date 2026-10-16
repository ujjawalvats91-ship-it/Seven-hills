Seven Hills Wai - landing page
==============================
index.html        page structure (HTML)
css/style.css     all styles
js/script.js      all scripts (hero video scrub, carousel, map, amenities, forms...)
images/map.jpg    satellite map used in the Location section

How to use
- Open index.html in a browser, or upload the whole folder to your hosting.
- Keep the folder structure as it is.
- GSAP animations load from the cdnjs link inside index.html (needs internet).

Photos to add (drop your files in these folders, keep the same file names)
- images/amenities/  rooftop-bar.jpg, gym.jpg, horse-arena.jpg, pool.jpg, more.jpg   (Amenities for Modern Living - 5 cards)
- images/nature/     misty-hills.jpg, hills-lake.jpg, waterfall.jpg, pandavgad-fort.jpg (Nature Attraction - 4 cards)
- images/plots/      plot-1625.jpg, plot-3250.jpg, plot-3600.jpg, plot-5000.jpg          (Investment Options - 4 cards)
  Each is a real <img> tag in index.html. Until a photo exists, the card shows its colour/artwork placeholder.
  To use a different file name, change the src="" of that <img> in index.html.

Bank logos (Banking Tie-Ups)
- images/logos/ idbi.svg, sbi.svg, hdfc.svg, pnb.svg  (simplified SVG marks - replace with the banks' official SVGs if you have them, same file names)

Other things you fill in
- Hero video:  index.html  -> <video id="scrub-video" src="...">
- Typeform link for the arrow buttons: js/script.js -> TYPEFORM_URL
- Section background photos still set in css/style.css (e.g. background-hills.jpg for Amenities, hero.jpg): put them in images/ and update the url('...') paths.
