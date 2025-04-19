# Illegal Temple Marker System

## Overview

This project is designed to allow users to upload pictures and tag locations using the Google Maps API. The system is intended to mark illegal temples based on user confirmations. It includes features for user registration, image uploads, and role-based management.

## Features

- **User Registration**: Users can register and log in using Google OAuth.
- **Image Upload**: Users can upload images and tag locations.
- **Confirmation System**: Images are classified as illegal temples after 30 user confirmations.
- **PDF Upload**: Users can upload PDF proof to deny illegal temple classification.
- **Role Management**: Superadmin and Admin roles for system management.
- **Ads Management**: Admins can approve ads uploaded by premium users.

## Technologies

- **Backend**: Node.js, Express.js
- **Database**: MariaDB
- **Frontend**: Bootstrap
- **Authentication**: Google OAuth
- **Maps**: Google Maps API

### Project Structure

1. **Backend**: Node.js with Express.js for handling API requests and interactions with the database.
2. **Database**: MariaDB for storing user data, uploaded images, tags, confirmations, and user roles.
3. **Frontend**: Bootstrap for responsive design, suitable for both desktop and mobile.
4. **Authentication**: Google OAuth for user registration and login.
5. **Google Maps API**: For tagging locations on uploaded images.

## Setup

### Prerequisites

- Node.js
- MariaDB
- Google Cloud account for Maps API and OAuth setup

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/user/harampark.git
   ```

2. Install dependencies:
   ```bash
   cd harampark
   npm install
   ```

3. Set up the database:
   - Create a MariaDB database and user.
   - Import the provided SQL schema.

4. Configure environment variables:
   - Create a `.env` file with your Google OAuth credentials and database connection details.

5. Start the server:
   ```bash
   npm start
   ```

## Usage

- Access the application at `http://localhost:3000`.
- Register using Google OAuth.
- Upload images and tag locations.
- Confirm or deny illegal temple classifications.

## Contributing

Please submit pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
```

### Suggestions

- **Security**: Ensure secure handling of user data and uploaded files.
- **Scalability**: Consider using cloud services for hosting and database management.
- **Testing**: Implement unit and integration tests for reliability.# harampark
