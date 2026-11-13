# 🃏 Interactive Pokémon Card Stack

A simple, interactive web project built with pure HTML and CSS that displays a fanned-out stack of Pokémon-themed cards. Hovering over the underlying cards dynamically brings them to the front of the stack.

## ✨ Features

* **Fanned Card Layout:** Uses CSS `rotate` transformations and `z-index` layering to create a natural, fanned-out deck appearance centered on the screen.
* **Interactive Hover Effects:** Hovering over any card behind the top card instantly elevates its `z-index`, bringing it into full view without JavaScript.
* **Clean & Lightweight:** Built entirely with semantic HTML5 and vanilla CSS3.

## 🛠️ Technologies Used

* **HTML5** – Page structure and image containers.
* **CSS3** – Flexbox centering, absolute positioning, CSS `rotate`, and `:hover` state layering.

## 📁 Project Structure

```text
├── index.html                           # Main HTML structure
├── style.css                            # Styling, card rotation, and hover effects
├── images-2.jpeg                        # Card 1: Great Ball
├── v4-1200px-Draw-Pikachu-Step-14.jpg   # Card 2: Pikachu
├── images.jpeg                          # Card 3: Squirtle
└── 1734433836048-i.webp                 # Card 4: Ash & Pikachu
```

## 🚀 Getting Started

To run this project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/pokemon-cards.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd pokemon-cards
   ```
3. **Open the project:**
   Double-click `index.html` to open it in your preferred web browser, or use a live server extension (like VS Code Live Server).

## 💡 Future Improvements

* Add smooth CSS `transition` animations when hovering over cards.
* Include a subtle `scale()` or `translateY()` effect on hover for a more tactile feel.
* Add card flip animations to reveal Pokémon stats on the back.

## 📄 License

This project is open-source and available for personal and educational use. Pokémon and all respective character names/images are trademarks of Nintendo/Creatures Inc./GAME FREAK inc.