# Haroon Ibn Rasheed Online Quran Academy — Multi-Panel HTML Starter

This project is a separate-HTML-page frontend starter based on the supplied Teacher dashboard and Schedule screenshots.

## Roles
- Admin: controls teachers, students, courses, master schedule, leave applications and salary details.
- Teacher: sees students, schedule, course material, leaves, salary and group classes.
- Student: logs in separately and sees their own dashboard, schedule, courses, leave and profile.

## Demo login
Admin: admin@haroonquranacademy.com / admin123
Teacher: teacher@haroonquranacademy.com / teacher123
Student: student@haroonquranacademy.com / student123

## Important production note
This version is a static GitHub-ready frontend. The demo login uses browser localStorage and is NOT secure authentication.
For real academy use, connect the same pages to a backend such as Supabase or Firebase:
- secure authentication
- role-based access control
- teachers/students/courses database
- schedule database
- leave approvals
- salary calculation
- file/course material storage
- admin-only permissions

Do not put real passwords or secret keys into HTML/JavaScript.

## Folder structure
- index.html
- admin-*.html
- teacher-*.html
- student-*.html
- assets/style.css
- assets/app.js

All major pages are separate HTML files so individual pages can be edited later without opening one huge HTML file.
