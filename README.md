# Data Science Bootcamp: Data Cleaning & Storytelling with Pandas
<img width="1139" alt="image" src="https://github.com/wheeliecopta/pandas-data-cleaning/assets/127804427/eda80dc6-804b-453e-91ef-1496a0879b56">

## Project Goal
This project revolved around the made-up e-commerce retailer Eniac, specialized in high-end tech products. The goal was to use a data-driven approach to find out if discounts are beneficial for the company's revenue. The bulk of the project consisted of cleaning up the data (which came from an unknown, real-world tech retailer) and making it interpretable for further analysis. 
<br><br>
Python's pandas did the heavy lifting (see picture above). 
<br>
Seaborn and Matplotlib were used to create the project's plots.
<br><br>
This project was a team effort implemented with my fellow bootcampers
- [Pete](https://github.com/PetriTiirikainen)
- [Rey](https://github.com/reymillerc)
- Matthias

## Repository Structure
### /data
The data folder consists of four csv files
1. orders.csv - information about complete orders
2. orderlines.csv - information about individual items in the orders
3. products.csv - information about the products in the company's product line
4. brands.csv - information about the brands in the company's product line

Different versions of these csv files exist in different subfolders. As their names suggest, one subfolder contains the raw data, another the cleaned-up data and the last subfolder contains the data used for analysis.

### /cleanup
Folder containing the Jupyter notebooks used to clean up the data.

### eniac_analysis
Notebook used for data analysis.

### Presentation
The PDF file of the 5-minute presentation we gave at the end of the project.


## Contributions of Team Members
Each team member went through the data cleaning process individually. We then decided to use Pete's cleaned-up tables, mostly because he had done a great job at creating product categories (which were used to find out for which types of products discounts might work).
- Rey gave the presentation together with Matthias
- Matthias developed suggestions on how to improve the data (presentation slide 7 and 8)
- Pete created the graphs from slides 2 to 5 (aside from his informal role as team captain)
- I created the graph from slide 6, helped finalize the graphs from slide 3 and 4, and designed the final version of the presentation
