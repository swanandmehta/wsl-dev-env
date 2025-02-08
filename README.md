# Development Environment for WSL  

### Background  
I prefer doing development on a Linux-based system, but I also use my Windows laptop for gaming and general tasks. Recently, my development machine broke, and I didn’t want to clutter my Windows installation with numerous applications—some of which I might only use once (looking at you, *Tesseract* 😅).  

### The Solution: WSL  
To get the best of both worlds, I turned to **WSL (Windows Subsystem for Linux)**. Initially, I installed a base OS and used it as needed, but then I realized that if I ever needed to start fresh, I’d have to reinstall everything manually. So, I decided to create a **custom WSL image** to streamline the process.  

---

### How to Use It  

1. **Request access to the image:** [Download here](https://drive.google.com/file/d/10L7b8TlB9bPLyL7ieB9VP3Pz-4diX45Q/view?usp=drive_link).  
2. **Import the image into WSL:**  
   ```sh
   wsl --import DevPower <Path-to-storage> <Path-to-downloaded-image>
   ```
3. **Login credentials:**  
   - **Username:** `dev_power`  
   - **Password:** `dev_power`  

---

### What's Included?  

- **Base OS:** Ubuntu 24.04 LTS  
- **Development tools:**  
  - JetBrains Toolkit  
  - SSH  
  - Git  
  - AWS CLI & Toolkit  

_Last updated: February 8, 2025_  
