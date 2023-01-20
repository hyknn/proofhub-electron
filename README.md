# About

Unofficial client for ProofHub providing a native Linux desktop experince and some additional features.

## Disclaimer

This project and its contributors are not affiliated with ProofHub, nor it's product. This repository does not contain any ProofHub software. It is simply an Electron wrapper that loads the official ProofHub web application page, just as it would in a regular web browser.

## How to use

1. Clone the repo
2. Edit homepage on script/main.js

    ```sh
    var homePage = 'https://xyz.proofhub.com/'; // Put your company's ProofHub URL here
    ```
3. Build the apps

    ```sh
    npm run build
    ```
4. Run the output AppImage or install it via deb package
