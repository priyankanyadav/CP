# CP Gyan 📱🐄

**A mobile-based Milk Chilling Center (MCC) Management System**

---

## 🚀 Project Overview

**CP Gyan** is a mobile application developed for a milk-based product company to manage their milk procurement and chilling operations. It supports farmers, MCC staff, and administrators in streamlining milk collection, quality testing, inventory tracking, and complaint management.

The system primarily focuses on the digitalization of milk procurement at **Milk Chilling Centers (MCCs)** and tracks data from **farmers to final tanker dispatch** through various operational modules.

---

## 📦 Key Features

### ✅ Farmer & Member Management
- Registration of farmers who supply milk to MCCs.
- Passbook Management: Tracks milk quantity, FAT, SNF, and financials.
- OTP-based login for farmers via mobile number.

### ✅ MCC Operations
- Monitor milk collection from farmhouses.
- Milk quality measurement using **FAT machines**.
- Track tanker dispatch between MCCs and final destinations.

### ✅ Mobile App Integration
- CP Gyan mobile app allows farmers to register, view their data, and interact with the MCC.
- OTP-based user authentication.
- Role-based authorization and pre-login checks.

### ✅ Key Modules and APIs

#### 🧑‍🌾 User Module
- User Registration & Login (with OTP)
- Authentication & Authorization
- Pre-login APIs
- Active user tracking

#### 🛠️ Miscellaneous Module
- Master Services (Master Data APIs)
- Workflow Services (Dynamic Flow APIs)

#### 📦 Inventory Module
- Asset Management (Create, Register, Update Assets)
- Indent APIs (Create & Manage Indents)

#### 🧾 Complaint (CTA) Module
- Attendance Management
- Complaints Registration and Resolution
- Task Activities
- Punch In / Punch Out APIs

#### 🐄 Animal Inspection Module
- Assign Animal Inspectors (like veterinary doctors)
- Track doctor visits and treatments

#### 🛒 Procurement Module
- Milk procurement cycle from farm to MCC
- Track quantity, quality (FAT & SNF), and location

---

## 🛠️ Technologies Used

- **Backend**: .NET 8 Web API
- **Database**: SQL Server / MySQL
- **Caching**: Redis
- **Mobile App**: Android App (CP Gyan)
- **Authentication**: OTP-based system
- **Tools**: Swagger, Postman, Git

---

## 📈 Architecture Overview

1. **Farmer** sends milk to **MCC**
2. MCC tests and records milk using **FAT Machine**
3. Milk is loaded into **Tanker**
4. App tracks data through APIs across modules
5. Backend syncs data and logs activities
6. Admin can monitor everything from a dashboard

---

## 📲 How to Use the App

1. Farmer receives download link from MCC
2. Downloads **CP Gyan** app
3. Registers with mobile number
4. Verifies via OTP
5. Accesses dashboards, passbook, complaints, and more

---

## 📚 Folder Structure (Backend APIs)

/Controllers

UserController.cs

InventoryController.cs

ComplaintController.cs

MiscellaneousController.cs

/Services

UserService.cs

WorkflowService.cs

AssetService.cs

/Models

Farmer.cs

Complaint.cs

Inventory.cs

/Helpers

OTPHelper.cs

AuthMiddleware.cs

## 🤝 Contributions

Developed and maintained by **Priyanka Yadav**  
- .NET API Development  
- Workflow & Master Data APIs  
- Indent & Asset Modules  
- CTA Module: Complaints & Attendance  
- OTP Authentication

---

## 📩 Contact

For any queries or feedback, reach out to:  
📧 PriyankaNYadav1144@gmail.com

