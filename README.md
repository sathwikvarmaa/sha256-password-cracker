# 🔓 SHA256 Password Cracker

> A Python-based cybersecurity learning project that demonstrates dictionary-based password recovery against SHA-256 hashes using a wordlist.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Learning-red)
![Cryptography](https://img.shields.io/badge/Cryptography-SHA256-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📖 Overview

SHA256 Password Cracker is a Python script that demonstrates how password hashes can be analyzed and matched against passwords from a wordlist.

The project helps learners understand:

* SHA-256 hashing
* Password security fundamentals
* Dictionary attacks
* Hash comparison techniques
* Python automation in cybersecurity

This tool is intended for educational purposes and authorized security testing environments only.

---

## ✨ Features

* 🔍 SHA-256 hash verification
* 📚 Wordlist-based password recovery
* ⚡ Real-time progress updates
* 🐍 Built with Python and Pwntools
* 🔒 Cryptography learning project
* 📈 Demonstrates password security concepts

---

## 🛠️ Technologies Used

* Python 3
* Pwntools
* SHA-256 Cryptographic Hashing

---

## 📂 Project Structure

```text
.
├── SHA256-Crack.py
├── rockyou.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/sathwikvarmaa/sha256-password-cracker.git
cd sha256-password-cracker
```

### Install Dependencies

```bash
pip install pwntools
```

---

## ▶️ Usage

Run the script by providing a SHA-256 hash:

```bash
python3 SHA256-Crack.py <sha256_hash>
```

### Example

```bash
python3 SHA256-Crack.py 5e884898da28047151d0e56f8dc6292773603d0d6aabbdd62a11ef721d1542d8
```

---

## 🧠 How It Works

1. Accepts a SHA-256 hash as input.
2. Loads passwords from a wordlist.
3. Generates SHA-256 hashes for each password.
4. Compares generated hashes against the target hash.
5. Displays the matching password if found.
6. Stops execution after a successful match.

---

## 📸 Sample Output

```text
[+] Attempting to crack hash...

[1250] password123 == e99a18c428cb38d5f260853678922e03abd8334...
[1251] letmein == 0d107d09f5bbe40cade3de5c71e9e9b7...

[+] Password hash found after 1251 attempts!
Password: letmein
```

---

## 🎯 Learning Outcomes

By building this project, you can gain practical knowledge of:

* Cryptographic Hash Functions
* Password Storage Concepts
* Dictionary Attack Methodology
* Python Security Automation
* Cybersecurity Fundamentals
* Ethical Hacking Concepts

---

## 🔐 Why Strong Passwords Matter

Even though cryptographic hashes protect passwords, weak passwords can often be recovered using common wordlists and dictionary attacks.

Security best practices include:

* Using strong and unique passwords
* Implementing password salting
* Using adaptive hashing algorithms
* Enabling multi-factor authentication (MFA)

---

## 🚀 Future Improvements

* Support for additional hash algorithms
* Custom wordlist support
* Multi-threaded processing
* GPU acceleration integration
* Salted hash demonstrations
* Improved performance metrics

---

## ⚠️ Disclaimer

This project is intended strictly for:

* Educational purposes
* Cybersecurity training
* Security research
* Authorized penetration testing labs

Do not use this software against systems, accounts, or data without explicit authorization.

The author assumes no responsibility for misuse of this project.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to:

* Fork the repository
* Open issues
* Submit pull requests
* Share feedback

---

## ⭐ Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

📢 Share it with fellow cybersecurity enthusiasts

---

## 📜 License

This project is provided for educational and research purposes only.

---

### Made with ❤️ using Python, Cryptography, and Cybersecurity Concepts
