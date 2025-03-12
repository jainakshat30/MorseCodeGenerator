# Morse Code Generator
## Description

Morse Code Generator is a Java-based application that converts text into Morse code and vice versa. It provides a simple and user-friendly GUI to encode and decode messages efficiently.

## Features

- Convert plain text to Morse code.
- Decode Morse code back to text.
- Graphical User Interface (GUI) for easy interaction.
- Supports alphanumeric characters and common punctuation.

## Technologies Used

- **Java** (Core Logic and GUI)
- **Swing/AWT** (For GUI Development)

## Installation & Usage

### Prerequisites

Ensure you have **Java JDK 8+** installed on your system.

### Steps to Run

1. **Clone the Repository**

   ```sh
   git clone https://github.com/jainakshat30/MorseCodeGenerator.git
   cd MorseCodeGenerator
   ```

2. **Compile the Java Files**

   ```sh
   javac -d out src/*.java
   ```

3. **Run the Application**

   ```sh
   java -cp out MorseCodeTranslatorGUI
   ```

## File Structure

```
MorseCodeGenerator/
├── src/                   # Source code files
│   ├── App.java           # Main application entry point
│   ├── MorseCodeController.java  # Handles encoding/decoding
│   ├── MorseCodeTranslatorGUI.java  # GUI implementation
│
├── out/                   # Compiled class files
├── README.md              # Project documentation
├── .gitignore             # Git ignored files
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## Author

Developed by **Akshat Jain**. If you have any questions or suggestions, feel free to contact me!

