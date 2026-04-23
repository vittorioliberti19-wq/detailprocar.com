# ProCar images

Images served here come from the Google Drive sync pipeline:

1. Community manager fills Google Form with car photo + metadata
2. Mac Mini cron downloads photo from Drive, resizes to 1200px WebP
3. Commits to this folder + updates ../procar.json

Until the pipeline runs, the web falls back to a gradient placeholder
(see the CSS `.procar-photo-placeholder` class in index.html).
