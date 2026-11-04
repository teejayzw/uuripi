Uripi
Photo-based location and nearby-places finder, packaged as an installable web app (PWA).
Files
index.html – the app
manifest.webmanifest – name, icons, theme, home-screen shortcuts
sw.js – service worker (offline app shell, map-tile cache)
icons/ – 192, 512, maskable and Apple touch icons
Run / host
PWAs must be served over HTTPS (localhost also works for testing).
Quick test:   python3 -m http.server 8080   then open http://localhost:8080
Free hosting: Netlify, Vercel, Cloudflare Pages, GitHub Pages (upload this folder as-is).
Install
Android / desktop Chrome and Edge: "Install app" button in the header, or the browser menu.
iPhone / iPad (Safari): Share, then Add to Home Screen.
App stores
Once the site is live on HTTPS, go to https://www.pwabuilder.com, enter the URL and generate packages for:
Google Play (Android, Trusted Web Activity)
Microsoft Store
Apple App Store (Xcode project, needs an Apple Developer account)
<img width="512" height="512" alt="maskable-512" src="https://github.com/user-attachments/assets/2c2cddd5-8aa1-468b-9e62-8cdfeddb6615" />
<img width="512" height="512" alt="icon-512" src="https://github.com/user-attachments/assets/84472ab2-1186-4fdc-995b-3ab80c518034" />
<img width="192" height="192" alt="icon-192" src="https://github.com/user-attachments/assets/c129c9b3-a90a-4fa9-9632-c6be7679c977" />
<img width="32" height="32" alt="favicon-32" src="https://github.com/user-attachments/assets/8fe56744-d7dd-4481-9efb-f794abd7af78" />
<img width="180" height="180" alt="apple-touch-icon" src="https://github.com/user-attachments/assets/c70c3c7d-342e-4393-8289-7f5e6641ba2f" />
