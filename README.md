# OPHMS

# Operation-Scheduler-For-Hospital-Management

This is a web-based hospital management system designed to streamline various administrative tasks such as managing doctors, patients, and operation schedules.

## Features

- Admin authentication system.
- Doctor management: Add, edit, and delete doctors.
- Patient management: Add, edit, and delete patients.
- Operation scheduling: Schedule operations with detailed information.

## Technologies Used

- HTML, CSS, JavaScript for frontend development.
- Firebase Firestore for database management.
- Firebase Authentication for user authentication.

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/sandhrijohn/OPHMS
   ```

2. Navigate to the project directory:

   ```bash
   cd OPHMS
   ```

3. Install dependencies:

   No external dependencies need to be installed as the project uses Firebase for backend services.

4. Set up Firebase:

   - Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
   - Enable Firestore and Authentication services.
   - Copy the Firebase config object from the Firebase console and replace the values in `firebase-config.js` with your own.
   - Ensure that your Firebase Firestore rules allow read and write access to your collections.

5. Run the application:

   - Open `index.html` in a web browser or set up a local server if necessary.

## Usage

- After setting up the application, login as an admin to manage doctors, patients, and operation schedules.
- Follow the intuitive interface to add, edit, and delete records as needed.

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

---

Feel free to customize the README file according to your project's specific details, such as adding more detailed instructions, screenshots, or additional sections as needed.
