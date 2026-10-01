# Dynamic Product Display Grid

A modern, responsive, and feature-rich e-commerce product display grid web application built with **React.js**, **Tailwind CSS**, and **JavaScript**, powered by a structured JSON dataset.

---

## 🚀 Key Features

1. **24 Curated Realistic Products**
   - Diverse catalog across 5 major categories: *Electronics*, *Clothing*, *Shoes*, *Accessories*, and *Home*.
   - Realistic Indian Rupee (₹) pricing ranging from under ₹1,000 to premium items above ₹10,000.
   - High-definition photography, stock statuses (*In Stock*, *Low Stock*, *Out of Stock*), and customer ratings.

2. **Fully Responsive Grid Layout**
   - **Desktop (≥ 1024px):** 4 columns
   - **Tablet (640px – 1023px):** 2 to 3 columns
   - **Mobile (< 640px):** 1 column

3. **Live Dynamic Search**
   - Real-time search query matching product names, categories, and descriptions.
   - Instant live counter of matching items.
   - Quick one-click clear button (`X`).

4. **Multi-Criteria Filtering & Sorting**
   - **Category Pills:** Filter by *All*, *Electronics*, *Clothing*, *Shoes*, *Accessories*, and *Home* with live product counts.
   - **Price Ranges:** *All Prices*, *Under ₹1,000*, *₹1,000 – ₹5,000*, *₹5,000 – ₹10,000*, and *Above ₹10,000*.
   - **Sorting:** *Default*, *Price: Low to High*, *Price: High to Low*, *Rating: High to Low*, *Name: A to Z*, and *Name: Z to A*.
   - **Seamless Integration:** Search, category filters, price filters, and sorting work in unison.

5. **Interactive Product Details Modal**
   - Click "View Details" on any card to open a modal with backdrop blur.
   - Large image display, full product description, guarantees, and stock indicator.
   - Interactive quantity counter and "Add to Cart" action.
   - Keyboard accessible (`Escape` key to close) and backdrop dismiss.

6. **Empty State & Reset System**
   - Friendly empty-state illustration when no products match.
   - "Reset All Filters" button to immediately return to the default catalog.

---

## 📂 Project Structure

```text
Task3/
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── README.md
└── src/
    ├── App.jsx
    ├── main.jsx
    ├── index.css
    ├── data/
    │   └── products.json
    └── components/
        ├── Header.jsx
        ├── SearchBar.jsx
        ├── FilterBar.jsx
        ├── ProductGrid.jsx
        ├── ProductCard.jsx
        └── ProductModal.jsx
```

---

## 🛠️ Installation & Setup Commands

### 1. Install Dependencies
```bash
npm install
```

### 2. Start the Development Server
```bash
npm run dev
```
Open your browser and navigate to:
```text
http://localhost:5173
```

### 3. Build for Production
```bash
npm run build
```

### 4. Preview the Production Build
```bash
npm run preview
```
