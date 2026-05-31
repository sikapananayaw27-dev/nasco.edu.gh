# 🎓 Natilla School Complex Website

A complete, luxury school management website for **Natilla School Complex** located at Abrafo, Cape Coast, near Kakum National Park, Ghana.

![Theme](https://img.shields.io/badge/Theme-Top%20Yellow%20→%20Down%20Green-gold)
![License](https://img.shields.io/badge/License-Free-green)

## 🌟 Features

### For Visitors (Public Website)
- ✅ **Beautiful Landing Page** — Luxury cream, smooth, elegant design with yellow-green theme
- ✅ **School History** — Editable about section with timeline
- ✅ **Class Enrollment** — Display of all classes from Creche to Basic 9
- ✅ **Teachers Directory** — Public-facing teacher profiles with photos
- ✅ **Online Admission Form** — New students can apply directly
- ✅ **School Prospectus** — Downloadable prospectus
- ✅ **Complaints & Enquiries** — Contact form for parents and students
- ✅ **Student Login** — Simple login with name and date of birth

### For Students (Student Portal)
- ✅ **Secure Login** — Name + Date of Birth authentication
- ✅ **View Results** — Access termly academic results uploaded by teachers
- ✅ **Books Library** — Read and download books uploaded by admin
- ✅ **Submit Complaints** — Send complaints/enquiries directly
- ✅ **View Profile** — Personal information and photo
- ✅ **Logout** — Secure session management

### For Admin (Management Dashboard)
- ✅ **Total Access Control** — Full control over all data
- ✅ **Student Management** — Add, edit, delete students with photos and info
- ✅ **Teacher Management** — Add, edit, delete teachers with photos and bios
- ✅ **Results Management** — Input termly results for each student
- ✅ **Books Library** — Upload books (PDF, images) for students
- ✅ **Admission Applications** — Review and approve/reject applications
- ✅ **Complaints Management** — View and manage all complaints
- ✅ **Edit Website Content** — Modify text on the main website
- ✅ **Dashboard Statistics** — Overview counts and recent activity

## 🎨 Design

- **Primary Colors**: Top Yellow → Down Green
- **Style**: Cream, smooth, elegant, neat
- **Typography**: Playfair Display (headings) + Inter (body)
- **Animations**: Smooth transitions, floating elements, hover effects
- **Responsive**: Works on desktop, tablet, and mobile

## 🗂️ File Structure

```
natilla-school/
├── index.html           # Main public website
├── admin.html           # Admin dashboard
├── student-portal.html  # Student login & portal
├── css/
│   └── style.css        # Luxury styling (30,000+ lines)
├── js/
│   └── app.js           # Application logic & database
└── images/              # Store uploaded images
```

## 🚀 How to Use

### 1. Deploy to GitHub Pages
1. Create a new repository on GitHub
2. Upload all files from this folder
3. Go to Settings → Pages → Select main branch
4. Your site will be live at `https://yourusername.github.io/natilla-school/`

### 2. Admin Access
- **Username**: `admin`
- **Password**: `admin123`
- Access: `your-site.com/admin.html`

### 3. Student Login
- Students login with their **Full Name** and **Date of Birth**
- Access: `your-site.com/student-portal.html`

### 4. Adding Data
All data is stored in the browser's **localStorage**:
- Add students via Admin → Students → Add Student
- Add teachers via Admin → Teachers → Add Teacher
- Upload books via Admin → Books Library → Add Book
- Input results via Admin → Results → Select Student
- Edit website text via Admin → Edit Website

## ⚠️ Important Notes

- **Data Storage**: All data is stored in the browser's localStorage. This means:
  - Data persists on the same device/browser
  - Data is NOT shared between different devices
  - Clearing browser data will erase all information
  - For production use, consider migrating to a real backend database

- **Images**: Passport pictures and book covers are stored as base64 data URLs within localStorage. Large images may hit storage limits.

- **Security**: This is a frontend-only application. The admin password is hardcoded for simplicity. For production, implement proper backend authentication.

## 📍 Location

**Natilla School Complex**
- Abrafo, Cape Coast
- Near Kakum National Park
- Central Region, Ghana

## 📝 Classes Offered

- Creche
- Nursery
- Kindergarten
- Basic 1 through Basic 9

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom design system)
- Vanilla JavaScript (No frameworks)
- localStorage (Browser database)
- Font Awesome Icons
- Google Fonts (Playfair Display + Inter)

---

**Built with ❤️ for Natilla School Complex**
