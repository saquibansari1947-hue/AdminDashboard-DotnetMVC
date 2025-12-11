# **Admin Dashboard Management System – ASP.NET Core 10 MVC**

This project is a fully functional **Admin Dashboard Management System** built using **ASP.NET Core 10 MVC**, **Entity Framework Core (Code First)**, and **ASP.NET Identity**.
It is designed to help administrators manage users, roles, categories, products, and other essential data through a clean, responsive, and easy-to-use dashboard interface.

The focus of this project is to learn and implement real-world backend concepts using the **MVC pattern**, **CRUD operations**, **authentication**, **authorization**, and **reusable UI components** like Tag Helpers and View Components.

---

## 🚀 **Features**

### 🔐 **Authentication & Authorization**

* Secure login & logout
* ASP.NET Core Identity integration
* Role-based access (Admin / Manager / User)
* Protected routes using `[Authorize]`

### 📦 **CRUD Operations**

Fully implemented CRUD modules for:

* Users
* Roles
* Product Categories
* Products
* Application Settings

Each module includes:

* Form validation
* Edit/View/Delete options
* Clean MVC structure

### 🧱 **Built with MVC Architecture**

* Clear separation of **Models**, **Views**, and **Controllers**
* Strongly-typed views
* Form validation via DataAnnotations
* ViewModels for clean data handling

### 🗄 **Database & EF Core (Code First)**

* Entity Framework Core for ORM
* Code First migrations
* Proper relationships (One-to-Many, Many-to-Many)
* Clean LINQ queries

### 🧩 **Tag Helpers & View Components**

Used ASP.NET Core UI features to enhance maintainability:

* Tag Helpers for forms, links, validation, and UI structure
* View Components for dashboard stats, sidebar, and reusable sections
* Partial views & layout pages for consistency

### 📊 **Admin Dashboard UI**

* Responsive Bootstrap-based admin layout
* Sidebar navigation, header, and analytics widgets
* User-friendly design for managing data efficiently

---

## 🛠 **Technology Stack**

* **.NET 10 / ASP.NET Core MVC**
* **C#**
* **Entity Framework Core**
* **SQL Server**
* **ASP.NET Core Identity**
* **Bootstrap 5**
* **Razor Views**
* **LINQ**
* **Visual Studio / VS Code**

---

## 🧪 **How to Run the Project**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Update the connection string in `appsettings.json`.

3. Run EF Core migrations:

   ```bash
   dotnet ef database update
   ```

4. Start the application:

   ```bash
   dotnet run
   ```

5. Open in browser:

   ```
   https://localhost:5001
   ```

---

## 🎯 **What I Learned**

* Implementing full MVC architecture
* Working with EF Core using Code First
* Building authentication & role-based authorization
* Designing reusable UI using Tag Helpers & View Components
* Applying CRUD operations across multiple modules
* Structuring scalable ASP.NET Core applications

---

## 📌 **Future Improvements**

* Add API layer for mobile/web integration
* Implement advanced dashboard analytics
* Add image upload for products
* Add logging & exception handling middleware
* Add dark/light theme toggle

---

## 🤝 **Contributions**

Feel free to open issues or submit pull requests if you want to improve this project.

---

## 📬 **Contact**

**Developer:** Mohammad Saquib
Email: [emailtosaquib@gmail.com](mailto:emailtosaquib@gmail.com)
GitHub: [https://github.com/your-username](https://github.com/your-username)
