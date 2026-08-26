📘 TechCompanion v5.3 — README
🚀 Overview
TechCompanion is a cross‑platform mobile app designed to simplify device setup, barcode scanning, and AI‑generated guides.
Built with React + Capacitor, it supports Android and iOS, offering fast scanning, personalised setup instructions, and saved guides.

🎯 Why This Project Exists
TechCompanion was built to solve a real engineering workflow problem:
technicians often need fast device identification, setup instructions, and repeatable guides.
This app demonstrates:

Full‑stack mobile development

Cloud API integration

ML‑powered barcode scanning

AI‑generated documentation

Production‑ready engineering workflows

It’s both a real tool and a portfolio showcase of engineering + software capability.

📂 Repository Structure
Code
techcompanion-v5.3/
│
├── builds/                 # Build artifacts (Android/iOS)
├── demo/                   # Demo HTML + showcase assets
├── docs/                   # Documentation (reports, guides, UI showcase)
├── screenshots/            # App screenshots for store listings
├── src/                    # React application source code
│
├── LICENSE                 # MIT License
└── README.md               # Project overview (this file)
📄 Documentation
All project documentation is stored in the /docs folder.

Core Documents
TechCompanion-Final-Report.docx

TechCompanion-Presentation.pptx

TechCompanion-UI-Showcase.docx

TechCompanion-UI-Walkthrough.pptx

TechCompanion-PlayStore-Guide.docx

TechCompanion-Android-Build-Guide.docx (if uploaded)

These cover:

Full project analysis

UI design and walkthrough

Android build instructions

Play Store submission guide

Presentation slides

Technical documentation

📱 Features
🔍 Barcode scanning (ML Kit)

📦 Device lookup

🤖 AI‑generated setup guides

💾 Saved guides

🎨 Dark/Light theme

💳 Pro subscription (RevenueCat)

⚡ Cloudflare Worker API proxy

🛠 Tech Stack
React

Capacitor 6

Android SDK 34

iOS 17

ML Kit Barcode Scanning

RevenueCat

Cloudflare Workers

GitHub Actions CI/CD

🧩 Architecture & Tech Decisions
This section shows your engineering reasoning — a big plus for recruiters.

React + Capacitor  
Chosen for cross‑platform speed and native plugin support without maintaining two codebases.

ML Kit Barcode Scanning  
Provides fast, reliable scanning with native performance.

Cloudflare Worker API Proxy  
Used to secure API keys and provide a lightweight serverless backend.

RevenueCat  
Simplifies subscription management across Android and iOS.

GitHub Actions CI/CD  
Automates builds and ensures consistent deployment pipelines.

🖼 Screenshots
(Add your images into /screenshots and reference them here)

Code
![Home Screen](screenshots/home.png)
![Barcode Scanner](screenshots/scanner.png)
![Device Details](screenshots/device-details.png)
![AI Guide](screenshots/ai-guide.png)
![Saved Guides](screenshots/saved-guides.png)
📦 Building the App
Android
See:
📄 /docs/TechCompanion-Android-Build-Guide.docx

iOS
See:
📄 /docs/TechCompanion-Final-Report.docx (iOS section)

🧪 Testing
Physical device testing

Internal Play Store track

TestFlight (iOS)

Automated CI builds via GitHub Actions

📜 License
This project is licensed under the MIT License.

👤 Author
Lee  
Leicester, UK
Embedded & Software Engineering
