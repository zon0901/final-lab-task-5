# Finals Task 5 Using SQL views and Stored Procedures and Stored Functions



In this activity, we used MySQL to create SQL views, stored procedures, and functions. Tasks included filtering product data, computing total prices by vendor, updating vendor names, and retrieving product details based on parameters.


## CREATE A VIEW that will display the vendors_code, vendors name, product description p_indate, of all products with p_indate from 2002 onwards.


SQL Statement:


![image](https://github.com/user-attachments/assets/c64d9183-3b2d-491e-a5c2-233fe70ac8e6)


Output:

![image](https://github.com/user-attachments/assets/ab32fa4b-9f5e-40eb-9183-61f66d962de0)


## CREATE a VIEW that will display all products whose price range is between 100-150.


SQL Statement:


![image](https://github.com/user-attachments/assets/d19d2719-8698-4c54-8c6a-d6801116e189)

Output:


![image](https://github.com/user-attachments/assets/02aa16f8-7957-4271-9ee1-682e1e18542d)

## CREATE a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with the following v_code (21344, 23119 and 24288).

SQL Statement:


![image](https://github.com/user-attachments/assets/1e794a51-d7d2-42e8-b4f3-ad133bd559cf)

Output:


![image](https://github.com/user-attachments/assets/383c1906-0fa4-4e50-bb04-e397022c5ece)

## CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.

SQL Statement:


![image](https://github.com/user-attachments/assets/600fc5cd-4074-49e8-9faa-6305d71198a0)

Output:


![image](https://github.com/user-attachments/assets/f527668b-3d38-46e8-916b-fa66d4af8d6f)

## CREATE A Function that will take 2 parameters(v_code and v_state) and display All the product description and price based on the parameters passed to the function


SQL Statement


![image](https://github.com/user-attachments/assets/f6a8d8e7-ef5b-46a2-bc7c-0a7c7f3ffa23)

Output:


![image](https://github.com/user-attachments/assets/354fdbe9-dba8-4e56-b93d-39a908c66e09)









