# AutoWifiLoginScript
Now no need to login again and again 
This script, along with the accompanying batch and VBS files, is designed for seamless login to Jaypee's WiFi system. It automates the process of logging into the Sophos Login Portal, which manages the login and logout functionality for the campus WiFi.

Sophos typically runs as a background process, consuming considerable system resources. This script provides a lightweight alternative, storing your WiFi credentials and automating the login process. Additionally, it notifies you if:

- You are successfully logged in.
- Your data limit has been exceeded, preventing login.

## Features

- **Automated Login**: Eliminates the need to manually open the Sophos client and log in.
- **Resource Efficient**: Reduces memory usage by bypassing the Sophos client.
- **Data Limit Notification**: Alerts you if your data limit has been exhausted.

## Prerequisites

- A **Windows** machine (no cross-platform support currently).
- **Python** installed on your system.

## How to Use

### 1. **Download and Extract**:
   - Download the repository as a ZIP file and extract it.

### 2. **Enter Your Credentials**:
   - Open the `auto_auth\config.py` file and put your WiFi login credentials.

   ```python
   USERNAME = ""  # Replace with your username
   PASSWORD = ""  # Replace with your password
   ```

### 3. **Run the Script**:
- Execute the `runLogin.vbs` file using any of the following methods:
   - Double-click the file.
   - Open the terminal or Run menu and execute the file.

### 4. **Check Notifications**:
- A notification pop-up will indicate if the login was successful.
- If your data limit has been exceeded, a notification will inform you that the login failed.

## Notes
- This script is tailored specifically for systems using the Sophos Login Portal.
- Ensure your credentials are securely stored and not shared with others.

## Contributing
- Feel free to fork this repository, suggest improvements, or report issues. Contributions are always welcome!
