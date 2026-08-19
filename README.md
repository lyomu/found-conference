# FOUND — Faith & Sexuality Conference 2026

Official landing page and registration portal for the **Faith & Sexuality Conference 2026**, hosted by **FOUND**.

---

## Overview

The **Faith & Sexuality Conference 2026** is a dedicated gathering exploring Biblical truth, pastoral wisdom, and compassionate ministry surrounding faith and human sexuality.

This repository contains the static web pages, design assets, and conversion tracking integrations for the event.

---

## Repository Structure

```text
├── index.html                           # Main conference landing page
├── thank-you.html                       # Post-registration confirmation page
├── faith-sexuality-conference-2026.html  # Standalone/mirrored landing page
├── assets/                              # Images, logos, and speaker photos
└── README.md                            # Project documentation
```

---

## Features

- **Modern & Responsive Design**: Crafted with clean semantic HTML5 and vanilla CSS with fluid typography and smooth scroll animations.
- **Conversion Tracking**:
  - Google Tag Manager / GA4 integration.
  - Meta Pixel tracking (`PageView` & `CompleteRegistration` custom/standard events).
- **Fast & Lightweight**: Zero external JavaScript framework dependencies for optimal load times.
- **Security & Privacy**: Pre-configured with secure Content Security Policies (CSP), referrer policies, and resource hints.

---

## Local Development & Preview

To preview the landing page locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lyomu/found-conference.git
   cd found-conference
   ```

2. **Open with any local server or directly in a browser:**
   - Using VS Code Live Server extension, or
   - Using Python:
     ```bash
     python -m http.server 8000
     ```
   - Then navigate to `http://localhost:8000/` in your browser.

---

## License

© 2026 FOUND Africa. All rights reserved.
