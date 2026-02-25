# 🏋️‍♀️ FitLife – Healthy Lifestyle Platform

A multi-page web application focused on fitness, nutrition, and healthy living — built with HTML, CSS, JavaScript, and Python as part of a Web Technologies (*Tehnici Web*) university course.

## 📖 About

**FitLife** is a comprehensive healthy lifestyle platform that combines workout guides, nutritious recipes, health tips, and a calorie calculator into a cohesive, visually appealing web experience. The project demonstrates front-end development skills with multiple interconnected pages, responsive design, interactive JavaScript components, and a simple Python-based authentication backend.

## ✨ Features

### 🔐 Authentication
- Login system with a Python backend (`login.py`)
- User data stored in JSON format (`login.json`)
- Custom-styled login page with SVG illustrations

### 🏃 Sport & Workouts
- **Cardio** – Curated cardio workout routines (abs, full body, legs, back) with embedded video recommendations
- **Pilates** – Wall pilates and mat pilates guides with exercise illustrations
- **HIIT** – High-intensity interval training sessions from popular fitness creators
- **Low Impact** – Gentle workout alternatives for all fitness levels
- Dedicated pages with category-specific styling and interactive elements

### 🥗 Recipes & Nutrition
- **Breakfast** (*Mic Dejun*) – Healthy morning recipes: omelettes, overnight oats, granola bowls, eggs & toast
- **Lunch** (*Prânz*) – Balanced midday meal ideas with detailed ingredient lists
- **Dinner** (*Cină*) – Light and nutritious evening recipes
- Recipe filtering and interactive browsing with JavaScript

### 💡 Health Tips (*Sfaturi*)
- Nutrition education: proteins, carbohydrates, fats, fruits & vegetables
- Practical wellness advice with supporting imagery
- Interactive content sections powered by JavaScript

### 🔢 Calorie Calculator
- Interactive calorie calculator (`calckcal.html`)
- Custom-styled input forms
- Real-time calculations with JavaScript (`calckcal.js`)

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Structure** | HTML5 |
| **Styling** | CSS3 (10 dedicated stylesheets) |
| **Interactivity** | Vanilla JavaScript |
| **Backend** | Python (authentication) |
| **Data** | JSON |
| **Assets** | PNG, JPG, SVG |

## 📁 Project Structure

```
Proiect-TehniciWeb/
│
├── index.html              # 🏠 Homepage
├── style.css               # Main stylesheet
├── index.js                # Homepage interactivity
│
├── login.html              # 🔐 Login page
├── login.css               # Login styling
├── login.js                # Login form validation
├── login.py                # Python authentication backend
├── login.json              # User credentials storage
├── login.svg               # Login page illustration
│
├── sport.html              # 🏃 Sport main page
├── sportstyle.css          # Sport page styling
├── sport.js                # Sport page interactivity
│
├── cardio.html             # ❤️ Cardio workouts
├── cardio.css              # Cardio styling
│
├── pilates.html            # 🧘 Pilates workouts
├── pilates.css             # Pilates styling
│
├── retete.html             # 🍽️ Recipes main page
├── retete.css              # Recipes styling
├── retete.js               # Recipe filtering/interaction
│
├── micdejun.html           # 🌅 Breakfast recipes
├── micdejun.css            # Breakfast styling
│
├── pranz.html              # ☀️ Lunch recipes
├── pranz.css               # Lunch styling
│
├── cina.html               # 🌙 Dinner recipes
├── cina.css                # Dinner styling
│
├── sfaturi.html            # 💡 Health tips
├── sfaturi.css             # Tips styling
├── sfaturi.js              # Tips interactivity
│
├── calckcal.html           # 🔢 Calorie calculator
├── calckcal.css            # Calculator styling
├── calckcal.js             # Calculator logic
│
└── *.png / *.jpg / *.svg   # 🖼️ Image assets
```

## 📄 Pages Overview

| Page | File | Description |
|------|------|-------------|
| Homepage | `index.html` | Landing page with navigation to all sections |
| Login | `login.html` | User authentication with Python backend |
| Sport Hub | `sport.html` | Main fitness page linking to workout categories |
| Cardio | `cardio.html` | Cardio workout routines and video guides |
| Pilates | `pilates.html` | Pilates exercises with visual instructions |
| Recipes | `retete.html` | Main recipe page with meal categories |
| Breakfast | `micdejun.html` | Healthy breakfast recipes and ideas |
| Lunch | `pranz.html` | Nutritious lunch recipes |
| Dinner | `cina.html` | Light dinner recipes |
| Health Tips | `sfaturi.html` | Nutrition education and wellness advice |
| Calorie Calculator | `calckcal.html` | Interactive daily calorie calculator |

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge)
- Python 3.x (for the login backend)

### Running the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mirunadragunoi/Proiect-TehniciWeb.git
   cd Proiect-TehniciWeb
   ```

2. **Start the Python backend** (for login functionality):
   ```bash
   python login.py
   ```

3. **Open in browser:**
   - Open `index.html` directly in your browser, or
   - Use a local server:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`

## 📸 Sections Preview

### 🏠 Homepage
The landing page introduces the platform and provides navigation to all major sections: workouts, recipes, health tips, and the calorie calculator.

### 🏃 Workouts
Browse through cardio, pilates, HIIT, and low-impact workout categories, each featuring curated exercise routines with visual guides.

### 🥗 Recipes
Explore healthy recipes organized by meal type — breakfast, lunch, and dinner — with ingredients and preparation details.

### 🔢 Calorie Calculator
Input your personal data to calculate your daily caloric needs and track your nutritional goals.

## 🎓 Academic Context

This project was developed as part of the **Tehnici Web** (Web Technologies) course, demonstrating:
- Multi-page website architecture
- Semantic HTML5 structure
- Custom CSS styling with dedicated stylesheets per page
- Client-side interactivity with vanilla JavaScript
- Basic server-side authentication with Python
- Responsive design principles
- File organization and project structure best practices

## 🤝 Author

**Miruna Drăgunoi** – [@mirunadragunoi](https://github.com/mirunadragunoi)

## 📝 License

This project was created for educational purposes as part of a university course.
