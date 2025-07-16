# Ordering App (ASP.NET Core MVC)

A cafeteria credit ordering system built with ASP.NET Core MVC, SQL Server, Tailwind CSS, and Feather Icons.  
Employees can receive deposits (with monthly bonuses), browse restaurant menus, and place multi-item orders.

-----------------------------------

## Features

- Employee Management
- Deposit System with Monthly Bonus (R500 per R250)
- Restaurant and Menu Management
- Multi-Item Ordering with Balance Validation
- Order History for Employees
- Admin Panel to Update Order Status
- Tailwind CSS + Feather Icons for UI polish

-----------------------------------

## Tech Stack

- ASP.NET Core MVC
- Entity Framework Core (SQL Server)
- Tailwind CSS (via CDN)
- Feather Icons
- SQL Server Express

---

## Setup Instructions

### 1. Requirements

- .NET 6 SDK
- SQL Server Express
- Visual Studio Code or Visual Studio

-----------------------------------

### 2. Run the App

cd OrderingApp
dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run

-----------------------------------

### 3. How to Use App

Go to Employees to add an employee.
Use Deposit to credit their account (R250 = R500 bonus).
Add Restaurants and Menu Items.
Place an order via Orders > Create.
View Order History or manage orders in the Admin Panel.

-----------------------------------

### 4. Folder Structrure

Controllers/
Models/
Views/
 --- Employees/
 --- Restaurants/
 --- Orders/
 --- Shared/_Layout.cshtml
Data/ApplicationDbContext.cs
Services/DepositService.cs
Program.cs
appsettings.json

## Author
### Mthobisi Nxumalo
