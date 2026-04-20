# Python Financial & Election Data Analysis

A Python-based data analysis project that processes large datasets to extract key financial and voting insights. This project demonstrates the use of Python for efficient data handling, aggregation, and reporting, replacing manual spreadsheet analysis with automated scripting.

---

## Objective
Analyze financial and election datasets using Python to compute key performance metrics, including profit trends and voting outcomes. The project focuses on transforming raw CSV data into structured insights through scripting and automation.

---

## Tools & Technologies
- Python  
- CSV Module  
- File I/O (Read/Write)  
- Data Structures (Lists, Dictionaries)  
- Iteration & Conditional Logic  
- Basic Data Aggregation & Analysis  

---

## Dataset
Two datasets were analyzed:

### Financial Data (PyBank)
- Monthly financial records  
- Includes:
  - Date  
  - Profit/Loss values  

### Election Data (PyPoll)
- Voting dataset from a simulated election  
- Includes:
  - Voter ID  
  - County  
  - Candidate  

---

## Key Analysis Performed

### Financial Analysis (PyBank)
- Calculated total number of months in dataset  
- Computed net total profit/loss over entire period  
- Analyzed month-over-month changes in profit/loss  
- Identified:
  - Average change in profit/loss  
  - Greatest increase in profits (date & value)  
  - Greatest decrease in profits (date & value)  

### Election Analysis (PyPoll)
- Calculated total number of votes cast  
- Identified all candidates receiving votes  
- Computed:
  - Total votes per candidate  
  - Percentage of votes per candidate  
- Determined election winner based on popular vote  

---

## Key Insights
- Financial data revealed **significant fluctuations in monthly performance**, highlighting volatility in profit trends  
- Average change calculations provided a clearer understanding of overall financial direction  
- Election data showed **dominant candidate performance**, with one candidate receiving a large majority of votes  
- Python scripting enabled efficient processing of large datasets that would be cumbersome in Excel  

---

## Output Summary

The Python scripts generate structured outputs for both analyses:
- Results printed directly to the terminal  
- Results exported to text files for documentation and reporting  

---

## Example Output

### Financial Analysis (PyBank)

Financial Analysis  
----------------------------  
Total Months: 86  
Total: $22564198  
Average Change: $-8311.11  
Greatest Increase in Profits: Aug-16 ($1862002)  
Greatest Decrease in Profits: Feb-14 ($-1825558)  

---

### Election Results (PyPoll)

Election Results
-------------------------
Total Votes: 369711

Charles Casper Stockham: 23.049% (85213)
Diana DeGette: 73.812% (272892)
Raymon Anthony Doane: 3.139% (11606)

Winner: Diana DeGette

## Business Impact
- Demonstrates ability to process and analyze large datasets using Python  
- Automates repetitive calculations and reporting tasks  
- Provides scalable alternative to Excel-based analysis  
- Highlights foundational skills in data analysis and scripting  

---

## Repository Structure
- `PyBank/` – Financial analysis script and data  
- `PyPoll/` – Election analysis script and data  
- `Resources/` – Raw CSV datasets  
- `analysis/` – Output text files  

---

## Future Improvements
- Refactor scripts using Pandas for more advanced data manipulation  
- Visualize results using Matplotlib or Seaborn  
- Combine analyses into a unified reporting dashboard  
- Integrate with databases for larger-scale data processing  

---

## Author
Jay Manion
