# 📒 Contact Book Management System (Python)

A simple and efficient **Contact Book** built using Python.  
This program allows users to **add, view, search, update, delete, export, and load contacts** using CSV and JSON files.  
It includes validation, error logging, and a clean menu-driven interface.

---

## 🚀 Features

### ✔ Add New Contact  
- Stores name, phone, and email  
- Validates phone number & email format  
- Detects duplicates and gives overwrite option  

### ✔ View All Contacts  
- Displays neatly formatted list  
- Auto-aligned columns  
- Sorted alphabetically  

### ✔ Search Contacts  
- Partial & case-insensitive search  
- Returns multiple matching results  

### ✔ Update Contacts  
- Update phone or email  
- Supports partial name matching  

### ✔ Delete Contacts  
- Confirmation before deletion  
- Partial or multiple match selection  

### ✔ Export to JSON  
- Saves contacts to `contacts.json`  
- Also creates a timestamped backup file  

### ✔ Load From JSON  
- Merge or overwrite CSV  
- Keeps everything sorted & clean  

### ✔ Error Logging  
- All errors saved automatically to `error_log.txt`  

---

## 🗂 File Structure

```
📁 Project Folder
│
├── contacts.csv
├── contacts.json
├── contacts_backup_*
├── error_log.txt
└── contact_book.py
```

---

## 🛠 Requirements

- Python 3.8 or above  
- No external libraries needed  

---

## ▶️ How to Run

```bash
python contact_book.py
```

---

## 🤝 Contributing

Pull requests are welcome.

---

## 📜 License

MIT License
