MuseMotion Research Demo — Static HTML Package

Serve this folder over HTTP(S). Do not open index.html with file://.
Example: python3 -m http.server 8080 --directory html-package

This package is a browser-only product demo. Generation, queue states,
credits, metrics, failure/refund handling, and deletion are simulated in
localStorage. Uploaded photos are cropped in the browser and never leave
the device. No fal key or other production credential is included.

Adversarial QA helpers in the prompt field:
  [fail]  simulate provider failure and credit refund
  [block] simulate provider moderation and credit refund
