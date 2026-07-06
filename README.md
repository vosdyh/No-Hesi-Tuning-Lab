# No-Hesi-Tuning-Lab

A high-performance, [web](https://vosdyh.github.io/No-Hesi-Tuning-Lab/)-based setup builder for Assetto Corsa. Stop guessing—instantly calculate and export precision .ini parameters for drift, grip, and Vmax builds. Optimized for No Hesi SRP traffic, this tool brings competitive-grade tuning to your browser. Build your winning setup, save your presets, and dominate the traffic.

## Features

*   **100% locally hosted:** No external telemetry, tracking, or data collection.
*   **Precision Physics Engine:** Real-time calculation of Tyre PSI, Wheel Alignment, and Suspension Geometry based on chassis type.
*   **Target-Based Presets:** Switch instantly between Weaving, Vmax, Drift, and Track/Touge modes.
*   **Persistent Storage:** Retain custom tuning setups across browser refreshes via LocalStorage.
*   **Assetto Corsa Ready:** Generates compliant `setup.ini` code for immediate use in Content Manager.

## Usage & Installation

This application is a single-file static tool, making deployment and usage straightforward:

1.  **Direct Access (No Installation):** You can access and run the lab directly in your browser without downloading any files by visiting the project’s GitHub [page](https://vosdyh.github.io/No-Hesi-Tuning-Lab/).
2.  **Local Execution:** Alternatively, you can clone or download this repository to your local machine and open the `index.html` file directly in any modern desktop web browser (Chrome, Firefox, Edge, Safari).
3.  **Development Setup:** For the best development experience when modifying the interface, serve the file using a local web server, such as the "Live Server" extension in VS Code.

## Written With

This project was built using:

*   Claude-3.5-Sonnet
*   Gemini-1.5-Pro

## Disclaimer

This project is built strictly for personal educational and simulation practice. It contains no proprietary, copyrighted, or paid content from any commercial simulator developers or racing teams. All physics approximations are derived from open community tuning standards.

## Security & Verification

This project runs entirely on client-side code and does not collect, store, or transmit user data. You can verify the integrity of the file by inspecting the source code directly; there are no hidden scripts, trackers, or obfuscated payloads. You can verify the integrity of the release file via VirusTotal using the official SHA-256 fingerprint:

* **SHA-256 Hash:** `e53491c418b195b37a5a1f74de3a87ef9ba1b249c7d0b572835193a2568fe652`
* **Direct Report:** [View Live Scan Analysis](https://www.virustotal.com/gui/file/e53491c418b195b37a5a1f74de3a87ef9ba1b249c7d0b572835193a2568fe652)

## Technical Stack

This project is built entirely with standard web technologies, requiring no build steps or external dependencies:

*   **HTML5/Tailwind CSS:** Semantic structure, custom CSS variables, and responsive grid layouts optimized for desktop browsing.
*   **Vanilla JavaScript (ES6+):** Real-time mathematical calculation engine, state management, and LocalStorage persistence.
*   **Architecture:** Single-file static application.

## License
*© 2026 jibbles Tuning-Lab* 

All Rights Reserved.

Prepared for personal testing purposes only. This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

**You are free to:**
*   **Share:** Copy and redistribute the material in any medium or format.
*   **Adapt:** Remix, transform, and build upon the material.

**Under the following terms:**
*   **Attribution:** You must give appropriate credit, provide a link to the license, and indicate if changes were made.
*   **NonCommercial:** You may **not** use this material for commercial purposes. You are strictly prohibited from selling this software, or integrating it into paid products or services.

*For full license details, visit [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)*
