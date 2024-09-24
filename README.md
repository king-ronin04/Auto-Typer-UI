# Auto Typer - Java Version

This is a simple **Auto Typer** application built in Java using the Swing library for the GUI and the `Robot` class for automating keyboard inputs. It allows users to input text and then automatically types it out with a specified delay between each character.

## Features
- **GUI**: A user-friendly graphical interface to input the text to be auto-typed.
- **Adjustable Speed**: Allows users to set a typing speed in milliseconds between characters.
- **Auto Typing**: The program automatically types the input text when triggered.

## How It Works
1. The user enters the text to be typed in the text area.
2. The user specifies the typing speed (in milliseconds per character).
3. After clicking the "Start Auto Typer" button, the program waits 3 seconds to allow the user to focus on the target window.
4. The program then automatically types the entered text at the specified speed.

## Dependencies
- Java Development Kit (JDK) 8 or higher.
- `javax.swing` for the graphical user interface.
- `java.awt.Robot` for simulating keyboard presses.

## How to Run
1. Compile the Java file using the following command:
    ```bash
    javac AutoTyper.java
    ```
2. Run the compiled class file:
    ```bash
    java AutoTyper.class
    ```

## Usage
1. Enter the text you want to be typed in the provided text area.
2. Set the typing speed in milliseconds (default is 100ms per character).
3. Click the **Start Auto Typer** button.
4. Switch to the target window where you want the text to be typed (you have 3 seconds before it starts typing).

## Example
- Input: `Hello World!`
- Typing speed: `100 ms per character`
- The program will type out `Hello World!` with a delay of 100 milliseconds between each character.

## Future Enhancements
- Add support for more complex text formatting (e.g., special characters).
- Allow stopping the typing process midway.
- Implement additional control features like pausing or resuming the typing.
