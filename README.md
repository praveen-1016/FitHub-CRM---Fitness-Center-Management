# 🏋️ Fit Hub CRM

## 📌 Introduction
Fit Hub CRM is a comprehensive gym and fitness management system developed to simplify the daily operations of fitness centers. The system is designed to handle customer relationships, membership management, payments, scheduling, and reporting in an organized and efficient manner.

In modern fitness businesses, managing data manually can be time-consuming and error-prone. Fit Hub CRM solves this problem by providing a centralized digital platform that automates tasks and improves productivity.

---

## 🎯 Objectives
- To manage customer information effectively  
- To automate membership and payment processes  
- To reduce manual work and human errors  
- To improve customer engagement and satisfaction  
- To provide analytical insights for business growth  

---

## 🚀 Key Features

### 👤 Customer Management
- Add, update, and delete member details  
- Store contact information and membership history  
- Track active and inactive members  

### 💳 Membership Management
- Create and manage membership plans  
- Track subscription start and end dates  
- Send renewal reminders  

### 💰 Payment & Billing
- Record payment details  
- Track pending and completed payments  
- Generate invoices and receipts  

### 📅 Class Scheduling
- Schedule fitness classes and sessions  
- Allow booking for members  
- Manage time slots and availability  

### 👨‍🏫 Trainer Management
- Maintain trainer profiles  
- Assign trainers to classes  
- Track trainer schedules  

### 📊 Reports & Analytics
- Generate sales and revenue reports  
- Analyze membership growth  
- Monitor business performance  

### 🔔 Notifications
- Send alerts for membership expiry  
- Notify users about new classes or offers  

---

## 🛠️ Technologies Used
- *Frontend:* HTML, CSS, JavaScript  
- *Backend:* Node.js / Java / Python  
- *Database:* MySQL / MongoDB  
- *Tools:* Git, VS Code  

---

## ⚙️ System Requirements
- Operating System: Windows / Linux / macOS  
- Browser: Chrome / Edge / Firefox  
- RAM: Minimum 4GB  
- Internet connection (optional for cloud features)

- ## *Fitness Center Management System using Salesforce*


## *1. Project Overview*

The *Fitness Center Management System* is a Salesforce-based application designed to manage gym operations efficiently. It helps automate member registration, trainer management, subscription tracking, attendance, and payments.

Using Salesforce features like objects, flows, and Apex, the system improves operational efficiency, reduces manual work, and enhances customer experience.


 *2. Business Objectives*

* To digitize gym operations
* To manage member details and subscriptions
* To track attendance and workout sessions
* To manage trainers and schedules
* To automate billing and payments
* To generate reports for decision-making


 *3. Functional Scope*
*Included Features*

* Member Registration & Management
* Trainer Management
* Membership Plans
* Attendance Tracking
* Payment Processing
* Notifications & Reminders
* Reports & Dashboards

*Excluded Features*

* Third-party payment gateway integration (optional)
* Mobile app development



*4. Stakeholder Mapping*

| Stakeholder      | Role                      |
| ---------------- | ------------------------- |
| Admin            | Manage entire system      |
| Trainer          | Handle members & workouts |
| Members          | Access plans & schedules  |
| Finance Team     | Manage payments           |
| System Developer | Maintain system           |


 *5. System Architecture*

* Platform: Salesforce CRM
* Components:

  * Standard Objects (User, Account)
  * Custom Objects (Member, Trainer, Plan)
  * Automation (Flows, Apex)
  * UI (Lightning App)


 *6. Salesforce Implementation*

 *6.1 Custom Objects*

| Object Name     Description             
| Member          Stores member details   
| Trainer         | Stores trainer details  
| Membership Plan | Stores plan info        
| Attendance      | Tracks daily attendance 
| Payment         | Stores payment records 

---

 *6.2 Fields (Examples)*

 *Member Object*

* Name (Text)
* Age (Number)
* Gender (Picklist)
* Phone (Phone)
* Email (Email)
* Membership Plan (Lookup)
* Join Date (Date)
* Status (Active/Inactive)

 *Trainer Object*

* Name
* Specialization
* Experience
* Contact Details

*Membership Plan*

* Plan Name
* Duration (Months)
* Fee
* Description



 *7. Relationships*

* Member → Membership Plan (Lookup)
* Member → Trainer (Lookup)
* Payment → Member (Master-Detail)
* Attendance → Member (Master-Detail)


*8. Validation Rules*

Examples:

* Age must be greater than 15
* Email must be in valid format
* Payment amount cannot be negative

 *9. Automation*

 *9.1 Flows*

* *Member Registration Flow*

  * Automatically assign trainer
  * Send welcome message

* *Payment Reminder Flow*

  * Trigger before plan expiry

* *Attendance Flow*

  * Mark daily check-in



*9.2 Apex Triggers*

* Update membership status when expired
* Calculate remaining days
* Auto-create payment record
    


 *9.3 Scheduled Apex*

* Run daily to check expired memberships
* Send notifications to members

    

 *10. Lightning App*

App Name: Fitness Center App

 Tabs Included:

* Members
* Trainers
* Membership Plans
* Payments
* Attendance
* Reports


 *11. Reports & Dashboards*
 Reports:

* Active Members
* Expired Memberships
* Monthly Revenue
* Trainer Performance

 Dashboard:

* Total Members
* Revenue Graph
* Attendance Trends



*12. Security Model*

 Roles:

* Admin
* Trainer
* Staff

Profiles:

* Full Access (Admin)
* Limited Access (Trainer)

 Permissions:

* Object-level and field-level security applied



 *13. Testing*

* Unit Testing for Apex
* Flow Testing
* User Acceptance Testing (UAT)


 *14. Deployment*

Steps:

1. Develop in Sandbox
2. Test all functionalities
3. Deploy using Change Sets
4. Validate in Production


*15. Benefits of the System*

* Reduces manual work
* Improves accuracy
* Saves time
* Enhances customer satisfaction
* Better data management
       
 *16. Limitations*

* Depends on internet connection
* Limited offline access
* Requires Salesforce knowledge

---

 *17. Future Enhancements*

* Mobile application integration
* AI-based fitness recommendations
* Payment gateway integration
* Wearable device tracking


 *18. Conclusion*

The *Fitness Center Management System* built on Salesforce provides a scalable and efficient solution for managing gym operations. It improves productivity, ensures better customer management, and supports business growth

## *Fitness Center Management System using Salesforce*

---

## *1. Project Overview*

The *Fitness Center Management System* is a Salesforce-based application designed to manage gym operations efficiently. It helps automate member registration, trainer management, subscription tracking, attendance, and payments.

Using Salesforce features like objects, flows, and Apex, the system improves operational efficiency, reduces manual work, and enhances customer experience.

---

## *2. Business Objectives*

* To digitize gym operations
* To manage member details and subscriptions
* To track attendance and workout sessions
* To manage trainers and schedules
* To automate billing and payments
* To generate reports for decision-making

---

## *3. Functional Scope*

### *Included Features*

* Member Registration & Management
* Trainer Management
* Membership Plans
* Attendance Tracking
* Payment Processing
* Notifications & Reminders
* Reports & Dashboards

### *Excluded Features*

* Third-party payment gateway integration (optional)
* Mobile app development

---

## *4. Stakeholder Mapping*

| Stakeholder      | Role                      |
| ---------------- | ------------------------- |
| Admin            | Manage entire system      |
| Trainer          | Handle members & workouts |
| Members          | Access plans & schedules  |
| Finance Team     | Manage payments           |
| System Developer | Maintain system           |

---

## *5. System Architecture*

* Platform: Salesforce CRM
* Components:

  * Standard Objects (User, Account)
  * Custom Objects (Member, Trainer, Plan)
  * Automation (Flows, Apex)
  * UI (Lightning App)

---

## *6. Salesforce Implementation*

### *6.1 Custom Objects*

| Object Name     | Description             |
| --------------- | ----------------------- |
| Member          | Stores member details   |
| Trainer         | Stores trainer details  |
| Membership Plan | Stores plan info        |
| Attendance      | Tracks daily attendance |
| Payment         | Stores payment records  |

---

### *6.2 Fields (Examples)*

#### *Member Object*

* Name (Text)
* Age (Number)
* Gender (Picklist)
* Phone (Phone)
* Email (Email)
* Membership Plan (Lookup)
* Join Date (Date)
* Status (Active/Inactive)

#### *Trainer Object*

* Name
* Specialization
* Experience
* Contact Details

#### *Membership Plan*

* Plan Name
* Duration (Months)
* Fee
* Description

---

## *7. Relationships*

* Member → Membership Plan (Lookup)
* Member → Trainer (Lookup)
* Payment → Member (Master-Detail)
* Attendance → Member (Master-Detail)

---

## *8. Validation Rules*

Examples:

* Age must be greater than 15
* Email must be in valid format
* Payment amount cannot be negative

---

## *9. Automation*

### *9.1 Flows*

* *Member Registration Flow*

  * Automatically assign trainer
  * Send welcome message

* *Payment Reminder Flow*

  * Trigger before plan expiry

* *Attendance Flow*

  * Mark daily check-in

---

### *9.2 Apex Triggers*

* Update membership status when expired
* Calculate remaining days
* Auto-create payment record
    
trigger MembershipExpiryTrigger on Member__c (before update) {
    for(Member__c m : Trigger.new) {
        if(m.Expiry_Date_c != null && m.Expiry_Date_c < Date.today()) {
            m.Status__c = 'Inactive';
        }
    }
}

### *9.3 Scheduled Apex*

* Run daily to check expired memberships
* Send notifications to members

     global class MembershipReminder implements Schedulable {
    global void execute(SchedulableContext sc) {
        List<Member__c> members = [
            SELECT Id, Name, Expiry_Date_c, Email_c
            FROM Member__c
            WHERE Expiry_Date__c = :Date.today().addDays(3)
        ];

        for(Member__c m : members) {
            System.debug('Reminder for: ' + m.Name);
        }
    }
}

## *10. Lightning App*

### App Name: Fitness Center App

#### Tabs Included:

* Members
* Trainers
* Membership Plans
* Payments
* Attendance
* Reports

---

## *11. Reports & Dashboards*

### Reports:

* Active Members
* Expired Memberships
* Monthly Revenue
* Trainer Performance

### Dashboard:

* Total Members
* Revenue Graph
* Attendance Trends

---

## *12. Security Model*

### Roles:

* Admin
* Trainer
* Staff

### Profiles:

* Full Access (Admin)
* Limited Access (Trainer)

### Permissions:

* Object-level and field-level security applied

---

## *13. Testing*

* Unit Testing for Apex
* Flow Testing
* User Acceptance Testing (UAT)

---

## *14. Deployment*

Steps:

1. Develop in Sandbox
2. Test all functionalities
3. Deploy using Change Sets
4. Validate in Production

---

## *15. Benefits of the System*

* Reduces manual work
* Improves accuracy
* Saves time
* Enhances customer satisfaction
* Better data management

---

## *16. Limitations*

* Depends on internet connection
* Limited offline access
* Requires Salesforce knowledge

---

## *17. Future Enhancements*

* Mobile application integration
* AI-based fitness recommendations
* Payment gateway integration
* Wearable device tracking

---

## *18. Conclusion*

The *Fitness Center Management System* built on Salesforce provides a scalable and efficient solution for managing gym operations. It improves productivity, ensures better customer management, and supports business growth.
