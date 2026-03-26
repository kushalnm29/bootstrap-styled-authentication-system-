# AuthFlow – Authentication System Styling

> CampusPe Assignment | Full Stack Development Task  
> Bootstrap 5 + Custom CSS Authentication System

---

## 📋 Overview

A fully styled, responsive authentication system built with **Bootstrap 5** and **custom CSS**. Includes 5 complete HTML pages with professional UI, smooth animations, and full responsiveness across all screen sizes.

---

## 🗂️ Project Structure

```
auth-system/
├── index.html           # Page 1 – Login
├── register.html        # Page 2 – Registration
├── forgot-password.html # Page 3 – Forgot Password
├── reset-password.html  # Page 4 – Reset Password
├── dashboard.html       # Page 5 – Dashboard
├── styles.css           # Custom CSS (shared across all pages)
├── screenshots/         # Screenshots folder
└── README.md            # This file
```

---

## 🚀 Features

### Bootstrap 5 Integration
- Bootstrap 5.3.3 CSS & JS Bundle via CDN
- Bootstrap Icons 1.11.3 via CDN
- Bootstrap cards, form controls, navbar, badges, alerts, grid system

### Pages

| Page | File | Description |
|------|------|-------------|
| Login | `index.html` | Email/password form, password toggle, remember me, validation |
| Register | `register.html` | Full registration with password strength meter, validation |
| Forgot Password | `forgot-password.html` | Email input with simulated send animation |
| Reset Password | `reset-password.html` | New/confirm password with strength meter & requirements checklist |
| Dashboard | `dashboard.html` | Navbar, stats cards, activity feed, quick actions |

### Custom CSS (`styles.css`)
- **Google Fonts**: Plus Jakarta Sans + Syne (via `@import`)
- **CSS Variables**: Full custom color scheme with `--primary`, `--accent`, etc.
- **Hover effects**: Buttons, cards, links, nav items
- **Box shadows**: Cards with layered shadows + hover depth
- **Background gradient**: Animated blob decorations
- **Custom spacing**: Consistent spacing system
- **Smooth transitions**: `cubic-bezier` transitions throughout
- **Animations**: Card reveal, staggered form field entrance

### Responsive Design
- ✅ Desktop (1920px+)
- ✅ Laptop (1366px–1920px)
- ✅ Tablet (768px–1024px)
- ✅ Mobile (320px–767px)

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Primary | `#4F46E5` (Indigo) |
| Accent | `#06B6D4` (Cyan) |
| Success | `#10B981` |
| Danger | `#EF4444` |
| Font | Plus Jakarta Sans + Syne |
| Radius | `16px` cards, `10px` inputs |

---

## 🔗 Page Flow

```
index.html (Login)
    ├── → register.html (Register) → dashboard.html
    ├── → forgot-password.html
    │       └── → reset-password.html → index.html
    └── ✓ → dashboard.html
```

---

## 🛠️ Technologies Used

- HTML5 (semantic, accessible)
- CSS3 (custom properties, animations, flexbox, grid)
- Bootstrap 5.3.3
- Bootstrap Icons 1.11.3
- Vanilla JavaScript (form validation, toggles, strength meter)

---

## 📸 Screenshots

*(Add screenshots to the `screenshots/` folder)*

---

## ✅ Submission Checklist

- [x] Bootstrap integrated in all 5 pages
- [x] Proper use of cards, forms, buttons
- [x] `styles.css` created and linked
- [x] Responsive design tested
- [x] README.md included
- [x] Clean, indented code
- [x] All redirections working

---

*Built for CampusPe Full Stack Development Assignment*
