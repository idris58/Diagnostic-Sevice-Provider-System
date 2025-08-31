# Diagnostic Management System

## Overview

The Diagnostic Management System is a Windows Forms application built on .NET Framework 4.7.2. It streamlines the management of diagnostic centers, patient registrations, service selection, payments, and reviews. The system is designed for ease of use, providing a seamless experience for both administrators and patients.

## Features

- **User Registration & Login:** Secure registration and authentication for patients and administrators.
- **Diagnostic Center Listing:** Browse and search diagnostic centers with detailed information and average ratings.
- **Service Selection:** View and select available diagnostic services/tests for each center.
- **Payment Processing:** Confirm payments using multiple payment methods (Bkash, Nagod, Rocket, Upay) and track payment details.
- **Order Management:** Automatically records orders and associates them with patients and diagnostic centers.
- **Review & Rating:** Patients can submit star ratings and comments for services received.
- **Admin Dashboard:** Manage diagnostic centers, services, and view analytics.

## Technologies Used

- **Platform:** Windows Forms (.NET Framework 4.7.2)
- **Language:** C#
- **UI:** WinForms
- **Database:** SQL Server
- **ORM:** Entity Framework
- **Version Control:** Git
- **IDE:** Visual Studio

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/idris58/Diagnostic-Sevice-Provider-System.git
   ```
2. **Open in Visual Studio 2022:**
   - Open the solution file (`.sln`) in Visual Studio 2022.
3. **Database Configuration**
- Ensure SQL Server is running.
- Create a database named `DSPS`.
- Set up tables: `Login`, `Patient`, `Diagnostic_Center`, `Services`, `DiagnosticCenterService`, `Orders`, `Payment`, `Rating`.
- Update the connection string in the code according to yours:
  ```
  Data Source=DESKTOP-XXXXX;Initial Catalog=DSPS;Integrated Security=True
  ```
4. **Build and run the project.**

## Usage

- **Register as a new user or login with existing credentials.**
- **Browse diagnostic centers, view details, and select services.**
- **Proceed to payment, choose a payment method, and confirm.**
- **Submit a review and star rating after payment.**
- **Admins can access the dashboard for management tasks.**

## Screenshots

> Add

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please submit issues or pull requests for improvements or bug fixes.

## Contact
*For any issues or feature requests, please open an issue in the repository.*
