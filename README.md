# 🧬 Quantum-Safe DNA Codon Encryption with Image Steganography

A Python-based security project that combines **DNA Codon Encryption**, **BB84 Quantum Key Distribution (QKD)**, **Homomorphic Encryption**, and **Image Steganography** to provide a multi-layered approach to secure communication. The system converts plaintext into DNA codons, secures the encoding with a simulated quantum-generated key, encrypts the data, and finally hides it inside an image using Least Significant Bit (LSB) steganography. Designed for Raspberry Pi, this project demonstrates how modern cryptographic techniques can be integrated into a lightweight embedded system for secure data transmission.

---

## 📖 Overview

With the rapid growth of quantum computing, traditional encryption techniques are expected to become increasingly vulnerable. This project presents a secure communication framework by combining concepts from quantum cryptography, bio-inspired encryption, and digital steganography.

The message is first converted into DNA codons using a custom encoding algorithm. A simulated BB84 Quantum Key Distribution protocol generates a secure 256-bit encryption key that is used to randomize the codon mapping. The encrypted codons are then protected using the Paillier Homomorphic Encryption scheme and finally embedded into a digital image using LSB Image Steganography. A graphical user interface allows users to securely encode and decode messages, making the system simple to use while maintaining multiple layers of security.

---

# 🎯 Objectives

- Develop a DNA Codon-based encryption system.
- Implement BB84 Quantum Key Distribution for secure key generation.
- Integrate Homomorphic Encryption for enhanced security.
- Hide encrypted information inside digital images using LSB Steganography.
- Design a user-friendly GUI for encoding and decoding.
- Demonstrate the complete workflow on Raspberry Pi.

---

# ✨ Features

- 🔐 DNA Codon Encryption
- 🔑 BB84 Quantum Key Distribution (Simulation)
- 🛡️ Paillier Homomorphic Encryption
- 🖼️ LSB Image Steganography
- 🔒 Password-based Dynamic Codon Mapping
- 💻 Interactive Python GUI
- 🍓 Raspberry Pi Compatible
- 📷 Automatic PNG Image Conversion

---

# 🏗️ System Architecture

```text
                Plain Text
                     │
                     ▼
          DNA Codon Encoding
                     │
                     ▼
      BB84 Quantum Key Distribution
                     │
                     ▼
      Homomorphic Encryption
                     │
                     ▼
       LSB Image Steganography
                     │
                     ▼
              Stego Image
                     │
                     ▼
            Image Decoding
                     │
                     ▼
          DNA Codon Decoding
                     │
                     ▼
           Original Message
```

---

# 🔄 Project Workflow

1. User enters a secret message.
2. Plaintext is converted into DNA codons.
3. BB84 Quantum Key Distribution generates a secure encryption key.
4. The generated key is applied to dynamic codon mapping.
5. Homomorphic Encryption secures the encrypted codons.
6. Encrypted data is embedded into an image using LSB Steganography.
7. The stego image is generated and stored.
8. During decoding, the hidden data is extracted, decrypted, and converted back into the original message.

---

# 🛠️ Technologies Used

- Python
- Raspberry Pi
- Tkinter
- ttkbootstrap
- Pillow (PIL)
- NumPy
- Matplotlib
- PHE (Paillier Homomorphic Encryption)

---

# 📂 Project Structure

```text
Quantum-Safe-DNA-Codon-Steganography/
│
├── codons.py
├── stego_image.py
├── gui_stego_modern.py
├── bb84_visual_gui.py
├── he_paillier.py
├── he_demo.py
├── requirements.txt
├── README.md
├── LICENSE
├── images/
├── docs/
└── sample_images/
```

---

# ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Quantum-Safe-DNA-Codon-Steganography.git
```

```bash
cd Quantum-Safe-DNA-Codon-Steganography
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

### Launch the GUI

```bash
python gui_stego_modern.py
```

### Run the BB84 QKD Visualizer

```bash
python bb84_visual_gui.py
```

### Encode a Message

```bash
python stego_image.py encode cover.png stego.png "Hello World"
```

### Decode a Message

```bash
python stego_image.py decode stego.png
```

---

# 📊 Results

The project successfully demonstrates:

- Accurate conversion between plaintext and DNA codons.
- Secure generation of a 256-bit encryption key using BB84 simulation.
- Successful implementation of Paillier Homomorphic Encryption.
- Invisible embedding of encrypted data inside PNG images using LSB Steganography.
- Correct recovery of the original message using the appropriate password.
- Efficient execution on Raspberry Pi, making it suitable for lightweight embedded security applications.

---

# 🚀 Future Scope

- Integration with real Quantum Key Distribution hardware.
- Secure communication between multiple Raspberry Pi devices.
- Mobile and web-based interfaces.
- Support for Post-Quantum Cryptographic algorithms.
- Secure IoT communication using cloud connectivity.
- Enhanced DNA codon randomization techniques.

---

# 📸 Screenshots

Add screenshots of the following:

- Main GUI
- BB84 QKD Visualizer
- DNA Codon Encoding
- Image Encoding
- Image Decoding
- Stego Image
- Raspberry Pi Setup

---

# 👩‍💻 Author

**K. L. Eshwari**  
B.Tech, Electronics and Communication Engineering  
SRM University-AP

---

**Project Guide:**  
**Prof. Rupesh Kumar**

# 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you found this project interesting or useful, please consider giving it a ⭐ on GitHub. It helps support the project and encourages further development.
