# Top 10 Products by Sales – Superstore

**Task 19 – Top 10 Products**
Veda Technology | Data Analytics Track | Level 1, Day 19

## About
I found the top 10 products by total sales in the Sample Superstore dataset (2014-2017, 9,994 transactions, about 1,850 different products) using a PivotTable in Excel. I sorted the products from highest to lowest, checked for ties, and showed the result in a bar chart.

## Top 10 table
| Rank | Product | Total Sales | % of All Sales |
|------|---------|-------------|----------------|
| 1 | Canon imageCLASS 2200 Advanced Copier | 61,599.8 | 2.7% |
| 2 | Fellowes PB500 Electric Punch Plastic Comb Binding Machine with Manual Bind | 27,453.4 | 1.2% |
| 3 | Cisco TelePresence System EX90 Videoconferencing Unit | 22,638.5 | 1.0% |
| 4 | HON 5400 Series Task Chairs for Big and Tall | 21,870.6 | 1.0% |
| 5 | GBC DocuBind TL300 Electric Binding System | 19,823.5 | 0.9% |
| 6 | GBC Ibimaster 500 Manual ProClick Binding System | 19,024.5 | 0.8% |
| 7 | Hewlett Packard LaserJet 3310 Copier | 18,839.7 | 0.8% |
| 8 | HP Designjet T520 Inkjet Large Format Printer - 24" Color | 18,374.9 | 0.8% |
| 9 | GBC DocuBind P400 Electric Binding System | 17,965.1 | 0.8% |
| 10 | High Speed Automatic Electric Letter Opener | 17,030.3 | 0.7% |
| | **Top 10 total** | **244,620.2** | **10.6%** |

## Chart
A horizontal bar chart of the top 10 products by total sales, with the highest product at the top.

## How I did it
1. Built a PivotTable with Product Name in Rows and Sum of Sales in Values
2. Sorted the sales from largest to smallest
3. Checked for ties by comparing the 10th product (17,030.3) with the 11th product in the PivotTable: [no tie found, edit this if you find one]
4. Copied the top 10 into a clean table with a rank and each product's share of total sales
5. Made the bar chart

## Findings
- The **Canon imageCLASS 2200 Advanced Copier** is the top product with 61,599.8 in sales (2.7% of all sales). That is more than double the second product, the Fellowes binding machine (27,453.4).
- The top 10 products together make up only **10.6%** of total sales, so sales are spread across many products and do not depend on just a few.
- Most of the top products are office machines, such as copiers, binding machines and printers.

## Files
- `Top_10_Products.xlsx` – workbook with the Raw Data, Pivot and Top 10 tabs
- `top10_screenshot.png` – screenshot of the Top 10 tab
- `README.md`

## Tools used
Microsoft Excel (PivotTable, sorting, charts)

## Author
Rabia
