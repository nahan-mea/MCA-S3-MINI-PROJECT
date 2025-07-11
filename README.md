# MCA-S3-MINI-PROJECT
# 🎓 Student Leave Management System

A comprehensive web-based leave management system built with Flask, featuring role-based access control, modern UI design, and complete user workflows.

## 🚀 **Live Demo**
- **URL**: `http://localhost:5000`
- **Start Command**: `python app.py`

## 👥 **User Roles & Functions**

### **🎓 Students**
**Avatar**: Blue graduation cap icon (`fas fa-user-graduate`)

**Functions:**
- ✅ Apply for leave requests
- ✅ View leave application history
- ✅ Search and filter leave applications
- ✅ Calendar view with leave status visualization
- ✅ View leave statistics and charts
- ✅ Sort leave applications by various criteria

**Dashboard Features:**
- Modern interface with role-based avatar
- Real-time statistics (Pending/Approved/Rejected)
- Interactive charts and visualizations
- Responsive design for all devices

### **👨‍🏫 Teachers**
**Avatar**: Green teacher icon (`fas fa-chalkboard-teacher`)

**Functions:**
- ✅ Apply for personal leave requests
- ✅ Approve/reject student leave applications
- ✅ View all student leave requests
- ✅ Manage own leave history
- ✅ View leave statistics and charts
- ✅ Sort and filter leave applications

**Dashboard Features:**
- Student leave approval interface
- Personal leave management
- Statistics dashboard
- Role-based avatar display

### **👔 Principals**
**Avatar**: Red business person icon (`fas fa-user-tie`)

**Functions:**
- ✅ Approve/reject all leave applications (students & teachers)
- ✅ Manage user accounts (add, edit, delete)
- ✅ View complete system statistics
- ✅ Monitor all leave activities
- ✅ User role management
- ✅ System administration

**Dashboard Features:**
- Complete user management interface
- System-wide leave overview
- Advanced statistics and analytics
- Administrative controls

## 🎨 **Key Features**

### **🔐 Authentication & Security**
- Role-based access control
- Session management
- Secure password validation
- User input sanitization

### **📊 Dashboard Analytics**
- Real-time statistics
- Interactive charts (Chart.js)
- Leave status visualization
- Role-specific metrics

### **🔍 Search & Filter**
- Search by leave reason
- Filter by status (Pending/Approved/Rejected)
- Sort by multiple criteria
- Advanced filtering options

### **📅 Calendar Integration**
- Visual calendar view for students
- Color-coded leave status
- Date range navigation
- Leave period visualization

### **👤 User Management**
- Add new users (Principals only)
- Edit user information
- Delete user accounts
- Role assignment
- Avatar-based user identification

### **📱 Modern UI/UX**
- Bootstrap 5 responsive design
- Role-based avatar system
- Hover animations and effects
- Professional color scheme
- Mobile-friendly interface

## 🛠️ **Technical Stack**

### **Backend**
- **Framework**: Flask (Python)
- **Database**: SQLite
- **Authentication**: Session-based
- **Validation**: Custom input validation

### **Frontend**
- **CSS Framework**: Bootstrap 5
- **Icons**: Font Awesome 6
- **Charts**: Chart.js
- **Styling**: Custom CSS with gradients

### **Features**
- **Responsive Design**: Works on all devices
- **Real-time Updates**: Live statistics
- **Data Visualization**: Interactive charts
- **User Experience**: Intuitive navigation

## 📁 **Project Structure**

```
STUDENTLEAVEMANAGEMENT/
├── app.py                 # Main Flask application
├── leave.db              # SQLite database
├── templates/            # HTML templates
│   ├── login.html       # Login page
│   ├── student.html     # Student dashboard
│   ├── teacher.html     # Teacher dashboard
│   ├── principal.html   # Principal dashboard
│   ├── calendar.html    # Calendar view
│   ├── manage_users.html # User management
│   ├── add_user.html    # Add user form
│   └── edit_user.html   # Edit user form
├── venv/                # Virtual environment
├── requirements.txt     # Python dependencies
├── setup.py            # Installation script
└── README.md           # This file
```

## 🚀 **Quick Start**

### **1. Installation**
```bash
# Clone or download the project
cd STUDENTLEAVEMANAGEMENT

# Install dependencies
pip install -r requirements.txt
```

### **2. Run the Application**
```bash
python app.py
```

### **3. Access the System**
- Open browser: `http://localhost:5000`
- Login with any user credentials

## 👤 **Default Users**

### **Students**
- Username: `student1`, Password: `password`
- Username: `student2`, Password: `password`

### **Teachers**
- Username: `teacher1`, Password: `password`
- Username: `teacher2`, Password: `password`

### **Principals**
- Username: `principal1`, Password: `password`

## 🎯 **System Workflow**

### **Student Leave Application**
1. Student logs in → Student Dashboard
2. Fills leave application form
3. Submits request → Status: Pending
4. Teacher/Principal reviews and approves/rejects
5. Student can view updated status

### **Teacher Approval Process**
1. Teacher logs in → Teacher Dashboard
2. Views pending student applications
3. Approves or rejects requests
4. Can apply for own leave (approved by Principal)

### **Principal Administration**
1. Principal logs in → Principal Dashboard
2. Manages all users (add/edit/delete)
3. Approves/rejects all leave applications
4. Monitors system statistics

## 📊 **Database Schema**

### **Users Table**
- `id` (Primary Key)
- `username` (Unique)
- `password`
- `role` (student/teacher/principal)

### **Leaves Table**
- `id` (Primary Key)
- `user_id` (Foreign Key)
- `from_date`
- `to_date`
- `reason`
- `status` (pending/approved/rejected)
- `applied_by`

## 🎨 **Design Features**

### **Avatar System**
- **Students**: Blue graduation cap
- **Teachers**: Green teacher icon
- **Principals**: Red business person
- Hover animations and effects
- Role-based color coding

### **UI Components**
- Modern gradient backgrounds
- Glass-morphism effects
- Responsive grid layouts
- Interactive buttons and forms
- Professional typography

## 🔧 **Advanced Features**

### **Data Visualization**
- Pie charts for leave distribution
- Bar charts for statistics
- Interactive legends
- Real-time data updates

### **Search & Filter**
- Multi-criteria search
- Status-based filtering
- Date range selection
- Sort by any column

### **Calendar View**
- Monthly calendar display
- Color-coded leave periods
- Navigation between months
- Visual status indicators

## 📱 **Responsive Design**
- Mobile-first approach
- Tablet-friendly interface
- Desktop optimization
- Cross-browser compatibility

## 🛡️ **Security Features**
- Input validation and sanitization
- SQL injection prevention
- XSS protection
- Session management
- Role-based access control

## 🚀 **Deployment Ready**
- Production-ready code
- Environment configuration
- Database setup scripts
- Documentation included

---

## 📝 **Project Summary**

This Student Leave Management System is a complete web application that demonstrates:

- **Full-stack development** with Flask and modern web technologies
- **Role-based access control** with secure authentication
- **Database design** and management with SQLite
- **Modern UI/UX** with responsive design and animations
- **Data visualization** with interactive charts
- **User experience** design with intuitive workflows
- **Professional development** practices and code organization

**Perfect for academic submissions, portfolio projects, and real-world applications!** 🎓✨

---

**Developed by**: Nahan  
**Technology**: Flask, Bootstrap, SQLite, Chart.js  
**Features**: 15+ core functionalities with modern UI/UX  
**Status**: Production Ready ✅
