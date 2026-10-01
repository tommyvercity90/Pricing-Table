# 💳 Pricing Table

A simple and responsive **Pricing Table** built using **HTML5 and CSS3**.
This project demonstrates the use of **CSS Grid, Flexbox concepts, responsive design, hover effects, and styled pricing cards**.

## 📌 Project Overview

The pricing table contains three different plans:

* **Basic** – Perfect for beginners
* **Professional** – Best for growing teams
* **Premium** – For large businesses

The **Professional** plan is highlighted as the **Popular** plan.

## ✨ Features

* 📱 Fully responsive design
* 💳 Three pricing cards
* ⭐ Highlighted "Popular" plan
* 🎨 Modern and clean UI
* 🖱️ Button hover effects
* ✨ Card hover animations
* 📐 CSS Grid layout
* 📱 Responsive stacking on smaller screens
* 🔗 Separate HTML and CSS files

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* CSS Grid
* CSS Media Queries
* CSS Transitions
* CSS Hover Effects

## 📂 Project Structure

```text
pricing-table/
│
├── index.html
├── style.css
└── README.md
```

## 🚀 How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Make sure `index.html` and `style.css` are in the same folder.
4. Open `index.html` in any modern web browser.

No additional libraries or installations are required.

## 💰 Pricing Plans

| Plan         |     Price | Storage | Projects  |
| ------------ | --------: | ------- | --------- |
| Basic        |  $9/month | 10 GB   | 5         |
| Professional | $19/month | 50 GB   | 20        |
| Premium      | $39/month | 200 GB  | Unlimited |

## 📱 Responsive Design

The pricing cards are displayed in three columns on larger screens.

On smaller screens, the cards automatically stack vertically using a CSS media query:

```css
@media (max-width: 800px) {
    .pricing-container {
        grid-template-columns: 1fr;
    }
}
```

## 🎯 Learning Objectives

This project was created to practice:

* Creating layouts with CSS Grid
* Designing reusable cards
* Using CSS transitions
* Creating hover effects
* Applying responsive design
* Using media queries
* Styling buttons and pricing sections

## 📚 References

* [MDN Web Docs – CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout)
* [MDN Web Docs – CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout)

## 📄 License

This project is created for **learning and practice purposes**. Feel free to modify and improve it.
