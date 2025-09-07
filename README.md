# Docdoc - Telemedicine Application

## Overview

Docdoc is a Flutter-based telemedicine platform that connects patients with healthcare providers. The app enables users to book virtual or in-person consultations, search for specialists, manage appointments, and communicate with doctors.

## Demo Video

<p align="center">
  <a href="https://drive.google.com/file/d/1KwKZ4ic5PyeOHSjF1_v5gm3D3xjCamCB/view?usp=sharing" target="_blank">
    <b>▶ Watch Demo</b>
  </a>
</p>

## Features

### Doctor Discovery
- Search for doctors by name, specialty, or availability
- Browse medical specialties (Cardiology, Dermatology, Orthopedics, etc.)
- View detailed doctor profiles with qualifications and reviews

### Appointment Management
- Book virtual or in-person consultations
- Select convenient appointment slots
- Track upcoming, completed, and canceled appointments
- Reschedule or cancel appointments as needed

### Communication
- Real-time chat with healthcare providers
- Receive appointment notifications and reminders

### User Management
- Manage personal profile and medical history
- Secure authentication system
- Customize app settings and preferences

### Payment Integration
- Support for multiple payment methods
- Track payment history

## Project Structure



```
lib/
├── core/                 # Core functionality
│   ├── app/              # App setup
│   ├── cache/            # Local storage
│   ├── constants/        # App constants
│   ├── database/         # API endpoints
│   ├── function/         # Helper functions
│   ├── router/           # Navigation
│   ├── services/         # Service locator
│   └── utils/            # Utilities
│
└── features/             # App features
    ├── auth/             # Authentication
    ├── home/             # Home screen
    ├── Inbox/            # Messaging
    ├── my_appointment/   # Appointments
    ├── onBoarding/       # Onboarding
    ├── profile/          # User profile
    ├── search/           # Search
    └── splash/           # Splash screen
```

## Technologies

- **State Management**: flutter_bloc (v8.1.6)
- **Navigation**: go_router (v14.2.3)
- **UI Components**: 
  - flutter_svg (v2.0.10+1)
  - easy_date_timeline (v1.1.3)
  - flutter_datetime_picker_plus (v2.2.0)
  - chat_bubbles (v1.6.0)
- **Data Management**:
  - get_it (v7.7.0)
  - shared_preferences (v2.3.1)
  - http (v1.2.2)
- **App Configuration**:
  - flutter_native_splash (v2.4.1)
  - flutter_launcher_icons (v0.13.1)

## Getting Started

### Prerequisites
- Flutter SDK (>=3.4.3)
- Dart SDK (>=3.4.3)
- Android Studio / VS Code

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/docdoc.git
   cd docdoc
   ```

2. Install dependencies
   ```bash
   flutter pub get
   ```

3. Run the app
   ```bash
   flutter run
   ```

## Architecture

The app follows a clean architecture approach with:
- **Presentation Layer**: BLoC/Cubit pattern for state management
- **Domain Layer**: Business logic and use cases
- **Data Layer**: API and local storage data handling

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

---

Built with ❤️ using Flutter.
