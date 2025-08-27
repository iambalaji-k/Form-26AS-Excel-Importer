# 📑 Form 26AS Text to Excel Importer

An **Excel-based tool** powered by **Power Query** to simplify and automate the process of importing the **Form 26AS text file** from the TRACES portal into a clean, structured, and easy-to-read format.

---

## 🚨 The Problem
As the due date for filing Income Tax Returns (**ITR**) approaches, it’s crucial to thoroughly review the information in **Form 26AS**.  
While the form is available in **PDF** and **Text** formats, working with it in **Excel** makes comparison and reconciliation far more efficient.

However, using Excel’s default **Text-to-Columns** method to import the raw text file is often tedious—requiring **manual formatting and cleanup**.

---

## 💡 The Solution
This **macro-enabled Excel template (`.xlsm`)** leverages the power of **Power Query** to automate data extraction and transformation.  

✨ With a single click, it:  
- Parses the raw Form 26AS text file.  
- Organizes the data into **clean, structured tables**.  
- Saves you significant time during the ITR filing process.  

---

## ✨ Features
- 🖱️ **One-Click Import**: Simple button-based interface.  
- 🧹 **Automated Formatting**: No manual cleanup required.  
- 📊 **Structured Data**: Tables organized for quick review.  
- ⚡ **Fast & Efficient**: Built on Power Query for optimal speed.  

---

## 📋 Requirements
- **Microsoft Excel for Windows**  
  - Version **2016 or later** or **Microsoft 365**, with Power Query support.  
- **Form 26AS text file** downloaded from the TRACES portal.  

---

## 🚀 Instructions for Use

1. **Download Form 26AS**  
   - Log in to the [Income Tax TRACES Portal]  
   - Download Form 26AS as a **ZIP file (Text format)**.  

2. **Extract the Text File**  
   - Unzip the downloaded file.  
   - Password = **Date of Birth/Incorporation (DDMMYYYY)**.  
   - Example: `01011980`.  

3. **Get the Excel Tool**  
   - Download **`Form-26AS-Excel-Importer.xlsm`** from this repository.  

4. **Unblock the File (Important!)**  
   - Right-click the `Form-26AS-Excel-Importer.xlsm` file → **Properties**.  
   - In **General** tab, check **Unblock** → **Apply** → **OK**.  
   - *(If you don’t see “Unblock,” you can skip this step.)*  

5. **Import Your Data**  
   - Open `Form-26AS-Excel-Importer.xlsm`.  
   - Enable **Macros / Content** when prompted.  
   - Click **“Import 26AS Text File”** → select your extracted text file.  
   - ✅ Done! The tool will parse and load your data automatically.
   - It will be useful for TDS reconciliation process.
---

## 🤝 Contributing
Got feedback or ideas?  
- [Open an Issue](https://github.com/iambalaji-k/Form-26AS-Excel-Importer/issues)  
- Suggest improvements, report bugs, or ask questions!  

---

## ⚠️ Disclaimer
This is a **personal project** to assist with data organization.  
It is **not an official tool** from the Income Tax Department of India.  

Always verify the imported data against the official **Form 26AS PDF** before filing your ITR.  
The author is **not responsible** for errors, discrepancies, or consequences arising from the use of this tool.  

---
