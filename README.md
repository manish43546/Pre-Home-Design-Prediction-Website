# 🏠 PRE-HOME DESIGN

### Visualize Your Future Home Before You Build It.

**PRE-HOME DESIGN** is a modern and interactive frontend project designed to help users **visualize and plan their future home before construction begins**.

The idea behind this project is simple:

> **Before spending money on construction, understand how your future home could look, feel, and be designed.**

The platform provides an immersive architectural experience where users can explore home designs, customize their preferences, visualize a home concept, and connect with an engineer for professional guidance.

---

## 🌐 Project Overview

Building a home is a major investment, but many people start construction without having a clear understanding of how the final house will look.

**PRE-HOME DESIGN** focuses on solving this problem through an interactive digital experience.

Users can:

- 🏠 Explore different home designs
- 🎨 Select architectural styles
- 🏢 Choose number of floors
- 🛏️ Select bedroom requirements
- 📐 Select plot-size preferences
- 👀 Preview a future-home concept
- 👷 Contact an engineer
- 🔐 Access a frontend login interface
- 📱 Experience the platform on desktop, tablet and mobile

---

# ✨ Key Features

## 🎬 Cinematic Landing Page

The website starts with a full-screen construction video background that creates an immersive architectural experience.

The hero section contains:

- `Design Before You Build`
- `See Your Future Home Before You Build It`
- `Design Your Future Home`
- `Explore Designs`
- `Contact Engineer`
- `Login`

---

## 🏡 Interactive Home Design Experience

Users can start their home-design journey by selecting different preferences.

### Users can choose:

- Home Type
- Number of Floors
- Bedrooms
- Architectural Style
- Plot Size
- Exterior Style

The selected options are reflected in the frontend preview experience.

---

## 🎨 Home Design Gallery

A dedicated design gallery allows users to explore different architectural concepts.

Examples include:

- Modern Villa
- Luxury Duplex
- Urban Residence
- Minimalist House
- Contemporary Family Home
- Premium Courtyard Villa

Each design card provides information such as:

- Design name
- Home type
- Area
- Bedrooms
- Floors
- Design preview

Interactive hover animations are also implemented to make the experience more engaging.

---

## 🧩 Design Your Future Home Wizard

One of the core features of the project is a **multi-step home-design wizard**.

### User Journey

```text
Choose Home Type
       ↓
Choose Number of Floors
       ↓
Choose Bedrooms
       ↓
Choose Architectural Style
       ↓
Choose Plot Size
       ↓
Generate Home Concept Preview
```

At the end of the process, the user receives a frontend-based summary of their selected preferences along with a visual home concept.

---

## 👷 Contact Engineer

Users can connect with an engineer through a consultation form.

The form collects:

- Name
- Phone
- Email
- Location
- Plot Size
- Home Type
- Message

After submission, a frontend success state is displayed.

> Currently this is a frontend-only implementation and does not send data to a backend.

---

## 🔐 Login Interface

A modern login interface has been created for the platform.

It includes:

- Email
- Password
- Forgot Password
- Continue with Google UI
- Create Account

Authentication functionality is intentionally not connected to a backend because this project focuses on the **frontend experience**.

---

# 🎯 Project Goal

The main goal of PRE-HOME DESIGN is to create a digital experience that helps users answer an important question:

> **"Mera future home construction ke baad kaisa dikhega?"**

Instead of directly moving from an idea to construction, the platform introduces a visualization and planning stage.

```text
Idea
 ↓
Explore
 ↓
Customize
 ↓
Visualize
 ↓
Consult Engineer
 ↓
Plan Construction
```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| Vite | Development & build tool |
| Tailwind CSS | UI styling |
| JavaScript | Application logic |
| Framer Motion | Animations & transitions |
| Lucide React | Icons |
| HTML5 Video | Construction background |
| Unsplash / Local Assets | Architectural imagery |

---

# 🎨 UI & Design

The interface follows a **premium architectural / real-estate design language**.

### Design principles:

- Dark cinematic interface
- Glassmorphism
- Architectural grid patterns
- Large typography
- Minimal UI
- Smooth transitions
- Subtle gold/amber accents
- Responsive layouts
- Interactive cards
- Modern navigation

The goal was to make the website feel less like a traditional real-estate website and more like a **modern architecture-tech product**.

---

# 📱 Responsive Design

The website is designed to work across:

- 💻 Desktop
- 🖥️ Laptop
- 📱 Mobile
- 📲 Tablet

The UI adapts to different screen sizes while maintaining the overall visual experience.

---

# 🎞️ Animations & Interactions

The project uses **Framer Motion** to create a more engaging user experience.

Implemented interactions include:

- Hero animations
- Scroll reveal
- Card hover effects
- Image zoom
- Button animations
- Modal transitions
- Design wizard transitions
- Navbar transitions
- Staggered content animations

Animations are intentionally kept smooth and subtle rather than excessive.

---

# 📂 Project Structure

```text
PRE-HOME-DESIGN/
│
├── public/
│   └── assets/
│       ├── construction-video.mp4
│       └── images/
│
├── src/
│   │
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Hero.jsx
│   │   ├── DesignVisualizer.jsx
│   │   ├── DesignGallery.jsx
│   │   ├── HowItWorks.jsx
│   │   ├── Services.jsx
│   │   ├── WhyPreHome.jsx
│   │   ├── ContactEngineer.jsx
│   │   ├── DesignWizard.jsx
│   │   ├── LoginModal.jsx
│   │   └── Footer.jsx
│   │
│   ├── data/
│   │   ├── designs.js
│   │   └── services.js
│   │
│   ├── pages/
│   │   └── Home.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── tailwind.config.js
└── README.md
```

---

# 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/pre-home-design.git
```

### 2. Navigate to the project

```bash
cd pre-home-design
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

# 🖼️ Project Preview

### Landing Page

> Add your screenshot here.

```text
![Landing Page](./screenshots/home.png)
```

### Design Gallery

> Add your screenshot here.

```text
![Design Gallery](./screenshots/design-gallery.png)
```

### Design Wizard

> Add your screenshot here.

```text
![Design Wizard](./screenshots/design-wizard.png)
```

---

# 🔮 Future Improvements

This project currently focuses on the frontend. Future versions could include:

- 🤖 AI-powered house visualization
- 🏠 Real-time 3D home configurator
- 📐 Interactive floor-plan editor
- 🧱 Material and exterior customization
- 🌳 Landscape visualization
- 👷 Real engineer consultation system
- 🔐 Real authentication
- 💾 Save home designs
- ☁️ Cloud-based project storage
- 📊 Construction cost estimation
- 📱 Mobile application
- 🥽 AR/VR home visualization

---

# 💡 What I Learned

While building this project, I focused on:

- Building reusable React components
- Creating responsive layouts
- Designing modern UI/UX
- Managing frontend state
- Creating multi-step user flows
- Implementing animations with Framer Motion
- Building interactive forms
- Structuring a scalable frontend project
- Creating a product-oriented user experience

---

# 🎯 Core User Flow

```text
                    PRE-HOME DESIGN
                           │
                           ▼
                  Landing Page
                           │
              ┌────────────┴────────────┐
              ▼                         ▼
       Explore Designs          Design Your Future Home
                                         │
                                         ▼
                                  Choose Preferences
                                         │
                                         ▼
                                  Home Concept Preview
                                         │
                                         ▼
                                  Contact Engineer
```

---

# 📌 Project Status

**Frontend:** ✅ Completed

**Backend:** ❌ Not implemented

**Authentication:** 🎨 UI only

**Database:** ❌ Not implemented

**AI Visualization:** 🔮 Future Feature

**3D Visualization:** 🔮 Future Feature

---

# 👨‍💻 Developer

**Manish Kumar Singh**

B.Tech Computer Science & Engineering

Interested in:

- Frontend Development
- Data Analytics
- Software Development
- UI/UX
- Problem Solving

---

## ⭐ If you find this project interesting

Feel free to explore the repository, suggest improvements, or use the project as inspiration for your own frontend experiments.

---

### PRE-HOME DESIGN

**Visualize. Design. Build.**

> *Your dream home shouldn't be a surprise after construction.*
> 
> *See it before you build it.*
