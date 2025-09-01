# Niyantri Cafe – 5 Page Website

This project builds a responsive 5-page coffee shop website using Tailwind CSS with a warm coffee color palette. It includes a cart system backed by localStorage, a PayPal Sandbox checkout, and a fullscreen hero with a Swiper carousel. All images use placeholder src as described.

Pages:
- index.html – Home with a Swiper hero, highlights, and testimonials
- menu.html – Menu with 8 items and Add to Cart buttons
- cart.html – Cart with a PayPal Sandbox checkout
- about.html – About/Niyantri Cafe story
- contact.html – Contact form and Hyderabad, India placeholder address

Tech & Assets:
- Tailwind CSS (via CDN)
- Swiper.js (via CDN) for hero carousel
- PayPal Checkout (Sandbox) integration via client-id sb
- Google Fonts: Poppins & Lora
- All interactive elements use Tailwind CSS for transitions and states
- All content uses semantic HTML with proper alt text for accessibility

Notes:
- The footer uses the provided current year 2025
- The cart system uses a single, shared set of functions on all pages:
  - getCart, saveCart, addToCart, removeFromCart, updateCartCount, renderCartPage
- The cart count is displayed in the navigation: Cart (X)

If you’d like any content adjusted (locations, item names, prices, or additional items), tell me and I’ll update quickly.