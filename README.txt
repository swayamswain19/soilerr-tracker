SOILERR ORGANICS — OFFLINE-FIRST TRACKER

Files:
- index.html       Main app
- manifest.json    Installable PWA settings
- sw.js            Offline cache/service worker

IMPORTANT:
1. Open the app once while online.
2. Install it to the phone home screen when prompted.
3. After that, the app shell works offline.
4. Data is stored locally in the browser/device using localStorage.
5. Staff do NOT need individual accounts.
6. Data does NOT automatically sync between different phones.

Recommended future architecture:
- Staff app: offline-first local storage.
- Optional sync when internet returns: Supabase/Firebase.
- Customer verification: public read-only batch page + QR code.
