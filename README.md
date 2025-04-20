# flutter-mobile-cos-work-app
Key Features
1. Authentication System
Login Screen: Secure login with username/password validation

Signup Screen: Account creation with form fields for first name, last name, email, and password

Splash Screen: 5-second introductory screen before login

2. Main Navigation
Drawer Navigation: Side menu with options for Home, Profile, Support, and Settings

Bottom Navigation: Alternative navigation pattern (though currently commented out)

3. Apartment Information
Room Displays: Interactive cards for different apartment areas (Living Room, Bed Room, Kitchen, etc.)

Room Details: Each room has a descriptive image and text overlay

4. Support System
Contact Options: Phone, email, and office location cards

Message Form: Text field for submitting support requests

5. User Profile
Profile View: Displays resident information including:

Contact details

Lease duration

Rent status

Parking spot

Emergency contacts

6. Settings
Account Management: Edit profile and change password options

Preferences: Notification and dark mode toggles

App Information: About section and logout functionality

Technical Implementation
Code Structure
Main Entry Point: main.dart initializes the app with SplashScreen

Screen Separation: Each major feature has its own Dart file

State Management: Uses basic setState for UI updates

Navigation: Navigator for screen transitions

UI Components
Consistent Styling: Green color theme throughout

Reusable Widgets: RoomCard component for consistent room displays

Form Validation: Login form includes input validation

Assets
Images: Uses local assets for room pictures and apartment logo

Icons: Material icons for consistent UI elements
Group Members & Contributions
This project was collaboratively developed by:

Olema Swaib


Contributions: [Brief description, e.g., "Implemented the login/signup authentication flow"]

Shanita Atukunda


Contributions: [e.g., "Designed the HomeScreen room selection interface"]

Kiza Gertrude



Contributions: [e.g., "Developed the SupportScreen contact form and validation"]

Mutonye Doreen Watnya



Contributions: [e.g., "Integrated navigation drawer and profile management"]

Nambale Kelly


Contributions: [e.g., "Led project coordination and settings screen implementation"]



Potential Improvements
State Management: Consider using provider or bloc for more complex state

Navigation: Implement named routes for better navigation management

Authentication: Add actual backend integration instead of hardcoded credentials

Responsiveness: Ensure UI works well on all device sizes

Local Storage: Add persistence for user preferences

Error Handling: More robust error handling for forms and network operations

Testing: Add unit and widget tests

Setup Instructions
Ensure Flutter SDK is installed

Add all image assets to the assets/images/ directory

Run flutter pub get to install dependencies

Launch with flutter run
