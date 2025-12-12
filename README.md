# 📌 Excel Sales Aggregation Tool

An automation tool that aggregates multiple daily Excel/CSV sales files into a single consolidated report using Python (pandas).

Ideal for **IT support**, **data management**, and **business operations automation**.

---

## 🚀 Features
- Automatically loads all Excel/CSV files inside the `data/` folder  
- Cleans and normalizes data (column names, missing values, date formats)  
- Aggregates sales by **store × date**  
- Exports the result as an Excel report  
- Works for any number of daily files  

---

## 📁 Folder Structure

excel_automation/
│
├── data/ # Put your daily Excel/CSV files here
├── output/ # Auto-generated results are saved here
├── aggregate_sales.py
└── README.md


---

## 🧠 Example Use Case
This tool is useful for:

- Daily or monthly business report creation  
- Store-based or department-based sales summaries  
- Replacing Excel-based manual processes  
- IT support teams who manage operational data  
- Anyone who wants to automate repetitive Excel tasks  

---

## 🐍 Usage

### **1. Install dependencies**

pip install pandas openpyxl


### **2. Place input files**
Put Excel or CSV files inside the `data/` folder.

Example input format:

| date        | store | sales |
|-------------|--------|--------|
| 2025-01-01  | Tokyo  | 12000  |
| 2025-01-01  | Osaka  | 9000   |

### **3. Run the script**

python aggregate_sales.py


The aggregated report will be saved to:


output/aggregated_sales_YYYYMMDD.xlsx


---

## 📌 Future Enhancements (optional)
- Add charts to the output Excel  
- Email automatic sending  
- Error logging  
- GUI version (Tkinter)  
- Web dashboard (Streamlit)  

---

## 📜 License
MIT License


MIT License
