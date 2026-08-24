# Australian First Aid Instructor Buddy — Test Build

This repository is a separate frozen test wrapper. It does not modify the development repository.

## Offline use

1. Open the GitHub Pages test site once while online.
2. Allow the page to finish loading completely.
3. On iPad/iPhone, use **Share → Add to Home Screen**.
4. Launch the installed app from the Home Screen.
5. After the first successful online launch, the app is designed to continue working from its local service-worker cache when offline.

The wrapper is pinned to development snapshot `84970441bb7cad59eb1ad1d41ff6514e11248146`, so later changes to the master build do not intentionally flow into this test snapshot.

Tester activity is local to the tester's device/browser storage and does not write to the development repository.