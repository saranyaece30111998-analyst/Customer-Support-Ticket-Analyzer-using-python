# Customer-Support-Ticket-Analyzer-using-python
Here’s a polished **README.md** draft for your GitHub repository that 

A simple Python-based ticket management and analysis system.  
This project demonstrates how to handle customer support tickets, clean text data, and generate insights using keyword analysis and priority tracking.

---

## 🚀 Features
- **Preloaded Tickets**: Starts with sample ticket data (ID, customer name, issue description, priority).
- **Add New Tickets**: Interactive function to add more tickets with validation for priority levels.
- **Text Cleaning**:
  - Removes punctuation
  - Converts text to lowercase
  - Normalizes spaces
  - Replaces slang (e.g., `ok → okay`)
- **Keyword Insights**: Counts tickets containing specific keywords (`poor`, `good`, `slow`, `excellent`).
- **Priority Analysis**: Summarizes ticket distribution across High, Medium, and Low priorities.
- **Longest Issue Detection**: Identifies the ticket with the longest issue description.
- **Unique Words Extraction**: Lists all unique words used in issue descriptions.

---

## 📂 Project Structure
```
ticket_analyzer.py   # Main script with ticket data and analysis functions
README.md            # Project documentation
```

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ticket-analyzer.git
   cd ticket-analyzer
   ```
2. Run the script:
   ```bash
   python ticket_analyzer.py
   ```
3. (Optional) Enable ticket addition by uncommenting:
   ```python
   # add_tickets(ticket_data)
   ```

---

## 📊 Example Output
```
Initial Ticket Data:
Ticket 1 | Name: Ravi | Issue: Internet not working !!! | Priority: High
...

Keyword Insights:
Tickets containing 'poor': 2
Tickets containing 'good': 3
Tickets containing 'slow': 2
Tickets containing 'excellent': 1

Priority Analysis:
High Priority: 4
Medium Priority: 3
Low Priority: 3

Ticket with Longest Issue Description:
Ticket No: 2
Customer: Meera
Issue: slow response very poor service
Word Count: 5

Unique Words Used:
Count: 34
['better', 'could', 'excellent', 'good', 'guidance', 'handling', ...]
```

---

## 🎯 Use Cases
- Customer support ticket management
- Text preprocessing and cleaning
- Keyword-based sentiment insights
- Priority-based workload analysis

---

## 🛠️ Technologies
- **Python 3**
- **string** library (for text cleaning)

---

## 📌 Future Enhancements
- Sentiment analysis using NLP libraries
- Export insights to CSV/Excel
- Visualization dashboards with **Power BI** or **Matplotlib**

---

## 👩‍💻 Author
Developed by **Saranya**  
Engineering graduate & Data Analyst | Skilled in Python, SQL, Power BI, and Excel
```

---

Would you like me to also create a **shorter version** of the README (like a one-page quick-start guide) so you can use it for recruiters or portfolio highlights?
