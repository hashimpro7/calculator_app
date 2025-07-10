# 🔢 Flutter Calculator App

A beautifully designed and fully functional calculator app built using **Flutter**. This project was created to strengthen my understanding of Dart, Flutter widgets, state management, and expression parsing in mobile app development.

---

## ✨ Features

- ✅ Basic arithmetic operations: `+`, `-`, `x`, `/`, `%`
- ✅ Clean and intuitive user interface
- ✅ Real-time input display and output evaluation
- ✅ Functional `AC`, `DEL`, and `=` buttons
- ✅ Decimal support
- ✅ Reusable custom button widget (`MyButton`)
- ✅ Handles input parsing and operator replacement (`x` ➝ `*`)
- ✅ Uses the `math_expressions` package for expression evaluation

---

## 🧠 What I Learned

- How to create **custom reusable widgets**
- Managing **state** using `setState()` effectively
- Parsing user input and performing **expression evaluation**
- Handling **UI layouts** using Rows and Columns
- Implementing **safe edge case handling** like deletion and empty strings

---

## 🛠️ Tech Stack

| Tech            | Description                          |
|-----------------|--------------------------------------|
| Flutter         | UI toolkit for building natively compiled applications |
| Dart            | Programming language used with Flutter |
| math_expressions | Package used to parse and evaluate math expressions |
| Widgets Used    | `Scaffold`, `SafeArea`, `Column`, `Row`, `Expanded`, `InkWell`, `Container`, etc. |

---

## 📂 Project Structure

lib/
│
├── components/
│ └── my_button.dart # Custom reusable button widget
│
├── main.dart # Entry point of the app
└── home_page.dart # Main calculator logic and UI


