# BloomCraft Website

## Project Overview
BloomCraft is a simple e-commerce flower website created using HTML and Tailwind CSS.

The website is designed to make flower shopping more convenient by allowing customers to browse flowers online and personalize bouquet selections without visiting a physical flower shop.

The project contains:
- A homepage with featured bouquets and flower collections
- A shop page displaying available flowers
- A bouquet customization page
- An occasions page for flower recommendations
- An about page
- A contact page with a contact form
- Navigation bar and footer sections

---

# Features

- Responsive navigation bar
- Flower product display cards
- Featured bouquet section
- Bouquet customization form
- Occasion-based flower recommendations
- Contact form
- Simple and elegant UI design
- Consistent styling across pages

---

# Technologies Used

- HTML5
- Tailwind CSS
- Figma

---

# Tailwind CSS Architecture Documentation

The styling for this project is implemented using Tailwind CSS utility classes to improve consistency, responsiveness, and development efficiency.

## 1. Global Styling

Global styling is achieved through Tailwind utility classes applied directly to HTML elements.

Examples include:
- Background colors
- Typography
- Spacing
- Layout utilities

Example:

```html
<body class="bg-pink-50 font-sans">
```

---

## 2. Navigation Bar Styling

The navigation bar uses Flexbox utilities for layout and alignment.

Features include:
- Logo positioning
- Navigation links
- Responsive spacing
- Hover effects

Example:

```html
<nav class="flex justify-between items-center px-8 py-4">
```

---

## 3. Product Card Styling

Flower and bouquet products are displayed using reusable card layouts.

The product card styling includes:
- Rounded corners
- Shadow effects
- Hover transitions
- Consistent spacing
- Responsive grid layouts

Example:

```html
<div class="bg-white rounded-xl shadow-md p-4">
```

---

## 4. Button Styling

Buttons use consistent colors, padding, and hover effects to create a modern shopping experience.

Example:

```html
<button class="bg-pink-500 text-white px-6 py-2 rounded-full">
```

---

## 5. Form Styling

The bouquet customization and contact forms use styled input fields and spacing for better usability.

Features include:
- Rounded input fields
- Consistent padding
- Responsive layouts
- Styled submit buttons

Example:

```html
<input class="border rounded-lg p-3 w-full">
```

---

## 6. Footer Styling

The footer maintains a consistent appearance across all pages.

Features:
- Multiple information sections
- Contact details
- Quick navigation links
- Centered copyright information

---

# File Structure

```plaintext
BloomCraft/
│
├── index.html
├── shop.html
├── bouquet.html
├── occasions.html
├── about.html
├── contact.html
│
├── images/
│   ├── hero-bouquet.jpg
│   ├── roses.jpg
│   ├── tulips.jpg
│   ├── lilies.jpg
│   ├── orchids.jpg
│   └── other-images
│
└── README.md
```

---

# Browser Compatibility Report

The website was tested on the following browsers:

| Browser | Status |
|----------|----------|
| Google Chrome | Compatible |
| Microsoft Edge | Compatible |

## Testing Notes

- Navigation links function correctly
- Product cards display properly
- Images load correctly
- Forms display correctly
- Layout remains responsive on different screen sizes
- Styling remains consistent across tested browsers

---

# Challenges Faced

- Designing an attractive e-commerce layout
- Creating consistent spacing using Tailwind CSS
- Structuring reusable product card sections
- Planning the bouquet customization interface
- Maintaining visual consistency across pages

---

# Future Improvements

Possible future improvements include:

- Adding JavaScript functionality
- Creating a live bouquet preview feature
- Adding shopping cart functionality
- Implementing customer accounts
- Connecting forms to a backend database
- Integrating online payment systems
- Adding flower delivery tracking

---

# Conclusion

This project demonstrates the use of HTML and Tailwind CSS to create a clean, modern, and visually appealing flower e-commerce website.

It also shows understanding of:

- Web page structuring
- Responsive design principles
- Tailwind CSS utility classes
- Navigation design
- Form creation
- Basic UI/UX principles
- E-commerce website design
