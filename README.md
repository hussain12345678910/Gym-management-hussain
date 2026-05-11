# 🌐 NexaStudio — Creative Agency Website

A modern, multi-page static website for **NexaStudio**, a creative digital agency. Built with pure HTML and CSS using a consistent dark-themed design system — no frameworks, no build tools, just clean code that runs in any browser.

---

## 📋 Table of Contents

- [Live Pages](#live-pages)
- [Features](#features)
- [Project Structure](#project-structure)
- [Pages Overview](#pages-overview)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Design System](#design-system)
- [Team](#team)

---

## 🖥️ Live Pages

| Page      | File            | Description                          |
|-----------|-----------------|--------------------------------------|
| Home      | `index.html`    | Hero, stats, services preview & CTA  |
| About     | `about.html`    | Studio story & team members          |
| Services  | `services.html` | Service cards with pricing           |
| Gallery   | `gallery.html`  | Project showcase with hover overlays |
| Contact   | `contact.html`  | Contact form with info panel         |
| Login     | `login.html`    | User sign-in form                    |
| Register  | `register.html` | New account creation form            |

---

## ✨ Features

- 🌙 **Dark Theme** — Deep dark backgrounds (`#0f0f1a`, `#1a1a2e`) for a premium look
- 🎨 **Gradient Accent** — Purple-to-teal gradient (`#6c63ff → #00d4aa`) as the brand identity
- 📱 **Fully Responsive** — Breakpoints at 600px, 768px, and 992px for all screen sizes
- 🧭 **Shared Navigation** — Consistent navbar with active-link state across all pages
- 🔐 **Authentication Pages** — Split-panel login & register with fade-in animation
- 🖼️ **Gallery with Overlays** — Hover reveals project name and category on each card
- 📬 **Contact Form** — Two-column layout with service selector and message textarea
- 👥 **Team Section** — 4-person grid with smooth hover lift effect

---

## 📁 Project Structure

```
NexaStudio/
│
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── gallery.html        # Gallery page
├── contact.html        # Contact page
├── login.html          # Login page
├── register.html       # Register page
│
└── css/
    ├── style.css       # Global styles (nav, base, buttons)
    ├── home.css        # Hero, stats, services preview, CTA
    ├── about.css       # About hero, team grid & cards
    ├── services.css    # Service cards with pricing
    ├── gallery.css     # Gallery grid and hover overlays
    ├── contact.css     # Contact grid and form styling
    └── auth.css        # Login & register split layout
```

---

## 📄 Pages Overview

### 🏠 Home (`index.html`)
- Full-width **hero** with headline "*We Build Digital Experiences*" and two CTA buttons
- **Stats bar** — 240+ Projects · 98% Satisfaction · 12+ Years · 40+ Team Members
- **Services preview** — 3-card grid for UI/UX, Web Development, and Mobile Apps
- **CTA banner** — "*Have a project in mind?*" with a link to Contact
- Footer with copyright notice

### 👥 About (`about.html`)
- Two-column hero: left text (studio founding story) + right gradient icon box
- **Team grid (4 cards):**
  - Aiden Carter — Founder & CEO
  - Sofia Reyes — Head of Design
  - Marcus Lin — Lead Engineer
  - Priya Nair — Strategy Director
- Cards animate upward on hover (`translateY(-8px)`)

### 🛠️ Services (`services.html`)
- 6-card grid with emoji icons and per-project/month pricing:

  | Service          | Price            |
  |------------------|------------------|
  | UI/UX Design     | $2,400 / project |
  | Web Development  | $4,800 / project |
  | Mobile Apps      | $6,500 / project |
  | Brand Identity   | $1,800 / project |
  | SEO & Analytics  | $1,200 / month   |
  | Cloud & DevOps   | $2,200 / month   |

### 🖼️ Gallery (`gallery.html`)
- 3-column image grid with real project screenshots
- Hover reveals gradient overlay with project name and category
- Projects: **NovaTech** (Web App) · **Lumière** (E-Commerce) · **Stride** (Mobile App) · **Aura Music** (Streaming) · **GreenRoot** (NGO Website) · **Vaulted** (FinTech)

### 📬 Contact (`contact.html`)
- Left panel: studio contact info
  - 📍 Karachi, Pakistan
  - 📧 hello@nexastudio.com
  - 📞 +92 300 1234567
- Right panel: form with First/Last Name row, Email, Service dropdown, Message textarea, and Submit button

### 🔐 Login (`login.html`)
- Split layout — gradient left panel + form right
- Fields: Username, Password
- Remember me checkbox + Forgot password link
- Link to Register page

### 📝 Register (`register.html`)
- Matching split layout to login
- Fields: Full Name, Email, Username, Password, Terms checkbox
- `.auth-card` fades in with `translateY` animation on load
- Link back to Login page

---

## 🛠️ Tech Stack

| Technology    | Usage                              |
|---------------|------------------------------------|
| HTML5         | Semantic page structure            |
| CSS3          | All styling, transitions, animations |
| CSS Grid      | Page layouts, team grid, gallery   |
| CSS Flexbox   | Navbar, form rows, info items      |
| Media Queries | Responsive design (3 breakpoints)  |

> ⚡ Zero dependencies — no JavaScript, no framework, no build step needed.

---

## 🚀 Getting Started

### Option 1 — Open directly in browser

```bash
# Clone the repository
git clone https://github.com/hussain12345678910/Gym-management-hussain.git
cd Gym-management-hussain

# Open in your browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Option 2 — VS Code Live Server (recommended)

1. Open the project folder in **VS Code**
2. Install the **Live Server** extension
3. Right-click `index.html` → **Open with Live Server**
4. The site opens at `http://127.0.0.1:5500` with hot reload

---

## 🎨 Design System

### Color Palette

| Role            | Hex       |
|-----------------|-----------|
| Page Background | `#0f0f1a` |
| Card Background | `#1a1a2e` |
| Primary Accent  | `#6c63ff` |
| Secondary Accent| `#00d4aa` |
| Muted Text      | `#aaa` / `#bbb` |
| Primary Text    | `#ffffff` |

### Responsive Breakpoints

| Breakpoint | Change                                         |
|------------|------------------------------------------------|
| `≤ 992px`  | About hero stacks vertically; team → 2 columns |
| `≤ 768px`  | Auth split collapses; contact stacks to 1 col  |
| `≤ 600px`  | Gallery → 1 column; team cards → 1 column      |

---

## 👨‍💻 Team

This project was developed by:

| Name               | Roll No |
|--------------------|---------|
| Hussain Alam Mirza | 035     |
| M. Ahsan Abid      | 040     |
| Abdul Qadeer       | 043     |
| Maliha Siddique    | 012     |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> ⭐ If you found this project helpful, give it a star on GitHub!
