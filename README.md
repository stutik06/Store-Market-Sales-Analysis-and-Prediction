# Store-Market-Sales-Analysis-and-Prediction
 ### **Store Market Sales Prediction Using XGBoost Regression – Detailed Description**

- **Objective:**  
   - To predict sales across different stores using the **XGBoost regression model**, which offers high accuracy and efficiency for structured data.  

- **Data Preprocessing:**  
   - **Encoding:**  
      - Applied **Label Encoding** to transform categorical variables (`Item_Type`, `Outlet_Size`, `Outlet_Location_Type`) into numerical values, making them compatible with the model.  
   - **Feature Scaling:**  
      - Normalized continuous features like `Item_Visibility` and `Item_MRP` to standardize the range of values, ensuring better model performance.  

- **Exploratory Data Analysis (EDA):**  
   - **Outlet Establishment Year:** Stores established in **1985** dominate the dataset, indicating they have the largest sales volume.  
   - **Product Categories:**  
      - **Fruits and Vegetables** and **Snack Foods** are the top-selling categories, highlighting customer preferences.  
   - **Outlet Size Distribution:**  
      - Medium-sized outlets generate higher sales, suggesting they are the most profitable.  

- **Model Implementation:**  
   - Utilized the **XGBoost Regressor** for its fast training speed and accuracy.  
   - Applied **Grid Search** or **Randomized Search** (if used) to optimize hyperparameters, improving the model's predictive performance.  

- **Model Performance:**  
   - Achieved **high accuracy** with minimal error, indicating the model effectively captures sales patterns.  
   - The model provides reliable predictions, helping retailers optimize inventory management and pricing strategies.  

- **Business Impact:**  
   - **Sales Forecasting:** Improved prediction accuracy enables better planning and resource allocation.  
   - **Data-Driven Decisions:** Retailers can enhance promotions, pricing, and store operations based on sales insights.

![Screenshot (36)](https://github.com/user-attachments/assets/f311fe1a-ffc9-4bd3-aff5-8fed22fb096c)
![Screenshot (37)](https://github.com/user-attachments/assets/f3b457a9-2e59-47d2-9fd2-532b62f25ba6)
![Screenshot (38)](https://github.com/user-attachments/assets/f1302a35-395a-4d7b-aa95-07819df612d9)
![Screenshot (42)](https://github.com/user-attachments/assets/2889e020-f769-4464-a380-3a4548d1efb1)
![Screenshot (44)](https://github.com/user-attachments/assets/4b21cc6a-21ac-489d-853b-22f3e57d16b2)

