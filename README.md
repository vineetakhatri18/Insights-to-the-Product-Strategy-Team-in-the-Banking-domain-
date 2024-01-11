# Insights to the Product Strategy Team in the Banking domain

#### Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.
#### AtliQ Data Services came to know about this through an internal link and approached Mitron Bank with a proposal to implement this project. They provided a sample dataset of 4000 customers across five cities on their online spend and other details.
#### Peter Pandey is a data analyst at AtliQ Data Services and asked by his manager to take over this project. His role is to analyse the provided sample data and report key findings to the strategy team of Mitron Bank.

#### Tool Used: 
#### Power BI: data modelling and data visualization
#### Microsoft Powerpoint: creating design and layout

##### The data contains all the meta information regarding the columns described in the CSV files. We have provided 2 CSV files: 1. dim_customers - 4000 records 2. fact_spends - around 8,00,000 records
##### Column Description for dim_customers:
##### customer_id: This column represents the Unique ID assigned to each customer.
##### gender: This column represents the gender of the customer. (Male, Female) 
##### age_group: This column categorizes the customer into different age groups. (21-24, 25-34, 35-45, 45+) 
##### marital_status: This column indicates the marital status of the customer (single, married).
##### city: This column represents the city of residence for the customer. (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru)
##### occupation: This column denotes the occupation or profession of the customer. (Salaried IT Employees, Salaried Other Employees, Business Owners, Freelancers, Government Employees)
##### average_income: This column indicates the monthly average income of the customer, in INR currency.

##### Column Description for fact_spends:
##### customer_id: This column represents the Unique ID of each customer, linking to the dim_customer table. 
##### month: This column indicates the month in which the spending was recorded. (May, June, July, August, September, October)
##### category: This column describes the category of spending (Entertainment, Apparel, Electronics, etc).
##### payment_type: This column specifies the type of payment used by the customer (Debit Card, Credit Card, UPI, Net Banking).
##### spends: This column shows the total amount spent by the customer in the specified month, category and payment_type.
