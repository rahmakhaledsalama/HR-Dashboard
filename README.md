# HR Dashboard 📊

This repository contains an HR Dashboard developed using Power BI. The dashboard provides insightful visualizations and reports to help manage and analyze HR data effectively.

## Features ✨

- **Interactive Visualizations**: Utilize various Power BI visuals to represent HR data in an interactive manner.
- **DAX Measures**: Create complex measures using Data Analysis Expressions (DAX) to perform calculations on your data.
- **Calculated Columns**: Use DAX to add calculated columns to your data model.
- **Power Query**: Transform and clean your data using Power Query before loading it into the data model.

## Getting Started 🚀

To use this dashboard, follow these steps:

### Prerequisites 📋

- Power BI Desktop installed on your machine. You can download it [here](https://powerbi.microsoft.com/en-us/desktop/).

### Installation 🛠

1. Clone the repository to your local machine:
   
   ```bash
   git clone https://github.com/rahmakhaledsalama/HR-Dashboard.git
Open the Power BI Desktop application.
Load the HR Dashboard Power BI file (.pbix) from the cloned repository.
Data Preparation 🗂
Using Power Query
Power Query is used to import, clean, and transform your data before it is loaded into the data model. The following steps outline the basic process:

Import Data: Bring in data from various sources such as Excel, SQL Server, or other databases.
Transform Data: Apply transformations like filtering rows, splitting columns, and changing data types.
Load Data: Load the transformed data into Power BI for further analysis and visualization.
Writing Measures and Calculated Columns
Measures and calculated columns are created using DAX (Data Analysis Expressions). Below are examples of how each is used in this dashboard:

Measures
Measures are used to perform calculations on your data. They are dynamic and recalculated based on the context of the report.

Example:

DAX
Total Employees = COUNTROWS(Employees)
Calculated Columns
Calculated columns are added to your data model and used for more static calculations.

Example:

DAX
Full Name = Employees[First Name] & " " & Employees[Last Name]
Usage 📈
Once the data is prepared and the measures and calculated columns are created, you can start building your visualizations. Here are some common visuals used in the HR Dashboard:

Bar Charts: To show comparisons between different categories.
Line Charts: To display trends over time.
Pie Charts: To show proportions of a whole.
Tables and Matrices: To display detailed data in a structured format.
Contributions 🤝
Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

