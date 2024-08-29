## **Data Transformation and Visualization in Power BI**

### **Project Overview**

This project demonstrates a comprehensive data transformation and visualization process using Power BI. The focus is on preparing and standardizing data for accurate analysis and creating insightful visualizations to drive business decisions.

### **Key Steps and Objectives**

1. **Data Import and Transformation:** 
   - Imported the dataset into Power BI and accessed the Power Query Editor for necessary transformations.
  
2. **Data Cleaning:**
   - Corrected spelling and punctuation errors in the "type" column to ensure consistency.
   - Standardized project names that were not uniform across the dataset.

3. **Handling Missing Data:**
   - Addressed missing values in the "Currency" column by creating a new custom column based on the "Amount" values.
   - Applied the following logic:
     - If `Amount` ≥ 1000, set `Currency` to "INR."
     - If `Amount` < 1000, set `Currency` to "USD."
     - If neither condition is met, set `Currency` to "EURO."

4. **Currency Normalization:**
   - Normalized the "Amount" column into INR based on the values in the "Currency" column to facilitate consistent analysis.

5. **Interactive Visualizations:**
   - Created a slicer visual for filtering data by project and employee.
   - Developed a bar chart visualizing the sum of normalized amounts by employee name.
   - Designed a pie chart to display the distribution of normalized amounts by project.
   - Added card visuals to display the total normalized amount and the count of requests with an "ApprovalStatus" of "Declined."

### **Conclusion**

This project showcases how to clean, transform, and visualize data effectively in Power BI, leading to meaningful insights and informed decision-making. The steps outlined provide a foundation for handling similar data preparation and analysis tasks in Power BI.
