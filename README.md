# Company-Order
Have you ever wanted to see a code in java that allows you to act as a Company owner... Well here you are

This code represents an inventory management system for a variety of products.

Product Class: This abstract class represents a  product in the inventory. It contains fields for the name, price, type, and amount of the product. It has methods to set and get the amount, calculates the total price based on quantity, and get the inventory size.

RProduct, SProduct, BProduct Classes: These classes represent specific types of products (Regular, Seasonal, Bulk) and extend the Product class. They provide implementations for the total price calculation method based on their respective pricing rules. Bc as you may no, when and how you buy the product changes things.

Date Class: Represents a date with methods to get the month, day, and year. It's used to represent the date associated with seasonal products.

Order Class: Represents an order with fields for the product, quantity, and date. It has a method to convert the order details into a string representation.

NajaniDriver Class: This is the driver class for the code. It's named after me, Najani/ It provides a menu-driven interface for interacting with the inventory system. It allows users to view the inventory, make orders, review orders, and exit the program. It also includes methods for displaying inventory, making orders, showing orders, saving orders to a file, and searching for products in the inventory.

Data: At the end of the code, there's a list of products with their names, prices, and quantities. This data represents the initial inventory that the system loads from a file (data.txt) when the program starts. You can change this to wtv you want if u wanna play around. 
