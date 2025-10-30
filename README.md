# MoneyLeek

A React Native mobile application for managing financial circles and payments.

## Features

- User Authentication (Login/Signup)
- OTP Verification
- CNIC Upload and Verification
- Circle Management
  - Create and View Circles
  - Join Existing Circles
  - Circle Payment Management
- Payment Settings
- Profile Management
- Push Notifications

## Project Structure

```
├── assets/            # Static assets (fonts, images)
├── components/        # Reusable UI components
├── constants/         # App-wide constants
├── navigation/        # Navigation configuration
├── screens/          # Screen components
├── store/            # Redux store setup
│   ├── actions/      # Redux actions
│   ├── reducers/     # Redux reducers
│   └── services/     # API services
└── utils/            # Utility functions
```

## Prerequisites

- Node.js
- npm or yarn
- React Native development environment setup
- iOS Simulator (for iOS) or Android Emulator (for Android)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/superdev947/moneyleek.git
cd moneyleek
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

4. Run the application:

For iOS:
```bash
npm run ios
# or
yarn ios
```

For Android:
```bash
npm run android
# or
yarn android
```

## Technology Stack

- React Native
- Redux for state management
- Native Base UI components
- React Navigation for routing

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
