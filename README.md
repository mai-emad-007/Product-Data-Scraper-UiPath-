# Vodafone Shop & Amazon Data Automation

## 📌 Project Overview
This project was developed as the **final project** of my internship at **Vodafone Egypt** within the Automation & AI team.  
The automation extracts product data from **Vodafone Shop** and **Amazon**, processes it, and merges both datasets into a single Excel file — enabling easy comparison and analysis.

## 🎯 Objectives
- Automate the process of scraping product data from two e-commerce sources.
- Standardize and organize extracted data for analysis.
- Output the results into one Excel file with clearly separated columns for each source.

## 🛠 Tech Stack
- **UiPath Studio** (Automation development)
- **Excel** (Data storage & output)
- **Web Scraping Activities** in UiPath

## 📂 Project Structure
Vodafone-Amazon-Automation/
│
├── Main.xaml # Main automation workflow
├── project.json # UiPath project configuration
├── Data/ # Input/Output files
│ ├── AmazonData.xlsx
│ ├── VodafoneData.xlsx
└── MergedData.xlsx
## ⚙️ How It Works
1. **Extract Data from Amazon**
   - Uses UiPath web scraping to capture product names, prices, and other details.
2. **Extract Data from Vodafone Shop**
   - Similar process applied to Vodafone Shop’s product listings.
3. **Merge Data**
   - Both datasets are merged into a single Excel sheet.
   - Each source’s data is displayed in separate columns for easy comparison.
4. **Export Final File**
   - Final merged file saved in the `Data` folder.

## 🚀 How to Run
1. Install **UiPath Studio** (version 25.0.167-cloud.20208 or newer).
2. Clone or download this repository.
3. Open the project in UiPath Studio.
4. Update browser settings in UiPath if needed (Chrome/Edge extension).
5. Run the automation from `Main.xaml`.
6. The merged Excel file will be generated in the `Data` folder.

## 📋 Requirements
- UiPath Studio Community or Enterprise Edition
- Excel (2016 or later)
- Stable internet connection
- Chrome or Edge browser with UiPath extension enabled
