Create table Customer(
Cust_Id int primary key,
Cust_Name varchar(30) not null,
Cust_Address1 varchar(20),
Cust_Address2 varchar(30),
Pincode int default 462030,
CUst_phone varchar(10));

Alter table Customer add column Email varchar(30);
Update column Email 
Insert into Customer values()
Alter table Customer drop column Email ;
Drop table Customer
Update salary (Select salary*1.1 from Employee where salary=salary*1.1)
 

Create table furniture (
No int primary key,
Item_name varchar(20) not null,
Type varchar(20),
DATEOFSTOCK date,
Price double
Discount double);

Select * from Furniture where type=’Baby Cot’
Select itemname from furniture where price>15000
Select itemname, type from furniture where dateofstock<2002-02-01 order by itemname desc;
Select * from furniture where itemname like ‘%t’
