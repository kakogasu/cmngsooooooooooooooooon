How to use (v2)
----------
This version removed the subscribe form and message area, uses local time for countdown, and replaced the progress bar with a checklist that animates checks as the launch approaches.

Files:
- index.html
- styles.css
- script.js

To preview:
1. Unzip the archive.
2. Open index.html in your browser.
3. Edit the local launch time in script.js by updating the line: const launchLocalString = '2026-01-01T00:00:00';
   The string is parsed in your browser using your local timezone.

Notes:
- No backend or email saving included in this version per request.
- Checklist progress is simulated from a 90-day window before launch; adjust the window in script.js if needed.
