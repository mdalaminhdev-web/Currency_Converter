# 💱 Currency Converter

A modern and responsive **Currency Converter** built with **React.js** that converts currencies using real-time exchange rates from an external API.

This project was built to practice **React Hooks, API integration, state management, form handling, input validation, and modern CSS design**.

---

## 🚀 Features

* 🌍 Select source and target currencies
* 🏳️ Display currency flags
* 💱 Display currency codes
* 💰 Enter custom amount for conversion
* 🔄 Real-time currency conversion
* 📡 Exchange Rate API integration
* ⚛️ React `useState` and `useEffect`
* ✅ Input validation
* 📱 Responsive design
* 🪟 Modern glassmorphism-style UI
* ⚡ Fast and interactive user experience

---

## 🛠️ Technologies Used

* **React.js**
* **JavaScript (ES6+)**
* **HTML5**
* **CSS3**
* **Vite**
* **REST API**
* **React Hooks**

---

## 🧠 What I Learned

Building this project helped me practice and understand:

* How to consume data from an external API
* Fetching data using JavaScript
* Working with asynchronous operations
* Managing state with `useState`
* Handling side effects with `useEffect`
* Handling form inputs in React
* Performing basic input validation
* Rendering dynamic API data
* Working with currency exchange rates
* Creating reusable React components
* Building responsive layouts
* Applying modern CSS techniques
* Structuring and deploying a React project

---

## 🔄 How It Works

The application follows a simple conversion flow:

```text
Select From Currency
        ↓
Select To Currency
        ↓
Enter Amount
        ↓
Fetch Exchange Rate
        ↓
Calculate Conversion
        ↓
Display Converted Amount
```

---

## 💻 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/mdalaminhdev-web/Currency_Converter.git
```

### 2. Navigate to the project

```bash
cd Currency_Converter
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

### 5. Open in browser

```text
http://localhost:5173
```

---

## 📡 API Integration

This application uses an external **Exchange Rate API** to retrieve currency exchange rates.

The selected currencies are sent to the API, and the returned exchange rate is used to calculate the converted amount.

The general conversion process is:

```text
Amount × Exchange Rate = Converted Amount
```

---

## 📁 Project Structure

```text
Currency_Converter/
│
├── public/
│
├── src/
│   ├── assets/
│   ├── components/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

> The exact folder structure may vary depending on the current implementation of the project.

---

## 🎨 UI Design

The project uses a clean and modern **glassmorphism-inspired interface**.

### Design Elements

* Glass-style card
* Rounded UI components
* Blur effects
* Soft shadows
* Modern typography
* Clean spacing
* Responsive layout
* Interactive form controls

The main goal was to keep the interface **simple, modern, and easy to use**.

---

## 📚 React Concepts Used

### `useState`

Used to manage:

* Selected currencies
* Amount
* Exchange rate
* Converted value
* API-related state

### `useEffect`

Used to:

* Fetch exchange-rate data
* Respond to currency changes
* Update conversion results

---

## 🔮 Future Improvements

Possible improvements for future versions:

* 🔄 Swap currencies button
* 🕘 Conversion history
* ⭐ Favorite currencies
* 📊 Historical exchange-rate charts
* 🌙 Dark/Light mode
* 📈 Exchange-rate trends
* 📱 Further mobile optimization
* 🌐 Support for more currencies

---

## 👨‍💻 Author

### Md Al Amin Hossain

**Software Engineer Intern | Aspiring Full-Stack / MERN Developer**

I'm currently focusing on building practical web applications and improving my skills in JavaScript, React.js, Node.js, Express.js, databases, APIs, and full-stack development.

### Connect With Me

* 💻 GitHub: https://github.com/mdalaminhdev-web
* 💼 LinkedIn: https://www.linkedin.com/in/mdalaminh271/
* 📧 Email: [mdalaminh.dev@gmail.com](mailto:mdalaminh.dev@gmail.com)

---

## ⭐ Support

If you found this project useful or interesting, feel free to **star ⭐ the repository**.

---

### Built with ❤️ using React.js
