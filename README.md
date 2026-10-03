# Daily Chuckle

One family-friendly joke for each day, with a punchline reveal, a midnight countdown, and a date picker that works across years, including leap years.

## Run the app

Open `index.html` in your browser. No installation, API key, or build is needed.

You can also serve the folder locally with `python -m http.server 8000`, then open http://localhost:8000.

## How daily jokes work

The app selects from a rotating collection of clean jokes using the calendar date. The same date always selects the same joke, and the app updates at local midnight. Jokes repeat when the collection cycles. Times follow the device's timezone.

## Files

- `index.html`: responsive interface and styles
- `app.js`: date selection, countdown, and punchline reveal
- `jokes.js`: joke collection

## Optional GitHub Pages

In the repository's Settings → Pages, select **Deploy from a branch**, choose **main** and **/(root)**, then save.
