# 🌿 Harvest & Co. — Premium Garden Café Landing Page

> A stunning, fully responsive restaurant landing page for **Harvest & Co.**, a premium garden café located inside Dubai Garden Centre, Sheikh Zayed Road. Built with pure HTML, CSS & JavaScript — featuring scroll animations, FAQ accordion, photo menu grid, guest reviews & a table reservation CTA.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-brightgreen?style=for-the-badge)
![Location](https://img.shields.io/badge/📍-Dubai%2C%20UAE-red?style=for-the-badge)

---

## 🌐 Live Demo

> 🔗 [Add your deployed link here once live!]

---

## 📍 About the Café

| Detail | Info |
|---|---|
| 📍 Location | Dubai Garden Centre, Sheikh Zayed Road, Al Quoz (next to Lexus showroom) |
| 📞 Phone | +971 56 219 7745 |
| ⭐ Rating | 4.9 / 5 from 8,800+ guests |
| 💰 Price | AED 50–100 per person |
| 🍳 Breakfast | Served all day until ~4 PM |
| 🚗 Service | Dine-in, Takeaway & Delivery |

---

## ✨ Features

- 🎨 **Premium Café UI** — Earthy green & sand color palette with Playfair Display + Outfit fonts
- 📱 **Fully Responsive** — Mobile, tablet & desktop with animated hamburger menu
- 🌀 **Scroll Reveal Animations** — Cards and sections animate in using Intersection Observer API
- 🦸 **Conversion-Focused Hero** — Location tag, rating badge, dual CTA buttons & highlight checklist
- ⚖️ **Problem / Solution Section** — Pain point cards vs. nature-inspired solution with floating glass card
- 🏆 **5 Benefits Cards** — 4.9 Rating, Fresh & Seasonal, Specialty Coffee, All-Day Breakfast, Garden Setting
- 🪜 **3-Step Booking Process** — Choose Time → Book Table → Enjoy
- 🍽️ **Photo Menu Grid** — 6 signature dishes with Unsplash photos (Brioche French Toast, Shakshuka, Avocado Toast, etc.)
- 💬 **Guest Testimonials** — 3 real 5-star reviews
- ❓ **FAQ Accordion** — 4 smooth animated open/close questions
- 📣 **Final CTA + Footer** — Reservation banner, address, phone & social links (Instagram, Facebook, TikTok)
- 📌 **Sticky Navbar** — Adds shadow & background on scroll
- 🔗 **Smooth Scrolling** — All anchor links scroll with header offset compensation

---

## 📁 Project Structure

```
harvest-and-co-cafe/
├── index.html      # Full single-page landing page
├── styles.css      # All styles, layout, animations & responsive rules
├── script.js       # Mobile menu, sticky nav, FAQ accordion & scroll animations
└── README.md
```

---

## 🗂️ Page Sections

| Section | Description |
|---|---|
| **Navbar** | Sticky nav with logo, links, Reserve Table CTA & mobile hamburger |
| **Hero** | Location badge, headline, 4.9★ rating, dual CTAs & highlights checklist |
| **Problem** | 4 pain-point cards — noisy, processed food, poor atmosphere, inconsistent quality |
| **Solution / Experience** | Two-column layout with café image, floating glass card & 4 benefit points |
| **Benefits** | 5-card green-background grid — rating, freshness, coffee, breakfast, garden setting |
| **How It Works** | 3-step booking process with connecting step lines |
| **Menu** | 6-photo dish grid — Brioche French Toast, Mocha, Shakshuka, Avocado Toast, Honey Butter Toast, Turkish Eggs |
| **Testimonials** | 3 five-star guest reviews |
| **FAQ** | 4-item animated accordion — location, price, delivery, breakfast hours |
| **Footer / CTA** | Reservation banner, café info, phone number & social media links |

---

## 🍽️ Menu Highlights

| Dish | Icon |
|---|---|
| Brioche French Toast | 🍞 |
| Mocha Coffee | ☕ |
| Shakshuka | 🔥 |
| Avocado Toast | 🥑 |
| Honey Butter Toast | 🍯 |
| Turkish Eggs | 🥚 |

---

## 🚀 Getting Started

No build tools or installation needed!

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/harvest-and-co-cafe.git

# Navigate into it
cd harvest-and-co-cafe

# Open in browser
open index.html
```

Use the **Live Server** extension in VS Code for the best development experience.

---

## 🌍 Deployment (Free Options)

### ⚡ Option 1 — Netlify Drop *(Easiest — 60 seconds)*
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag & drop your project folder
3. Get a live `https://` link instantly!

### 🐙 Option 2 — GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Select `main` branch → Save
4. Live at: `https://yourusername.github.io/harvest-and-co-cafe`

---

## ⚙️ Customization Guide

### 🏷️ Update Café Name / Branding
Search for `Harvest & Co` in `index.html` and replace with your café name throughout.

### 📞 Update Phone Number
Search for `+971 56 219 7745` in `index.html` and replace with your number.

### 📍 Update Location
Find the address references in `index.html`:
```html
<p>Dubai Garden Centre – Sheikh Zayed Road</p>
```
Replace with your actual address.

### 📱 Update Social Media Links
In the footer of `index.html`, update the `href="#"` on each social button:
```html
<a href="https://instagram.com/yourhandle"><i class="fa-brands fa-instagram"></i></a>
<a href="https://facebook.com/yourpage"><i class="fa-brands fa-facebook"></i></a>
<a href="https://tiktok.com/@yourhandle"><i class="fa-brands fa-tiktok"></i></a>
```

### 🍽️ Add / Replace Menu Items
In `index.html`, find the `.menu-grid` section and update or duplicate any `.menu-card`:
```html
<div class="menu-card">
    <img src="YOUR_IMAGE_URL" alt="Dish Name" class="menu-img">
    <div class="menu-info">
        <h3><i class="fa-solid fa-icon-name"></i> Dish Name</h3>
    </div>
</div>
```

### 🎨 Change Color Theme
At the top of `styles.css`, update the CSS variables:
```css
:root {
    --primary: #your-green;
    --secondary: #your-sand;
    --accent: #your-accent;
}
```

### ❓ Add FAQ Questions
Duplicate any `.faq-item` block in `index.html`:
```html
<div class="faq-item">
    <div class="faq-question">
        <h3>Your question here?</h3>
        <i class="fa-solid fa-chevron-down"></i>
    </div>
    <div class="faq-answer">
        <p>Your answer here.</p>
    </div>
</div>
```

---

## 🧩 Dependencies

All loaded via CDN — no npm install needed.

| Library | Usage |
|---|---|
| [FontAwesome 6](https://fontawesome.com/) | All icons throughout the page |
| [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) | Heading typography |
| [Outfit](https://fonts.google.com/specimen/Outfit) | Body typography |
| [Unsplash](https://unsplash.com/) | Menu dish photos (replace with real photos) |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with 🌿 for fresh food lovers in Dubai</p>
