# Gate Pass Application

## Overview
The Gate Pass Application is a cross-platform mobile application developed using .NET MAUI. It allows students to request gate passes, view the status of their requests, and check the history of past requests. Admins and faculty can approve or reject requests, while security personnel can verify passes using QR codes.

## Features
- **User Roles**:
  - **Student**: Request gate passes, view request status, and check history.
  - **Admin/Faculty**: Approve or reject requests with comments.
  - **Security Personnel**: Scan QR codes to verify approved passes.

- **Functional Requirements**:
  - Secure login using email and password.
  - Input form for gate pass requests.
  - Document upload with validation.
  - Status dashboard for requests.
  - Push notifications for status updates.

## Technical Specifications
- **Frontend Framework**: .NET MAUI
- **Backend**: Firebase Firestore or SQL Server
- **APIs**: ASP.NET Core
- **QR Code Generation**: ZXing.NET library
- **Data Validation**: Ensures all form fields are validated for proper input.
- **Error Handling**: Includes try-catch blocks for graceful error handling.

## Getting Started

### Prerequisites
- .NET 7.0 SDK or later
- Visual Studio 2022 or later with .NET MAUI workload installed
- Xcode (for iOS development)
- Android Studio (for Android development)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/prabhastdvj/GatePass-APP-using-.NET-MAUI.git
   cd GatePassApp
   ```

2. Restore the NuGet packages:
   ```bash
   dotnet restore
   ```

3. Build the project:
   ```bash
   dotnet build
   ```

4. Run the application:
   - For iOS:
     ```bash
     dotnet run -f net7.0-ios
     ```
   - For Android:
     ```bash
     dotnet run -f net7.0-android
     ```
   - For Mac Catalyst:
     ```bash
     dotnet run -f net7.0-maccatalyst
     ```

## Usage
- Launch the application and log in using your credentials.
- Students can request gate passes and view their status.
- Admins can manage requests and provide feedback.
- Security personnel can verify passes using QR codes.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.


## Acknowledgments
- .NET MAUI for cross-platform development.
- Firebase for backend services.
- ZXing.NET for QR code generation.
