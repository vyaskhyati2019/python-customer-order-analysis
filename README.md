# E-Commerce Customer Order Analysis

### Project Overview
This project analyzes e-commerce customer orders using Python's core data structures (Lists, Tuples, Dictionaries, and Sets). The goal is to classify customers based on spending, identify popular product categories, and generate actionable business insights.

### Key Features
* **Data Processing:** Organizes raw order data into structured dictionaries for easy retrieval.
* **Customer Segmentation:** Automatically classifies buyers into High-Value, Moderate, or Low-Value categories based on spending thresholds.
* **Category Insights:** Calculates total revenue per product category and identifies cross-category purchasing patterns using set operations.
* **Top Performer Identification:** Uses custom sorting logic to identify the top 3 highest-spending customers.

### Tools Used
* Python 3.x
* No external libraries (Pure Python fundamentals)

### How to Run
1. Make sure Python 3.x and Jupyter are installed (or open the notebook in Google Colab).
2. Clone the repository:
   ```bash
   git clone https://github.com/vyaskhyati2019/python-customer-order-analysis.git
   cd python-customer-order-analysis
   ```
3. Open `Customer Orders.ipynb` and run all cells.

### Sample Output
```
Customer     | Total spent  | Classification
---------------------------------------------
Alice        | $2000        | High-Value Buyer
Bob          | $75          | Moderate Buyer
Charlie      | $80          | Moderate Buyer
Dana         | $45          | Low-Value Buyer
Eve          | $150         | High-Value Buyer

Total Revenue per Category:
- Electronics: $2150
- Clothing: $85
- Home Essentials: $115

Top 3 Spenders: Alice, Eve, Charlie
```
