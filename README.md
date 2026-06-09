# Galvatron Finder

Galvatron Finder is a personal LAN utility for quickly finding the current IP address of my Galvatron device, especially when I am in VR and opening a command prompt to run `ipconfig` is inconvenient. It is published as-is for my own workflow and should not be treated or presented as a general public security or network scanner.

The newer `GalvatronFinder2.html` version is built around concurrent browser-based subnet scanning, async JavaScript, `AbortController` timeouts, dynamic DOM updates, a mobile/VR-first responsive UI, self-contained HTML/CSS/JS, HUD-style CSS design, accessible status messaging, and no build step.

## Files

- `GalvatronFinder2.html` - Current HUD-style version, designed for the normal VR/mobile workflow.
- `GalvatronFinder.html` - Earlier version included for continuity.

## GitHub Pages

- [GalvatronFinder2.html](https://rolex20.github.io/galvatron-finder/GalvatronFinder2.html)
- [GalvatronFinder.html](https://rolex20.github.io/galvatron-finder/GalvatronFinder.html)

## Use

Open one of the GitHub Pages links from a browser on the same local network as the Galvatron device. The page probes the configured local subnet range and reports the first matching device endpoint it can confirm.

Because this is a browser-only LAN helper, results depend on the browser, local network, device availability, and CORS behavior from the target endpoint.

## Rights

Copyright (c) 2026 rolex20. All rights reserved.

This repository is publicly visible only so the app can be served through GitHub Pages on a GitHub Free account. The source code is provided for personal hosting/reference only. No permission is granted to copy, modify, redistribute, sublicense, sell, or reuse this code or any derivative work without explicit written permission from the author.
