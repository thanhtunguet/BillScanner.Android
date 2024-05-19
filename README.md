Certainly! Here's the updated `README.md` file with your information:

```markdown
# Bill Scanner App

![Build Status](https://github.com/thanhtunguet/BillScanner.Android/workflows/Android%20CI/badge.svg)

Bill Scanner is an Android application that allows users to capture images of their bills and extract text from them using Optical Character Recognition (OCR) technology.

## Features

- Capture bills using the device camera
- Detect and recognize text from captured images
- Display extracted text for user review
- Save and manage scanned bills

## Technologies Used

- **Android SDK**: Native Android development
- **CameraX**: For camera functionality
- **ML Kit**: For text recognition

## Getting Started

### Prerequisites

- Android Studio 4.0 or higher
- Android device or emulator running Android 5.0 (Lollipop) or higher

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thanhtunguet/BillScanner.Android.git
   cd BillScanner.Android
   ```

2. Open the project in Android Studio.

3. Build the project:
    - Select `Build > Make Project` from the menu.
    - Ensure there are no build errors.

4. Run the app:
    - Connect an Android device or start an emulator.
    - Select `Run > Run 'app'`.

## Usage

1. Launch the Bill Scanner app on your Android device.
2. Point the camera at a bill and press the capture button.
3. The app will process the image and display the extracted text.
4. Review the text and save the scan if desired.

## CI/CD with GitHub Actions

This project includes a GitHub Actions workflow for continuous integration. The workflow:
- Builds the project on every push and pull request to the `main` branch.
- Publishes the APK as an artifact.

### Workflow Configuration

The workflow is defined in `.github/workflows/build.yml`.

### Build Status

![Build Status](https://github.com/thanhtunguet/BillScanner.Android/workflows/Android%20CI/badge.svg)

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please open an issue or contact [ht@thanhtunguet.info](mailto:ht@thanhtunguet.info).
```

### Notes:

- The badge URLs and repository URLs have been updated to match your GitHub username `thanhtunguet`.
- Your contact email has been included in the "Contact" section.
- Replace the placeholder text in any specific project details if necessary.
