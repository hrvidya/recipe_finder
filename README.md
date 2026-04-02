# 🍽️ AI Recipe Finder

🚀 AI-powered Recipe Finder using Django & Image Processing

---

## 🧠 Overview

**AI Recipe Finder** is a smart web application that helps users discover recipes using ingredients or food images.
It combines **Django backend + Image Processing + AI logic** to deliver intelligent and interactive recipe recommendations.

---

## ✨ Key Features

* 🖼️ Image-based Recipe Detection (AI/ML)
* 🔍 Ingredient-based search
* ⚡ Fast Django backend
* 🎨 Clean UI using templates & static files
* 📦 Scalable project structure

---

## 🤖 AI / Image Processing

This project uses basic **image processing techniques**:

* Image input handling
* Feature extraction (via `encoder.py`)
* Mapping food images → recipes
* Extendable with:

  * CNN models
  * OpenCV
  * TensorFlow / PyTorch

---

## 🛠️ Tech Stack

| Category | Technology       |
| -------- | ---------------- |
| Backend  | Django           |
| Language | Python           |
| Frontend | HTML, CSS        |
| AI/ML    | Image Processing |
| Database | SQLite           |

---

## 📂 Project Structure

```
mini project/
│
├── Source Code/
│   └── RecipeFinder/
│       └── src/
│           └── main/
│               ├── migrations/
│               ├── static/
│               ├── templates/
│               ├── encoder.py   # AI logic
│               ├── models.py
│               ├── views.py
│               ├── urls.py
│
├── manage.py
└── requirements.txt
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/hrvidya/recipe_finder.git
cd recipe_finder
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Migrations

```bash
python manage.py migrate
```

### 5️⃣ Run Server

```bash
python manage.py runserver
```

---

## 🌐 Usage

* Open browser and go to:
  http://127.0.0.1:8000/

* Enter ingredients OR upload food image

* Get recipe suggestions instantly 🍜

---

## 📸 Screenshots

👉 Add these for better impact:

* Home Page
* Input Page
* Results Page

---

## 🚀 Future Enhancements

* 🔥 Deep Learning model (CNN)
* 📱 Mobile responsive UI
* ☁️ Cloud deployment (AWS / Render)
* 🧾 Nutritional analysis

---

## 🙌 Author

**HR Vidya**
🔗 https://github.com/hrvidya

---

## ⭐ Support

If you like this project:
👉 Star ⭐ the repository
👉 Share with others

---

## 📜 License

This project is licensed under the MIT License.
