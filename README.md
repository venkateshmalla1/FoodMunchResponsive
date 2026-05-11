# 🍔 Food Munch Website

## ℹ️ Overview
Food Munch is a responsive restaurant landing page built with HTML, CSS, and Bootstrap. The site highlights menu items, delivery options, features, and contact details with a polished, modern presentation.

## ✨ Features
- ✅ Fixed navigation bar with smooth scrolling to page sections
- 🎯 Full-width hero section with dark overlay and headline copy
- 📱 Responsive feature cards for restaurant benefits
- 🍽️ Menu item cards with hover interactions
- 🚚 Delivery and payment section with call-to-action button
- 🔗 Footer with social links and brand information

## 📁 Project Structure
```
FoodMunchResponsive/
├── index.html
└── style.css
```

## 💻 Technologies
- HTML5
- CSS3
- Bootstrap 4.5
- Font Awesome icons
- Unsplash image assets via CDN

## ⚙️ Setup
1. Clone or download the repository.
2. Open `index.html` in your web browser.
3. Ensure internet access for Bootstrap and Font Awesome CDN resources.

## 🎨 Customization
- Update images and background graphics directly in `style.css`.
- Adjust hero overlay opacity in the `.welcome-container::before` rule:
  ```css
  .welcome-container::before {
    background: rgba(0, 0, 0, 0.8);
  }
```
- Modify typography and color variables in `style.css` to match brand identity.

## 📝 Notes
This project is designed as a static demo site and does not include backend functionality.
