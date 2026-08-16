# Cleaning Tracker — app icon  

## What to do
1. Upload these files to the cleaning-tracker2 repo, in the SAME folder as
   cleaning_tracker_v2.html:
      icon-32.png, icon-180.png, icon-192.png, icon-512.png,
      icon-maskable-512.png, manifest.webmanifest
2. Edit cleaning_tracker_v2.html on GitHub (pencil icon), paste the lines from
   HEAD-SNIPPET.html inside <head> just after <title>, and commit.
3. On each device: REMOVE the old home screen shortcut, reload the page in the
   browser, then Add to Home screen again. Old shortcuts keep the old icon
   forever — re-adding is what picks up the new one.

## Note on the manifest
"start_url" points at cleaning_tracker_v2.html. If you ever rename that file
to index.html, update start_url to "./index.html" to match.

## iPhone / iPad
iOS uses apple-touch-icon (icon-180.png), not the manifest icons. Both are
included, so it works on iOS and Android.
