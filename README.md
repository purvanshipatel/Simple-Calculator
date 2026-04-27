#  Simple Calculator (Flutter)

A basic Flutter application that performs arithmetic operations on two user-provided numbers. This project demonstrates handling user input, button interactions, and dynamic UI updates.

---

##  Features

* 🔢 Input two numbers using TextFields
* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* 📊 Displays the calculated result instantly
* 🎨 Simple and user-friendly interface

---

##  Tech Stack

* **Framework:** Flutter
* **Language:** Dart

---

##  Project Structure

```id="calcstruct1"
lib/
 └── main.dart     # Contains UI and calculator logic
```

---

## Getting Started

Follow these steps to run the project locally:

### Prerequisites

* Flutter SDK installed
* Android Studio / VS Code
* Emulator or physical device

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/simple_calculator_flutter.git
   ```

2. Navigate to the project directory:

   ```bash
   cd simple_calculator_flutter
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the application:

   ```bash
   flutter run
   ```

---

##  How It Works

* Users enter two numbers in input fields
* Each operation button performs a calculation:

  * **Addition:** `a + b`
  * **Subtraction:** `a - b`
  * **Multiplication:** `a * b`
  * **Division:** `a / b`
* The result is displayed on the screen using Flutter's state management (`setState()`)

---

##  Notes

* Handles basic input only (numeric values)
* Division by zero should be handled to avoid runtime errors

---

##  Screenshots

*Add screenshots of your app here*

---

##  Future Improvements

* Add input validation and error messages
* Improve UI design with better styling
* Add support for more advanced operations
* Implement history of calculations

---

##  Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

