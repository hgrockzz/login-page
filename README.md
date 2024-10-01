# Login Page

This project implements a fully functional login page with sign-up, authentication, and suggestions. The following sections detail the features:

## Features

### 1. Sign Up Page
Users can create an account by entering their details and verifying through OTPs.

- **Name**
- **Email**  
  - Send OTP to Email — Verify
- **Set Password**  
  - Re-enter to Confirm
- **Mobile No.**  
  - Send OTP to Phone No. — Verify
- **Sign Up Button**
- **Redirect to Login Page** upon successful sign-up

### 2. Login Page
Users can log in using their registered credentials.

- **Email** (registered with)
- **Password**
- **Log In Button**

### 3. Log In with Popular Platforms
Users can log in using:

- Google
- Facebook
- GitHub
- LinkedIn
- Twitter

### 4. Log Out Option
Users can log out from the account at any time.

### 5. Suggestion Box
A feature allowing users to share feedback or suggestions.

- Request any additional platform for "Log In" integration
- Provide project suggestions
- Share any cool, random thoughts!

## Important Notes

- **Persistent Session**:  
  Once logged in, users will remain logged in, even if they close the tab, browser, or restart their machine.

- **Route Guarding**:  
  If a user attempts to access the homepage or any restricted route without authentication, they will be redirected back to the Login page.

- **Validation**:  
  All text fields will be validated for correct input before submission.

- **Security**:  
  User credentials and details are securely handled and not exposed.
