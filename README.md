```markdown
# 📝 CCBP 4.0 Testimonials Search Filter

A responsive web application that displays student testimonials from the CCBP 4.0 program and allows users to filter them in real-time based on a search keyword.

---

## 🚀 Features

- 🔍 **Live Search Filtering**: As users type into the search input, testimonials are filtered and displayed instantly.
- ✂️ **Clear Button**: A clear (✖) icon appears when input is typed, allowing users to reset the input and view all testimonials again.
- 🧠 **Case & Partial Match Support**: The search works for both full and partial words, regardless of case. Example: typing "mech" will match "Mechanical".
- ⌨️ **Enter Key Functionality**: Optionally triggers filter on pressing Enter (though filtering is live).
- 📱 **Responsive Design**: Fully optimized for desktop and mobile screens.

---

## 🧑‍💻 Technologies Used

- **HTML** – Markup structure
- **CSS** – Styling and layout
- **JavaScript** – Filtering logic, DOM manipulation, and dynamic rendering

---


```
## 📂 Folder Structure
├── index.html


├── style.css


├── script.js

└── README.md

```

---

## 🧪 How It Works

1. A static list of 10 testimonials is stored in a JavaScript array.
2. When the user types in the search bar:
   - JavaScript reads the input, converts it to lowercase.
   - It filters the array using `.filter()` and `.includes()`.
   - The filtered testimonials are rendered live in the DOM.
3. The Clear button removes input text and restores the full list.

---

## 💡 Use Cases

- Resume/portfolio projects
- Beginner-friendly JavaScript DOM practice
- Live search implementation demo

---

## 🖼️ Screenshots

> *(You can add screenshots or a screen recording here)*

---

## 📌 To Run Locally

1. Clone the repository
2. Open `index.html` in a browser

---

## 🙋‍♂️ Author

**Vinay Kalva**  
Full Stack Developer & Cybersecurity Enthusiast  
📫 [Connect on LinkedIn](https://vinay382910.vercel.app/)

---

## 📃 License

This project is licensed under the MIT License.

```
