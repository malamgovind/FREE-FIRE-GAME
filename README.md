# Free Fire Max - Interactive Web Experience & Login Flow

A responsive, interactive frontend web project recreating the **Free Fire Max** game launch sequence and authentication interface using pure HTML5, modern CSS3, and vanilla JavaScript.

---

## 🎮 Overview

This project provides an authentic, browser-based simulation of the Free Fire Max mobile experience. Users navigate through the complete game initiation sequence—from the Google Play Store installation card to the animated splash screen, interactive loading progress bar, terms dialog, and the main game title screen featuring a fullscreen video background with polished Facebook and Google authentication sub-pages.

---

## ✨ Features

- **Full-Viewport Responsive Layout (`100vw` × `100vh`)**:
  - Replaces rigid, fixed-pixel containers with a modern fluid layout.
  - Fully responsive across mobile smartphones, tablets, laptops, and ultra-wide desktop monitors.
  - Utilizes modern Flexbox and CSS Grid with custom viewport units and clamp typography.

- **Multi-Stage Game Launch Flow**:
  1. **Play Store Preview (`.one`)**: Modern app showcase card with game metadata and an interactive "Play" button.
  2. **Cinematic Splash Screen (`.two`)**: Fullscreen animated game splash screen driven by smooth CSS keyframes (`govind`).
  3. **Simulated Loading Screen (`.three`)**: Dynamic progress bar advancing from 0% to 100% with real-time percentage counter and gameplay guide tips.
  4. **Terms & Conditions Dialog (`.four`)**: Centered glassmorphism modal with Terms of Service & Privacy Policy review.
  5. **Main Game Title Screen (`.five`)**: Fullscreen looping background video (`video02.mp4`), game branding header, ToS & age confirmation checkboxes, and multi-provider sign-in options (Facebook, Guest, Google).

- **Modern Authentication Sub-Pages**:
  - **Facebook Login & Registration (`.six` & `.seven`)**:
    - Authentic Facebook brand aesthetic (`#1877F2`) with dark theme styling.
    - Polished input fields with focused border glows, "or" divider, and green "Sign Up" button (`#42B72A`).
    - Dedicated registration sub-page with responsive name inputs and custom selectable gender tiles.
  - **Google Log In & Sign In (`.eight` & `.nine`)**:
    - Material Design card layout featuring centered Google branding.
    - Segmented tab bar allowing instant switching between "Log In" and "Sign In".
    - Clean dark outlined input fields, password confirmation, and styled action buttons.
  - **Close Controls**: Responsive dismiss buttons (`#close01`, `#close02`, `.x-mark01`, `.x-mark02`) returning smoothly to the game title screen.

---

## 🛠️ Technologies Used

- **HTML5**: Semantic markup, video integration, and form controls.
- **CSS3**: Modern layout (Flexbox & CSS Grid), CSS custom properties (variables), backdrop filters, keyframe animations, and media queries.
- **JavaScript (ES6+)**: Event-driven UI state machine managing screen switching, loading bar intervals, and checkbox-dependent button activation.
- **Font Awesome (v6.7.1)**: Scalable vector icons for social media branding and UI controls.

---

## 📂 Project Structure

```text
FREE-FIRE-GAME-main/
│
├── 001_index.html       # Primary HTML document containing all 9 flow sections
├── 001_index.css        # Responsive full-viewport stylesheet with modern UI styling
├── 001_index.js         # Client-side JavaScript handling animations and view transitions
├── README.md            # Comprehensive project documentation
│
├── 1.jpg                # Google Play store game poster/cover
├── 2.jpg                # Free Fire splash screen banner
├── 3.jpg                # Gameplay loading background
├── 4.jpeg               # Additional visual asset
├── z_google.png         # High-resolution Google brand asset
└── video02.mp4          # High-definition looping video background for the game title screen
```

---

## 🚀 How to Run Locally

### Option 1: Direct File Open
Simply double-click `001_index.html` or right-click and open it with any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

### Option 2: Local HTTP Server (Recommended)
Running through a local web server ensures seamless loading of all video and media assets:

#### Using Python 3:
```bash
# Navigate to the project folder
cd /path/to/FREE-FIRE-GAME-main

# Start a local HTTP server on port 8000
python3 -m http.server 8000
```
Open your browser and navigate to `http://localhost:8000/001_index.html`.

#### Using Node.js (via `npx serve`):
```bash
npx serve .
```

#### Using VS Code Live Server:
1. Open the project folder in VS Code.
2. Right-click `001_index.html` and select **"Open with Live Server"**.

---

## 💡 Best Practice Note

This project is built for frontend design demonstration and educational UI/UX modeling. In real-world production web and game applications, third-party authentication (Google & Meta) is implemented using official **OAuth 2.0 / OpenID Connect SDKs** (such as [Google Identity Services](https://developers.google.com/identity) and the [Facebook JavaScript SDK](https://developers.facebook.com/docs/facebook-login/web)) rather than custom in-page credential forms.

---

## 📄 License & Disclaimer

- This project is a non-commercial fan creation developed solely for educational, design, and portfolio purposes.
- All game titles, character imagery, audio/video assets, and trademarks related to *Free Fire* and *Garena Free Fire Max* belong to **Garena International**.
- Facebook and Google trademarks and logos belong to their respective owners (Meta Platforms, Inc. and Google LLC).
