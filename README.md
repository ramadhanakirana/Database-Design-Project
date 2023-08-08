# Final Project Database Design and Programming with SQL - Digitalent KOMINFO
🛠️ Tool: DBeaver (using MySQL)

# 📄 Case
PT. Nusantara Building Industries is a national private company engaged in building materials industry activities. Currently, the company has more than 5000 employees working in various fields, including CEO, management, accountants, and technicians. To track each employee's ownership, a system is needed that can store basic information about each employee, such as the date of recruitment and the date of resignation from the company. In addition, information on the division of labor for each employee also needs to be known so that the division of labor is in accordance with their specialization.<br>
It was informed that the divisions owned by the company are spread across several locations in Indonesia. Making it possible for a division to be in more than one location, such as the distribution, sales, receiving, and payroll departments. Therefore, the company has more than one office building for each of its divisions. Information related to office buildings needs to be stored so that it is easier for companies to contact their employees in various divisions at different locations. <br>
In sales, PT. Nusantara Building Industries does not only sell finished products but also raw materials. Sales only serve retailers, not individuals. So to launch its business, the company cooperates with many suppliers of raw materials and logistics companies. To fulfill each order, the company needs to know from which suppliers raw materials must be ordered, prices, supplier contact information, and methods of delivery of goods.<br>
For every order of finished products/raw materials by a retailer, the system records the order quantity, the quantity sent, and information on how to send the goods (transportation). For goods delivery methods, it is necessary to know the logistics company's information, the type of shipping transportation used (land, sea, or air) and the percentage discount given by the company. This information is used to determine how the order will be sent to the retailer.<br>

# 🔍 Objectives
1. Business and mission of PT. Nusantara Building Industries.
2. Information requirements.
3. Business rules.
4. Assumption.
5. Database Design.

# 🙌 Results
## 👨‍💼 Business and mission of PT. Nusantara Building Industries
1. PT. Nusantara Building Industries is a company engaged in the building materials industry that supplies both raw and finished goods throughout Indonesia.
2. PT. Nusantara Building Industries maintains good relations with the suppliers it works with and the shipping service companies it works with.
3. PT. Nusantara Building Industries has a mission to expand connections to suppliers and other shipping service companies.
4. PT. Nusantara Building Industries requires a system to fulfill every order, with the aim of knowing from which suppliers raw materials must be ordered, prices, supplier contact information, and methods of delivery of goods.

## 💁 Information requirements
1. PT. Nusantara Building Industries requires data on company branches, warehouses, and employees who work according to their departments.
2. PT. Nusantara Building Industries needs information about suppliers, service companies used, and routes to be used for delivery.
3. Each warehouse located in a company branch is required to manage stock, prices, and deliveries to suppliers.

## ❔ Business rules
1. Order data for each customer to make it easier to check to find out shipments and stock items in the warehouse.
2. There are two types of products sold: finished products and raw materials.
3. Warehouse PT. Nusantara Building Industries is located in several areas.
4. Apart from warehouses, PT. Nusantara Building Industries also has several offices. 1 head office and several branches.
5. Line of delivery of goods to customers on request customer.
6. Each warehouse is responsible for managing stock and establishing communication with other divisions if the stock of goods is at the lower limit.

## 🤔 Assumption
1. The client knows that personal data regarding his company will be shared with other teams for the purpose of the company's interests.
2. The company knows that client data is private, so it only provides it to divisions that really need it.
3. Data within a period of >3 years will be entered into the 'history' database so that it is not mixed with the data currently used.

## 🔄️ Database design (Entity Relationship Diagram)
From the information above, a database design can be created, as shown in Figure 1.
<p align="center">
![image](https://github.com/ramadhanakirana/Database-Design-Project/assets/102908444/7e33a054-2438-4fdc-9281-4adfcb689636)
</p>
<p align="center">Figure 1. ERD.</p> <br>
P.s The syntax is attached.

# 🪄 Conclusions
1. PT. Nusantara Building Industries requires a system to simplify the company's internal managerial processes (employees, warehouses, branch offices) and those of external companies (suppliers, service companies).
2. A good and systematic database design can help companies manage their management efficiently.

# 👇 Recommendation
1. Create a database per company branch and warehouse so that data can be managed easily.
2. Separating the finished product and raw product entities is necessary because large companies have a large variety of products.
