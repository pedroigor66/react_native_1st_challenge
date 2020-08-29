# Table of contents
- [About](#about)
- [Main libs and techs used](#-main-libs-and-techs-used)
- [Downloading and setting up the project](#-downloading-and-setting-up-the-project)
- [Usage](#usage)
- [License & copyright](#license--copyright)

## About

In this project a mobile App was developed for Android and iOS using React Native. The App was developed and tested using Android Studio to emulate an Android phone. This project was done during Rocketseat's GoStack bootcamp challenge.

---

## 👨‍💻 Main libs and techs used

This project was developed using the following techs:

- [React](https://reactnative.dev/)
- [CSS with Styled Components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [Android Studio](https://developer.android.com/studio)

---

## 🔧 Downloading and setting up the project

Simply clone this template or download it to your device and run the command `yarn` on your terminal to install all required dependencies. </br>
To make sure everything is running properly, run `yarn test`. </br>
To run the App on your emulator, make sure the **api.ts** file inside the services folder is configured correctly. It is now set as `baseURL: 'http://10.0.2.2:3333',` to run on Android Studio's Android emulator. Use `baseURL: 'http://localhost:3333',` to run the App on an iOS emulator. </br>
To run the fake API server in order to load the products in the Dashboard page, run the command `yarn json-server server.json -p 3333` in a terminal inside the App's root folder. </br>

---

## Layout and usage

The usage is very intuitive and simple: in the Dashboard page that the App launches on, simply click on the `+` sign to add the desired product to the cart. To review your cart, press on the cart icon on the bottom section of the App. In the cart page, previously added products can have their quantities increased or decreased as desired. </br>

This is how the app pages should look like:
</br>
</br>
</br>

![app_pages](/src/assets/app_pages.png)

</br>
</br>
</br>


## License & copyright

Developed by Pedro Igor C. de Oliveira.

Licensed under the [MIT License](LICENSE).
