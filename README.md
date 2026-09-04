# Academic Calendar and Leave Management System

## About the Project

The Academic Calendar and Leave Management System is a web application developed using ASP.NET Core Razor Pages.

The system allows students to:

- Login to the system
- View the academic calendar
- View important academic events
- Apply for leave
- Select different types of leave
- Enter leave dates
- Provide a reason for leave
- Select a workload plan
- View their leave history
- Logout from the system

The project also demonstrates the use of **Session and Cookies** in ASP.NET Core.

---

## Technologies Used

- ASP.NET Core 7.0
- Razor Pages
- C#
- HTML
- CSS
- Bootstrap
- Session Management
- Cookies

---

## Main Features

### 1. Login

Students can enter their User ID and Password to access the system.

The login information is maintained using ASP.NET Core Session.

### 2. Academic Calendar

The Academic Calendar displays important academic events such as:

- Independence Day
- Teachers' Day
- Gandhi Jayanti
- Mid-term Examination
- Children's Day
- End Semester Examination

### 3. Leave Management

Students can submit leave applications by providing:

- Student Name
- Leave Type
- From Date
- To Date
- Reason
- Workload Plan

### 4. Leave History

Submitted leave applications are displayed in the Leave History section.

### 5. Session Management

Session is used to maintain the logged-in student's information while navigating through the application.

### 6. Cookie Management

Cookies are used as part of the application's user/session management functionality.

### 7. Responsive Design

The application uses responsive CSS so that the interface adjusts to different screen sizes including:

- Desktop
- Laptop
- Tablet
- Mobile

---

## Project Structure

```text
AcademicLeaveSystem
│
├── Pages
│   ├── Index.cshtml
│   ├── Index.cshtml.cs
│   ├── Login.cshtml
│   ├── Login.cshtml.cs
│   ├── Leave.cshtml
│   ├── Leave.cshtml.cs
│   └── Shared
│
├── wwwroot
│   ├── css
│   │   └── site.css
│   │
│   ├── js
│   │   └── site.js
│   │
│   └── lib
│
├── Properties
│   └── launchSettings.json
│
├── appsettings.json
├── appsettings.Development.json
├── Program.cs
└── README.md
