# Render Time Calculator

The **Render Time Calculator** is a lightweight and intuitive web application designed to help animators, video editors, and 3D artists estimate their render times efficiently. It provides two main functionalities:

1. **Calculate Completion Time**: Determine when a render job will finish based on the start time, number of frames, and render time per frame.
2. **Calculate Time Per Frame**: Figure out the maximum allowable render time per frame to meet a specific deadline.

## Features
- **Simple Input Fields**: Quickly input frame ranges, render start/end times, and time per frame.
- **Dark Mode Toggle**: Switch between light and dark themes for comfortable use.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Offline Capability**: Thanks to its PWA (Progressive Web App) functionality, the app can be used offline once loaded.

## How to Use

### Option 1: Calculate Completion Time
1. Enter the **Frame Start** and **Frame End** values.
2. Set the **Render Start Time**.
3. Input the **Time Per Frame** (in seconds).
4. Click the **"Calculate Completion Time"** button to see when the render will finish.

### Option 2: Calculate Time Per Frame
1. Enter the **Frame Start** and **Frame End** values.
2. Set the **Render Start Time** and **Desired Render End Time**.
3. Click the **"Calculate Time Per Frame"** button to determine the maximum time each frame can take.

## Installation

This app is available as a PWA (Progressive Web App). To install:

### On Desktop
1. Open the app in your browser.
2. Click the browser's **install button** (usually in the URL bar or menu).
3. Follow the prompts to add it as a desktop application.

### On Mobile (iOS/Safari)
1. Open the app in Safari.
2. Tap the **Share button**.
3. Select **"Add to Home Screen"**.
4. The app will appear as an icon on your home screen.

### On Mobile (Android/Chrome)
1. Open the app in Chrome.
2. Tap the **three-dot menu**.
3. Select **"Add to Home Screen"**.
4. The app will appear as an icon on your home screen.

## Development Setup

### Prerequisites
- A text editor like VSCode.
- A local web server for testing (e.g., [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VSCode).

### Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RenderCalculator.git
   ```
2. Navigate to the project folder:
   ```bash
   cd RenderCalculator
   ```
3. Open the `index.html` file in your browser, or start a local web server to view it.

## File Structure
```
RenderCalculator/
├── index.html          # Main HTML file
├── manifest.json       # Web App Manifest for PWA functionality
├── service-worker.js   # Service Worker for offline support
├── styles.css          # Custom styles (inline styles are used in the current version)
```

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request with detailed information about your changes.

## License
This project is licensed under the [MIT License](LICENSE).

---

For any inquiries or suggestions, feel free to reach out to us at [contact@yourstudio.com](mailto:contact@yourstudio.com).

