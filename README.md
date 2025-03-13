
  Helper: https://www.youtube.com/watch?v=gTK5rNhWJyA
  
# Vrinda Store Data Analysis - Annual Sales Report for 2022

## **Objective**
Vrinda Store aims to create an annual sales report for 2022 to understand customer behavior and identify growth opportunities for 2023.

## **Data Cleaning**
1. **Index and Order ID**  
   - Applied filters to check for duplicates and null values.  
   - Ensured all Order IDs are unique and free of null values.  

2. **Customer ID**  
   - Verified that all Customer IDs are numeric and free of null values.  

3. **Gender**  
   - Data was inconsistent (e.g., M, F, Male, Female).  
   - Replaced "M" with "Men" and "F" with "Women" for consistency.  

4. **Age**  
   - Confirmed that Age is numeric and has no null values.  

5. **Quantity**  
   - Standardized inconsistent data (e.g., replaced "One" with "1" and "Two" with "2").  

6. **Date, Status, Channel, Category, Size, Currency, Amount, Ship-City, Ship-State, Ship-Postal-Code, Ship-Country**  
   - Ensured all fields are clean and consistent.  

## **Data Processing**
1. **Age-Group Categorization**  
   - Created an "Age-Group" column using the formula:  
     ```excel
     =IF(col>=50,"Senior",IF(col>=30,"Adult","Teenager"))
     ```  
   - Categories:  
     - Teenager: Below 30 years  
     - Adult: 30-49 years  
     - Senior: 50+ years  

2. **Extracting Month from Date**  
   - Extracted the month from the "Date" column using:  
     ```excel
     =TEXT(col,"mmm")
     ```  

## **Data Analysis**
1. **Pivot Tables and Charts**  
   - Created pivot tables to summarize data.  
   - Visualized insights using charts (e.g., bar charts, pie charts).
   - 
     ![image](https://github.com/user-attachments/assets/3d773eb8-96f3-42f6-8bba-24692cb6ece9)
  
     
     ![image](https://github.com/user-attachments/assets/d98f7cf8-5c91-40d9-a488-7c6bad58a4c3)
  
     
     ![image](https://github.com/user-attachments/assets/2ea14782-708b-4847-9721-b3258c069289)
  
     
     ![image](https://github.com/user-attachments/assets/b6df19b7-5b50-4643-9ef3-434b52ea8d1f)
  
     
     ![image](https://github.com/user-attachments/assets/29b607fa-8016-47b9-a309-aea35a406193)
  
     
     ![image](https://github.com/user-attachments/assets/d5440801-c968-4a02-bb1b-9e814862d3ef)


2. **Key Insights**  
   - **Gender Analysis**:  
     - Women are more likely to purchase compared to men (approx. 65%).  
   - **Top States**:  
     - Maharashtra, Karnataka, and Uttar Pradesh are the top 3 contributing states (approx. 35%).  
   - **Age-Group Analysis**:  
     - The Adult age group (30-49 years) contributes the most (approx. 50%).  
   - **Sales Channels**:  
     - Amazon, Flipkart, and Myntra are the top-performing sales channels (approx. 80%).  

## **Conclusion**
The analysis highlights key trends in customer behavior, such as the dominance of women shoppers, the importance of the Adult age group, and the top-performing states and sales channels. These insights can help Vrinda Store strategize for growth in 2023.  

![image](https://github.com/user-attachments/assets/1d799e9a-0c0b-47f2-aae4-4efb66c2d4aa)
