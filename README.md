# WifiGate: ESP32-Based Wi-Fi Access Control with Captive Portal and Google Authentication  

**SEO Keywords:** ESP32 Wi-Fi Access Control, Captive Portal with Google Auth, Wi-Fi Repeater with Ads, IoT Access Management, ESP32 Captive Portal, Google OAuth2.0 on ESP32, Wi-Fi Manager for ESP32, IoT Advertisement System  

## Project Overview  

This project introduces an innovative **ESP32-based Wi-Fi access control system** that leverages a **captive portal with Google authentication** to manage internet access for connected users. The ESP32 acts as a **Wi-Fi repeater** with a unique 16-character alphanumeric ID, allowing users to connect to the network. By default, users are redirected to a **captive portal** where they must authenticate using **Google OAuth2.0** to gain internet access. After successful authentication, users are granted access for a specific period, after which they must re-authenticate to continue using the internet.  

This system is designed for **IoT applications**, public Wi-Fi networks, or any scenario where controlled internet access is required. It integrates **advertisement display**, **user data collection**, and **machine learning-based ad optimization** to create a seamless and engaging user experience.  

---

## Key Features  

### 1. **ESP32 Wi-Fi Repeater with Unique ID**  
- The ESP32 acts as a **Wi-Fi repeater** with a unique 16-character alphanumeric ID.  
- Captures and manages connected devices' IP addresses for access control.  

### 2. **Captive Portal with Google Authentication**  
- Users are redirected to a **captive portal** upon connecting to the network.  
- **Google OAuth2.0** integration ensures secure and seamless authentication.  
- Grants internet access for a specific period after successful authentication.  

### 3. **Wi-Fi Manager for Initial Configuration**  
- If the ESP32 is not configured with Wi-Fi credentials, it uses the **Wi-Fi Manager library** to create a temporary access point (AP).  
- Users can input their Wi-Fi credentials via a web interface, which are securely stored on the ESP32.  

### 4. **Advertisement Display and Optimization**  
- The captive portal displays **targeted advertisements** (image, video, or text) to users.  
- Advertisements can be targeted to specific geographic areas.  
- **Machine learning algorithms** optimize ad delivery for maximum conversion rates.  

### 5. **User Data Collection and Analysis**  
- Collects user data such as search history and authentication details.  
- Stores data in a **Firestore database** for analysis and improved ad targeting.  

### 6. **Scalable and Secure Architecture**  
- Uses **MQTT communication** for efficient management of access periods and user interactions.  
- Ensures all communications are **encrypted** and secure.  

---

## Use Cases  

1. **Public Wi-Fi Networks**  
   - Provide controlled internet access in cafes, airports, or public spaces.  
   - Monetize access through targeted advertisements.  

2. **IoT Device Management**  
   - Manage internet access for IoT devices in smart homes or industrial settings.  

3. **Event Wi-Fi Access**  
   - Offer temporary internet access at events, requiring user authentication.  

4. **Advertisement Platforms**  
   - Create a platform for businesses to display targeted ads to users.  

---

## How It Works  

1. **Device Connection**  
   - Users connect to the ESP32 Wi-Fi network.  
   - The ESP32 captures the device's IP address and redirects the user to the captive portal.  

2. **Google Authentication**  
   - Users authenticate via **Google OAuth2.0** on the captive portal.  

3. **Access Granting**  
   - After successful authentication, the user is granted internet access for a predefined period.  

4. **Advertisement Display**  
   - Users may be shown targeted ads during their session.  

5. **Access Expiry and Re-authentication**  
   - When the access period expires, users must re-authenticate to regain internet access.  

---

## Key Benefits  

- **Enhanced User Experience**: Seamless authentication and controlled access.  
- **Monetization Opportunities**: Display targeted ads to users.  
- **Scalability**: Designed to handle multiple devices and users.  
- **Security**: Secure authentication and encrypted communications.  
- **Customizability**: Advertisements and access rules can be tailored to specific needs.  

---

## Future Enhancements  

- Integration with additional authentication methods (e.g., Facebook, email).  
- Advanced machine learning models for ad optimization.  
- Support for multiple languages and regions.  
- Real-time analytics dashboard for administrators.  

---

## Why This Project?  

This project combines **IoT technology**, **user authentication**, and **advertisement optimization** to create a versatile and scalable solution for controlled internet access. Whether you're looking to monetize public Wi-Fi, manage IoT device access, or create an engaging user experience, this system provides a robust foundation for your needs.  

---

## Get Involved  

This project is open for collaboration and contributions. If you're interested in IoT, Wi-Fi access control, or advertisement systems, feel free to reach out or contribute to the project.  

**Star this repository** to show your support and stay updated with the latest developments!  

---

**SEO Keywords:** ESP32 Wi-Fi Access Control, Captive Portal with Google Auth, Wi-Fi Repeater with Ads, IoT Access Management, ESP32 Captive Portal, Google OAuth2.0 on ESP32, Wi-Fi Manager for ESP32, IoT Advertisement System  

--- 

This README is designed to **convey the intent of the project** clearly while being **SEO-optimized** to attract relevant audiences. It avoids technical setup details, focusing instead on the project's purpose, features, and benefits.
