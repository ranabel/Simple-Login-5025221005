# 📱 Simple Login App with Jetpack Compose
  **Nama:** Nabilah Atika Rahma  
  **NRP:** 5025221005  
  **Kelas:** PPB G - Week 7

## 📝 Overview
This is a simple login screen implementation using **Jetpack Compose** for Android. The UI features a clean, modern design with email/password fields, social login options, and basic credential logging functionality.

## ✨ Features
- Email and password input fields
- Password visibility toggle *(feature can be added)*
- Login button with credential logging
- "Forgot Password" option
- Social login options (Facebook, Google, Twitter)
- Responsive layout that works on different screen sizes
- Clean Material Design aesthetics

## 📸 Screenshots
*(You can add screenshots of your app here)*

## ⚙️ Implementation Details

### 📦 Main Components
- `LoginScreen()` - The main composable that builds the entire login interface
- `SocialIcon()` - Reusable component for social login buttons

### 🧑‍💻 Technical Highlights
- Uses **Material 3** components (`TextField`, `Button`, `Card`)
- State management with `remember` and `mutableStateOf`
- Custom styling for buttons and text fields
- Proper spacing and alignment with `Spacer`, `Row`, and `Column`
- Click handlers for login and social buttons

## 🚀 Usage
1. Enter your email and password.
2. Click the **Login** button (credentials will be logged to Logcat).
3. Alternatively, use one of the social login options (clicks are logged).

## 🎨 Customization
To customize this screen:
- Replace the image resources (currently using placeholder `R.drawable.a`).
- Modify the social icons by updating the drawable resources.
- Adjust padding and spacing values as needed.

## 👩‍💻 Author
**Nabilah Atika Rahma**  
**NRP**: 5025221005

## ⚠️ Note
This is a sample implementation for educational purposes. In a production app:
- Add proper credential validation
- Implement secure authentication
- Remove credential logging from production code
- Add proper error handling
