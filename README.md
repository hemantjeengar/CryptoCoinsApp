# CryptoCoinsApp

A modern Android cryptocurrency application built with **Kotlin** and **Jetpack Compose**. This app fetches a list of cryptocurrencies from the **CoinPaprika API** and displays their details. It follows a modular, scalable architecture, adhering to **Clean Architecture** principles and the **MVVM (Model-View-ViewModel)** design pattern.

## ✨ Features

- **Coin List:** Displays a list of popular cryptocurrencies.
- **Coin Details:** Shows detailed information for a selected cryptocurrency.
- **API Integration:** Fetches data from the CoinPaprika API.
- **UI:** A beautiful, responsive user interface built entirely with Jetpack Compose.
- **Architecture:** Implements Clean Architecture and MVVM for a clear separation of concerns.

## 🧱 Architecture

The project is structured to ensure maintainability and testability:

- **Presentation Layer:** The UI components built with Jetpack Compose and ViewModels that handle the UI logic.
- **Domain Layer:** Contains the core business logic, including use cases and models. This layer is independent of any framework.
- **Data Layer:** Manages data sources (e.g., remote API) and repositories that provide a clean API to the domain layer.

## 🛠️ Technologies Used

- **Language:** Kotlin
- **UI Toolkit:** Jetpack Compose
- **Networking:** Retrofit
- **Dependency Injection:** Hilt
- **Asynchronous Operations:** Kotlin Coroutines & Flow

## 🚀 Getting Started

1.  Clone the repository:
    ```bash
    git clone [https://github.com/hemantjeengar/CryptoCoinsApp.git](https://github.com/hemantjeengar/CryptoCoinsApp.git)
    ```
2.  Open the project in Android Studio.
3.  Build and run the app on an emulator or a physical device.

---
