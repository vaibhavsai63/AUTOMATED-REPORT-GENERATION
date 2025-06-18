# AUTOMATED-REPORT-GENERATION

COMPANY: CODETECH IT SOLUTIONS
NAME : VAIBHAVA SAI GANGA
INTERN ID:CT06DM777
DOMAIN :PYTHON
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH


# DESCRIPTION

The sales data analysis presented provides a clear, concise summary of product performance based on the data from the file sales_data.csv. This analysis was performed using a Python script (generate_report.py) that utilizes the pandas library for data processing and the fpdf library to generate a PDF report titled "Sales_Performance_Report.pdf".

The console output confirms that the data was successfully read and analyzed. It first prints a Data Analysis Summary, reporting a total revenue of $16,683.50. This value is computed by multiplying the quantity and unit price for each transaction and summing the results across all products. The top-selling product based on revenue is identified as the Laptop, which generated a remarkable $12,000.00 in revenue from just 10 units sold, showing its high unit price and profitability.

A detailed Product-wise Summary follows, listing each product along with its total quantity sold and the corresponding total revenue. For example:

Headphones sold 6 units, generating $900.00.

Keyboards and Monitors each brought in $1,500.00, but from different quantities: 20 and 5 units, respectively.

Mouse and Webcam, while selling in decent quantities (17 and 7 respectively), had lower unit prices, reflected in their comparatively modest revenues of $433.50 and $350.00.

The script then proceeds to generate a PDF report, neatly organizing the same insights into a readable document. The PDF includes a formal Executive Summary, clearly stating the total revenue and the best-performing product. Following this, the Product-wise Sales Performance section displays a tabular breakdown of all products, their total quantities, and total revenue in USD.

From a software design perspective, the Python code is well-structured into modular functions:

read_and_analyze_data() is responsible for reading the CSV file, converting numeric fields, calculating totals, and returning aggregated results.

generate_sales_report() takes these results and formats them into a professional PDF using a custom PDFReport class that adds a consistent header and footer.

Error handling is also implemented. If the data file is missing or contains invalid values, appropriate messages are printed, ensuring the user is informed of any problems.

This project highlights the practical application of Python for business reporting. It automates the extraction of insights from raw sales data and presents them in both console and printable formats. Stakeholders, such as sales managers or financial analysts, can use such a report to assess product performance, make inventory decisions, and strategize future sales campaigns.

In conclusion, this automated reporting solution provides a streamlined approach to transforming raw transactional data into actionable intelligence. With easy adaptability to different datasets and customizable formatting, it stands as a scalable model for real-world sales reporting. The entire process—from reading data to generating visual and textual summaries—is completed efficiently using a single script, demonstrating the power of Python in business analytics.


##OUTPUT
