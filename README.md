# mobile-automation-testing-ecommerce-appium
# Mobile Automation Testing – E-Commerce App (Appium)

This project demonstrates automated testing of an e-commerce mobile application using Appium. Test cases cover login, product search, add to cart, and checkout workflows.

## 🔧 Tools Used

- Appium
- Java + TestNG
- Maven
- Android Emulator
- Allure Reporting

## 🚀 Features Tested

- Login & Logout
- Product Search
- Add/Remove Items from Cart
- Checkout Process
- Profile Management

## 📂 Folder Structure
mobile-automation-testing-ecommerce-appium/
│
├── src/
│   ├── test/
│   │   ├── java/                       # or /python/ or /js/ based on your language
│   │   │   ├── tests/
│   │   │   │   ├── LoginTest.java
│   │   │   │   ├── CartTest.java
│   │   │   │   └── CheckoutTest.java
│   │   │   └── utils/
│   │   │       ├── DriverManager.java
│   │   │       └── TestDataReader.java
│
├── testng.xml                         # or pytest.ini / mocha config
├── pom.xml                            # or build.gradle / package.json
├── app/
│   └── ecommerce-demo.apk             # sample app
├── README.md
├── .gitignore
└── reports/                           # auto-generated test reports

## ▶️ How to Run Tests

1. Start Appium server
2. Connect an emulator or device
3. Run tests using:

```bash
mvn clean test
