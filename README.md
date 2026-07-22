# Jinja College Smart Visitor Check-In System

Welcome to the **Jinja College Smart Visitor Check-In System** - A modern, feature-rich web application for managing visitor registrations and check-ins.

## 🎓 About Jinja College

Jinja College is a premier educational institution dedicated to excellence in academic and professional training. This visitor management system streamlines the check-in process for all campus visitors.

## ✨ Features

### 👥 Visitor Check-In
- Easy-to-use registration form
- Real-time data validation
- Department tracking
- Visit reason categorization
- Contact information capture

### 📱 QR Code Management
- Generate instant QR codes for check-in
- Department-specific QR codes
- Custom QR code creation
- Download as PNG images
- Perfect for printing at entrances

### 🔔 Admin Notifications
- Real-time visitor alerts
- Email notifications (ready for integration)
- Browser pop-up notifications
- Notification dashboard
- Mark notifications as read

### ⚙️ Admin Panel
- Password-protected access
- Manage admin users
- Configure notification settings
- Export visitor data to CSV
- Auto-save settings

### 📊 Visitor Dashboard
- View all check-in records
- Real-time visitor list
- Complete visitor information
- Check-in timestamps

## 🚀 Quick Start

### Access the System

**Live URL:** [https://joshemmie71-web.github.io/josh/visitor-checkin.html](https://joshemmie71-web.github.io/josh/visitor-checkin.html)

### Admin Access

1. Click on **⚙️ Admin Panel** tab
2. Enter password: `jinja@2024`
3. Add admin emails to receive notifications
4. Configure notification settings

### For Visitors

1. **Scan QR Code** or visit the link above
2. Fill in your information
3. Select your department and reason for visit
4. Submit check-in
5. Done! 🎉

## 📋 How It Works

### For Visitors:
```
Scan QR Code → Fill Form → Submit → Instant Confirmation
```

### For Admins:
```
Visit Admin Panel → Add Email → Enable Notifications → Receive Alerts
```

## 🔐 Admin Login

**Default Password:** `jinja@2024`

⚠️ **Important:** Change this password immediately for security!

To change the password:
1. Open `visitor-checkin.html` in a text editor
2. Find: `const ADMIN_PASSWORD = "jinja@2024";`
3. Replace with your secure password

## 📧 Email Notifications Setup

To enable email notifications, you'll need to integrate with an email service:

### Option 1: EmailJS (Easiest)
```javascript
// Sign up at emailjs.com
// Add your service configuration
```

### Option 2: Backend API
Send notifications through your own server

### Option 3: Third-party Services
- Formspree
- SendGrid
- Mailgun

## 📊 Data Storage

All data is stored locally in your browser:
- **Visitors:** `jinjaCollegeVisitors`
- **Admins:** `jinjaCollegeAdmins`
- **Notifications:** `jinjaCollegeNotifications`
- **Settings:** `jinjaCollegeSettings`

## 💾 Export Data

1. Go to **⚙️ Admin Panel**
2. Click **📥 Export Visitor Data**
3. CSV file downloads automatically
4. Open in Excel or Google Sheets

## 🎨 Customization

### Colors
- Primary Color: `#667eea` (Purple)
- Secondary Color: `#764ba2` (Dark Purple)
- Text: `#333333`

### Branding
You can customize:
- Institution name
- Logo
- Colors
- Department list
- Notification settings

## 🔒 Security Features

✅ Password-protected admin panel  
✅ Form validation  
✅ Email format verification  
✅ Secure data storage  
✅ Browser-based (no server exposure)  

## 📱 Responsive Design

Works perfectly on:
- 🖥️ Desktop computers
- 💻 Tablets
- 📱 Mobile phones

## 🐛 Troubleshooting

### QR Codes not showing?
- Wait a few seconds for generation
- Refresh the page
- Check browser console for errors

### Notifications not appearing?
- Ensure admin emails are added
- Check notification settings are enabled
- Verify browser allows notifications

### Data not saving?
- Check browser's storage space
- Ensure cookies are enabled
- Try clearing browser cache

## 📞 Support

For issues or feature requests, please contact:
- **Email:** support@jinjacollege.edu
- **Phone:** +256 XXX XXX XXX

## 🔄 Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **QR Codes:** QRCode.js library
- **Storage:** Browser LocalStorage
- **Icons:** Unicode & Emoji

## 📜 License

© 2024 Jinja College. All rights reserved.

## 🎯 Roadmap

Upcoming features:
- [ ] Email service integration
- [ ] SMS notifications
- [ ] Mobile app
- [ ] Database backend
- [ ] Multi-language support
- [ ] Advanced analytics
- [ ] Visitor photos
- [ ] ID scanning

## 📝 System Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- LocalStorage enabled
- Internet connection

## 🌐 Access Points

- **Main URL:** https://joshemmie71-web.github.io/josh/visitor-checkin.html
- **GitHub:** https://github.com/joshemmie71-web/josh
- **Repository:** joshemmie71-web/josh

---

**Last Updated:** July 22, 2024  
**Version:** 2.0  
**Status:** ✅ Active & Fully Functional

Made with ❤️ for Jinja College
