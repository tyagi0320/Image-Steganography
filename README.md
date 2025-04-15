# Image Steganography Project

## 📌 Project Overview
The **Image Steganography Project** is a Python-based application that allows users to hide and retrieve secret messages within images using **Least Significant Bit (LSB) encoding**. The project also integrates **encryption** for added security, ensuring that hidden messages remain confidential.

## 🚀 Features
- **Encode Text into Images**: Hide secret messages within image files.
- **Decode Hidden Messages**: Extract messages from steganographic images using a secret key.
- **Secure Encryption**: Uses a **transposition cipher** for encrypting hidden messages before embedding.
- **Graphical User Interface (GUI)**: Built using **Tkinter** for user-friendly interactions.
- **Supports Multiple Image Formats**: Works with **PNG, JPEG, and JPG** files.

## 🏗️ Tech Stack
### **Frontend**
- Tkinter (GUI for encoding/decoding operations)

### **Backend**
- Python (Core logic & encryption)
- PIL (Image processing)
- Tkinter FileDialog (File selection)

### **Encryption & Decryption**
- Custom Transposition Cipher (Encryption before embedding)
- Least Significant Bit (LSB) steganography

## 🔬 How It Works
1. **Encoding Process:**
   - Select an image file.
   - Enter the secret message and encryption key.
   - Message is encrypted and embedded in the image using LSB steganography.
   - Save the modified image.

2. **Decoding Process:**
   - Select a steganographic image.
   - Enter the correct decryption key.
   - Extract and decrypt the hidden message.

## 📌 Challenges & Solutions
### **1️⃣ Ensuring Secure Data Hiding**
- **Issue:** LSB steganography can be easily altered by image compression.
- **Solution:** Use **lossless PNG format** to maintain data integrity.

### **2️⃣ Preventing Unauthorized Access**
- **Issue:** Extracted messages could be compromised without encryption.
- **Solution:** Implemented **transposition cipher encryption** for added security.

## 📜 License
This project is licensed under the MIT License.

---

