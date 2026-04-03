# BMI Calculator

## About the Project

BMI Calculator is an Android application designed to help users understand their body mass index (BMI) in a simple and accessible way. The app lets the user enter weight and height, calculates the BMI, classifies the result, and shows a dedicated screen with a message for each category.

The project focuses on clarity, validation, and navigation across multiple Android screens. It also includes lifecycle logging to help observe how each Activity behaves during execution.

## Student Information

- Name: Gabriel Henrique Coelho Marussi
- Course: Computer Science - FECAP NACCOMP3
- Student ID: 24026609

## Features

- BMI calculation based on the user's weight and height.
- BMI classification with dedicated screens for each category.
- Personalized messages for underweight, normal weight, overweight, and obesity ranges.
- Input validation to prevent empty fields, invalid values, and negative numbers.
- Multi-screen Android navigation using Intents.
- Activity lifecycle logging for basic runtime monitoring.

## How It Works

1. The user opens the app and starts the BMI calculator.
2. Weight and height are entered in the form.
3. The app validates the input values.
4. The BMI is calculated using the formula weight / (height * height).
5. The app routes the user to the correct result screen based on the BMI range.

## BMI Classification

| BMI Range | Classification |
| --- | --- |
| Below 18.5 | Underweight |
| 18.5 to 24.9 | Normal weight |
| 25.0 to 29.9 | Overweight |
| 30.0 to 34.9 | Obesity Class 1 |
| 35.0 to 39.9 | Obesity Class 2 |
| 40.0 and above | Obesity Class 3 |

## Project Structure

- app/src/main/java/com/example/CalculadoraIMC - Android Activities and app logic.
- app/src/main/res/layout - XML layouts for each screen.
- app/src/main/res/values - Strings, colors, and themes.
- app/src/main/AndroidManifest.xml - Application and Activity declarations.

## Requirements

- Android Studio.
- Java 11.
- Android SDK 35 or compatible.
- Minimum SDK 24.

## Running the Project

1. Open the project in Android Studio.
2. Let Gradle sync finish.
3. Run the app on an emulator or physical Android device.

## Download APK

- [APK file](https://github.com/gabmarussi/CalculadoraIMC/raw/refs/heads/main/CalculadoraIMC.apk)
- [ZIP file](https://github.com/gabmarussi/CalculadoraIMC/raw/refs/heads/main/CalculadoraIMC.zip)

## Future Improvements

- Dark mode support.
- Database integration to store BMI history.
- Charts to visualize BMI trends over time.
- Health suggestions based on the user's BMI.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
