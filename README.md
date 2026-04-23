# 🎁 Lily Studio Gifts

A warm, handcrafted business website for custom laser-cut personalized gifts — made to order in Boston, MA.

**Live site:** [https://lilyntran98.github.io/lily-studio-gifts](https://lilyntran98.github.io/lily-studio-gifts)

---

## 📦 Products & Prices

| Product | Price | Notes |
|---------|-------|-------|
| Wooden Bookmarks | $10 | Bamboo, personalized |
| Wooden Coasters | $5 each · $18 / set of 4 | Birch plywood |
| Charcuterie Board | $20 | Hardwood, food-safe |
| Engraved Box | $15 | Customer provides the box |
| Wooden Lantern | $35 | Birch plywood |
| Engraved Glass or Bottle | $15 | Customer provides the glass/bottle |
| Custom Signs & More | $10–$20 | Depends on size and complexity |

---

## 📁 Folder Structure

```
lily-studio-gifts/
├── index.html
├── README.md
└── images/
    ├── bookmark.jpg         ← Wooden bookmarks
    ├── IMG_4757.jpg         ← Wooden coasters
    ├── IMG_4758.jpg         ← Charcuterie board
    ├── IMG_5735.jpg         ← Engraved box
    ├── IMG_5432.jpg         ← Wooden lantern
    ├── IMG_4222.jpg         ← Engraved glass cup
    └── IMG_5431.jpg         ← Custom signs
```

> 💡 The `images/` folder can be shared or copied from your makerspace portfolio repo — the filenames are the same.

---

## ➕ How to Add a New Product

Copy and paste this template inside the `<div class="products-grid">` section of `index.html`:

```html
<div class="product-card">
  <div class="product-thumb">
    <img src="images/your-photo.jpg" alt="Product Name"/>
  </div>
  <div class="product-body">
    <h3 class="product-name">Product Name</h3>
    <p class="product-desc">Short description of the product.</p>
    <p class="product-note">✦ Any special notes (e.g. customer provides item)</p>
    <div class="product-footer">
      <span class="product-price">$XX</span>
      <a href="#order" class="order-btn">Order</a>
    </div>
  </div>
</div>
```

Also add the new product to the order form dropdown by finding the `<select id="f-product">` section and adding:

```html
<option>Your Product Name — $XX</option>
```

---

## 🎨 Quick Customizations

| What | Where in index.html |
|------|---------------------|
| Business name | Nav logo + footer logo |
| Hero title / subtitle | Hero section |
| Trust badges | `.hero-trust` div |
| Product prices | Each `.product-price` span |
| How It Works steps | `.steps` section |
| Occasion cards | `.occasions-grid` section |
| Email address | `mailto:` links + form script |
| Instagram handle | `instagram.com/` links |
| WhatsApp number | `wa.me/` links |
| Footer copyright | Bottom of file |

---

## 📬 Contact & Ordering

Customers can reach out via:
- **Email:** tran.nhi2@northeastern.edu
- **Instagram:** [@littlelil22](https://instagram.com/littlelil22)
- **WhatsApp:** +1 (949) 880-7221
- **Order form** on the site (pre-fills an email automatically)

---

## 📸 Photo Tips

- Keep photos under **1MB** — compress at [squoosh.app](https://squoosh.app)
- No spaces in filenames — use `bookmark.jpg` not `book mark.jpg`
- Landscape (4:3 ratio) works best for product cards

---

Made with ♥ in Boston, MA · Northeastern MakerSpace
