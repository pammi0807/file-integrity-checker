# 🔐 File Integrity Checker - Internship Task

This project is part of my internship task at **CODTECH**.

## 📌 Objective

To build a tool that monitors changes in files by calculating and comparing **SHA256 hash values** using Python.

## ⚙️ How It Works

- Calculates the current SHA256 hash of the file
- Compares it with a previously saved hash value
- If hashes match → ✅ File is unchanged
- If hashes differ → ⚠️ File has been modified

## 🚀 How to Use

1. Download the Python script: `file_integrity_checker.py`
2. Place it in the same folder as your target file
3. Open a terminal or command prompt
4. Run:
   ```
   python file_integrity_checker.py
   ```
5. Enter the name/path of the file you want to monitor

## 🧪 Sample Output

```
Enter the path of the file to check: testfile.txt
✅ File is intact. No changes detected.
```

## 📦 Built With

- Python `hashlib` (standard library)

## 📄 Deliverable

A Python script uploaded on GitHub as part of **Task-1: File Integrity Checker** for CODTECH Internship.

---

### 👩‍💻 Author

Intern: [Pranamya R]  
Internship Provider: **CODTECH**
