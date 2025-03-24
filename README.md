# Password Manager

## Overview
This is a simple **Password Manager** built with Python using the `tkinter` library for the graphical user interface. The application allows users to:
- Generate secure random passwords.
- Copy passwords to the clipboard automatically.
- Store website credentials in a text file (`data.txt`).

## Features
- **Password Generator:** Creates strong passwords using letters, numbers, and symbols.
- **Clipboard Support:** Automatically copies the generated password.
- **Data Storage:** Saves website, email/username, and password securely in `data.txt`.
- **User-Friendly Interface:** Built with `tkinter` for ease of use.

## Installation
### Prerequisites
Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

### Required Libraries
Install the required libraries using pip:
```bash
pip install pyperclip
```

## How to Run
1. Clone or download the repository.
2. Ensure you have a `logo.png` image in the project directory.
3. Run the Python script:
   ```bash
   python main.py
   ```

## Usage
1. **Enter a Website Name.**
2. **Enter Email/Username.** (Default is prefilled)
3. **Generate a Password** (or enter your own).
4. **Click "Add"** to save the credentials to `data.txt`.

## File Structure
```
project-folder/
│-- main.py         # The main script
│-- data.txt        # Stores saved credentials
│-- logo.png        # App logo image
│-- README.md       # Project documentation
```

## Example of Saved Data
```
website: example.com | username: user@example.com | password: Xy@3kL!9
```

## Contributing
Feel free to contribute by improving features or fixing bugs. Fork the repository and create a pull request!

## License
This project is licensed under the MIT License.

