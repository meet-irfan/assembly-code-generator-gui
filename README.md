# assembly-code-generator-gui
A Python-based application that generates assembly code for mathematical expressions using a stack-based approach. Includes a user-friendly GUI built with tkinter for ease of use.
 # GUI Code 
  # Assembly Code Generator with GUI

This project is a Python application that generates assembly code for arithmetic expressions. The application uses a stack-based approach to convert infix expressions into postfix notation and then generates corresponding assembly instructions. The project includes a user-friendly GUI built using `tkinter`.

---

## Features

- Input arithmetic expressions in infix notation.
- Generates assembly code for basic operations: `+`, `-`, `*`, `/`.
- Error handling for invalid expressions.
- Clean and interactive GUI for user input and output.

---

## How to Run the Project

### Prerequisites
- Python 3.7 or higher installed on your system.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/assembly-code-generator-gui.git
Navigate to the project directory:

bash
Copy code
cd assembly-code-generator-gui
Run the script:

bash
Copy code
python assembly_code_gui.py
Usage
Enter a mathematical expression (e.g., 3 + 5 * ( 2 - 8 )) into the input field.
Click on "Generate Assembly Code."
View the generated assembly code in the output text box.
Example Input and Output
Input:
scss
Copy code
( 3 + 5 ) * 2 - 8 / 4
Output:
css
Copy code
PUSH 3
PUSH 5
ADD A, B
PUSH A
PUSH 2
MUL A, B
PUSH A
PUSH 8
PUSH 4
DIV A, B
PUSH A
SUB A, B
PUSH A
Project Structure
assembly_code_gui.py : Main script containing the code for GUI and assembly generation.
Technologies Used
Python
tkinter (for GUI)
Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
Developed by Irfan Ali Narejo. If you have any questions, feel free to reach out at irfanalinarejo842@gmail.com.

yaml
Copy code

---

### Steps to Upload the Project to GitHub

1. **Initialize a Git Repository**:
   ```bash
   git init
Add Files to the Repository:

bash
Copy code
git add .
Commit the Changes:

bash
Copy code
git commit -m "Initial commit: Assembly Code Generator with GUI"
Create a Repository on GitHub:

Go to your GitHub account.
Click on New Repository.
Name the repository assembly-code-generator-gui.
Add a short description: A Python-based GUI for generating assembly code from mathematical expressions.
Create the repository.
Link the Local Repository to GitHub:

bash
Copy code
git remote add origin https://github.com/your-username/assembly-code-generator-gui.git
Push the Code to GitHub:

bash
Copy code
git branch -M main
git push -u origin main
