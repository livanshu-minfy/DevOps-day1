# day-one-takeHome
 Building a Two-Tier Web Application Infrastructure

## I have not added my name in the screenshots , but my email id is visible in right corner of every screenshot.

the goal fo this take home assignment was to make two instances , one is a public web server and other is a private db server and the db server can only be accessed via the public web server. According to me the trick was to select another security group by its ID instead of an IP.

deliverables---->

A screenshot of your EC2 instances list, showing both the Web-Server (with a public IP) and the DB-Server (with only a private IP).
![453933989-f50ee988-5d90-45b5-b56c-94bd61760c51](https://github.com/user-attachments/assets/f4ec6528-c346-4f9f-9a25-a21bb592f9f2)

--public web-server--
![453934409-da326d22-85ec-462f-b540-3e79026c23b5](https://github.com/user-attachments/assets/23b1e073-c3cc-40fd-a484-28eea8fe4856)

--private DB-server--
![453934588-9e651ded-4aae-4b92-b217-8285daf683d7](https://github.com/user-attachments/assets/b56dffaf-7460-47fe-9acb-b8ce48664f0c)


A screenshot of the inbound rules for your database-sg Security Group.
![453936881-405477c8-a191-4fcf-b7ec-454d3a1c32bd](https://github.com/user-attachments/assets/e11232bf-61b4-4a85-a37e-94c3c640955d)


A screenshot of your terminal, showing a successful ping from the Web-Server to the DB-Server.

![Screenshot 2025-06-11 184101](https://github.com/user-attachments/assets/901bd2dc-928f-454b-b1c4-cae743bb7430)
![Screenshot 2025-06-11 184118](https://github.com/user-attachments/assets/1368af3e-add6-4acb-b230-cd539fa9e03b)


bonus challenge --->

![image](https://github.com/user-attachments/assets/cad4540e-11ff-46e3-a14a-5998a6e58f27)
![image](https://github.com/user-attachments/assets/608ba323-4eae-426d-bf9a-6ece1b925fe3)
![Screenshot 2025-06-11 190807](https://github.com/user-attachments/assets/127ab040-5c6c-4041-948f-7e6d522e9482)


After this whole assignment i made sure that I implement clenup properly i.e. terminate all instances, security groups, route tables, etc everything. 
