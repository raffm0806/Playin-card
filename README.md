# 🃏 Playing Cards — Flexbox Project

A responsive playing cards layout built as part of the **freeCodeCamp** Responsive Web Design curriculum. The project focuses on semantic HTML5 structure and CSS Flexbox alignment using an internal `<style>` block.

---

## 🚀 Features & Layout Structure

* **Semantic Container**: Uses a `<main id="playing-cards">` wrapper containing multiple `.card` elements.
* **Flexbox Grid**: `#playing-cards` uses `display: flex`, `flex-wrap: wrap`, horizontal centering, and a `20px` gap between cards.
* **Card Sections**: Each `.card` contains `.left`, `.middle`, and `.right` containers styled with `display: flex` and `justify-content: space-between`.
* **Item Alignment**:
  * `.left` aligns to the start of its parent container.
  * `.middle` centers itself and stacks its children in a column (`flex-direction: column`).
  * `.right` aligns to the end of its parent container.

---

## 📁 Project Structure

```text
└── index.html    # Single HTML file with semantic markup and internal CSS (<style>)
