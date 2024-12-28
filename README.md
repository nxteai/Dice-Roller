
# Dice Roller App

A simple Android app built with Jetpack Compose to simulate rolling a dice.

## Features

- Displays a dice image corresponding to the rolled number.
- Allows users to roll the dice by pressing a button.
- Built with Jetpack Compose and Material3 for modern UI design.

## Screenshots

![Screenshot](src/main/Screenshot%202024-12-28%20041302.png)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nxteai/Dice-Roller.git
   ```
2. Open the project in **Android Studio**.
3. Sync the Gradle files.
4. Run the app on an emulator or connected Android device.

## Usage

1. Launch the app.
2. Tap the **Roll** button to roll the dice.
3. The dice image will update to reflect the result.

## Requirements

- Android Studio Arctic Fox or newer.
- An Android device/emulator running Android 5.0 (Lollipop) or higher.

## How It Works

- The app uses `mutableStateOf` to store the current dice value.
- A random number between 1 and 6 is generated when the button is clicked.
- The corresponding dice image is displayed using `painterResource`.

## Future Improvements

- Add animations to make the dice roll more interactive.
- Support multi-dice rolling.
- Include themes and customizable dice styles.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
