This script allows you to compute the cryptographic hash of a file using various hash algorithms like `MD5`, `SHA1`, and `SHA256`. Hashing is a one-way process that converts file data into a unique fixed-length string, commonly used to verify file integrity.

---

### **How to Use**
1. **Run the Script**:
   - Open a terminal or command prompt.
   - Navigate to the directory where the script is saved.
   - Run the script using Python:
     ```bash
     python script_name.py
     ```
   - Replace `script_name.py` with the actual name of your script.

2. **Provide File Path**:
   - When prompted, enter the full path of the file you want to hash. For example:
     ```
     Enter the path to the file: C:\Users\YourName\Documents\example.txt
     ```

3. **Select a Hash Algorithm**:
   - The script will ask for the hash algorithm to use. Enter one of the following options:
     - `md5` for MD5 hashing.
     - `sha1` for SHA-1 hashing.
     - `sha256` for SHA-256 hashing (default if you skip specifying).
   - Example input:
     ```
     Enter the hash algorithm (e.g., md5, sha1, sha256): sha256
     ```

4. **View the Result**:
   - The script will compute and display the hash:
     ```
     The sha256 hash of the file is: d2d2d2d2... (hash value)
     ```

---

### **Example Usage**

#### Example Input:
```plaintext
Enter the path to the file: C:\example\file.txt
Enter the hash algorithm (e.g., md5, sha1, sha256): sha1
```

#### Example Output:
```plaintext
The sha1 hash of the file is: e8c89db74f52e38dded5a7b3d05ec3b39bc3f112
```

---

### **Common Errors and Troubleshooting**

1. **File Not Found**:
   - If you see the error:
     ```
     File not found. Please enter a valid file path.
     ```
   - Ensure the file path is correct and that the file exists. For example:
     - Use `C:\path\to\file.txt` for Windows.
     - Use `/path/to/file.txt` for Linux/Mac.

2. **Invalid Hash Algorithm**:
   - If you see the error:
     ```
     Invalid hash algorithm: your_input. Please enter a valid algorithm (e.g., md5, sha1, sha256).
     ```
   - Make sure to input a supported algorithm (`md5`, `sha1`, or `sha256`).

3. **Permission Issues**:
   - If the script cannot access the file, check if you have read permissions for the file.

---

### **Notes for New Users**
- **Hashing Use Cases**:
  - Verifying downloaded files by comparing their hash values to published ones.
  - Ensuring file integrity during data transfers.

- **Cross-Platform**:
  - This script works on any platform where Python is installed (Windows, macOS, Linux).

- **Python Version**:
  - Make sure you have Python 3.8+ installed to support the `:=` operator (walrus operator).

---
