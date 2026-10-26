# MAISON ÉLIXIR — Haute Parfumerie Artisanale

An ultra-luxury, responsive e-commerce web application for an artisanal Parisian perfumery, handcrafted using pure **HTML5**, **CSS3**, and modern vanilla **JavaScript** (ES6+).

---

## 🌟 Key Features

### 1. Luxury Editorial Visual Experience
- **Color Palette & Typography**: Obsidian noir (`#08090C`), satin surface cards, champagne gold accents (`#D4AF37`), Cormorant Garamond serif headings, and clean Plus Jakarta Sans modern typography.
- **Announcement Ticker**: Infinite marquee highlighting complimentary engraving, worldwide courier delivery, and VIP discount voucher.
- **Glassmorphic Navigation**: Sticky translucent header with live badge counters for shopping bag and wishlist.
- **Accolades Strip**: Editorial reviews from *Vogue*, *Harper's Bazaar*, *Elle*, and *GQ*.

### 2. Interactive Olfactory Experience
- **The Olfactory Pyramid Masterclass**: Interactive 3-tier visualization breaking down *Top Notes* (0–15m), *Heart Notes* (2–4h), and *Base Notes* (8–24h) with botanical ingredients and scientific evaporation context.
- **Fragrance Finder Quiz Modal**: 3-step interactive questionnaire that guides the client through their mood, occasion, and raw material preferences to unveil their personalized signature perfume.

### 3. Dynamic Product Catalog & Filtering
- **Live Search**: Instant keyword search across perfume names, mood tags, and top/heart/base ingredients.
- **Olfactory Family Filter Pills**: Filter by *Woody & Amber*, *Floral & Romantic*, *Fresh & Citrus*, or *Gourmand & Warm*.
- **Gender Category Tabs**: *All*, *Unisex*, *For Her*, and *For Him*.
- **Sort Selector**: Sort by Featured, Highest Rated, or Price (Low to High / High to Low).
- **Flacon Size Switcher**: Switch between 50ml and 100ml directly on each card or within the Quick View modal, recalculating the price in real time.

### 4. Interactive Shopping Bag & Checkout Simulation
- **Slide-Out Cart Drawer**:
  - Item list with quantity adjusters (`+` / `−`) and remove actions.
  - **Free Shipping Progress Tracker**: Visual progress bar calculating the remaining amount to reach free express worldwide shipping ($150 threshold).
  - **VIP Privilege Vouchers**: Enter promo code `LUXURY15` or `MAISON15` for 15% off, or `PARIS20` for 20% off.
- **Boutique Concierge Checkout**:
  - Shipping address form with complimentary bottle engraving option.
  - Real-time order calculation.
  - Order completion simulation with bespoke `#ELX-XXXXXX` order reference.

### 5. Wishlist & Quick View
- **Heart Wishlist**: Toggle favorites, persisted across sessions in `localStorage`.
- **Wishlist Drawer**: View saved fragrances and move them directly into your shopping bag.
- **Quick View Modal**: Deep dive into the perfume’s longevity meter, sillage rating, season pairing, and complete olfactory notes breakdown.

### 6. Atelier Heritage & VIP Club
- **Atelier Story**: Heritage since 1928, 90-day cold maceration in Grasse, France, and ethical botanical sourcing.
- **Client Testimonials**: Verified patron reviews from Paris, London, and New York.
- **Cercle Privé Newsletter**: Email signup with celebratory welcome toast alert.

---

## 📁 File Structure

```
perfume/
├── index.html          # Semantic HTML5 markup and modals
├── css/
│   └── style.css       # Design system, CSS variables, glassmorphism, animations & responsive queries
├── js/
│   ├── products.js     # Master fragrance catalog, notes pyramids & specs
│   └── app.js          # Cart state, wishlist, quiz engine, filters & UI interactions
└── README.md           # Documentation
```

---

## 🚀 How to Run & Preview

1. Open `index.html` directly in any modern browser (Chrome, Edge, Firefox, Safari).
2. Or serve it using any local HTTP server:
   - Using VS Code: Right-click `index.html` → **Open with Live Server**.
   - Using Python: `python -m http.server 8000` and navigate to `http://localhost:8000`.
