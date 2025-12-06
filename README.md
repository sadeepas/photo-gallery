# Creative Tech Photo Gallery 📸


A sleek, responsive photo gallery template designed with a modern "Tech" aesthetic. This project demonstrates how to create a grid layout with hover effects and a functional image lightbox using Tailwind CSS and vanilla JavaScript.

## 🌟 Features

*   **Responsive Grid Layout:** Automatically adjusts columns based on screen size (1 column on mobile, 2 on tablet, 3 on desktop).
*   **Dark Mode Aesthetic:** Features a custom gradient background suitable for tech or portfolio portfolios.
*   **Interactive Animations:** Smooth `hover:scale` and shadow effects on images.
*   **Lightweight Lightbox:** Custom JavaScript modal to view images in full size without external libraries.
*   **Zero Build Step:** Uses the Tailwind CSS CDN, so you can run it instantly without Node.js or npm.

## 🚀 How to Run

1.  **Clone the repository** (or download the ZIP file):
    ```bash
    git clone https://github.com/yourusername/creative-tech-gallery.git
    ```
2.  **Open the file:**
    Simply double-click the `index.html` file to open it in your default web browser.

## 🛠️ Customization

Currently, the gallery uses placeholder images from `via.placeholder.com`. To make this gallery your own:

1.  Open `index.html` in your code editor.
2.  Locate the `<img>` tags.
3.  Replace the `src` attribute with your own image URLs or local file paths.
4.  **Important:** Make sure to update the `onclick` parameter to match the new image source so the modal opens the correct image.

**Example:**
```html
<!-- Change this -->
<img 
  src="https://via.placeholder.com/300" 
  onclick="openModal('https://via.placeholder.com/300')">

<!-- To this -->
<img 
  src="./images/my-photo.jpg" 
  onclick="openModal('./images/my-photo.jpg')">
```

## 💻 Technologies Used

*   **HTML5**: Semantic structure.
*   **Tailwind CSS (CDN)**: Utility-first styling for layout, typography, and responsive design.
*   **JavaScript (ES6)**: DOM manipulation for the modal (Open/Close functionality).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Made with ❤️ using Tailwind CSS
</p>
```
