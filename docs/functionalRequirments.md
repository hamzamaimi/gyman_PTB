🏋️‍♂️ Gyman PTB – Functional Requirements
📘 Overview
Gyman PTB is a web application designed to manage personal trainer bookings. It facilitates seamless interaction between gym administrators and members, enabling efficient scheduling and management of training sessions.

👥 User Roles
Admin
Responsible for managing member accounts, calendar availability, and booking approvals.

Member
Can request bookings for available personal training sessions.

✅ Functional Requirements
1. 🔐 Member Account Management
The system must allow the admin to create member accounts.

Members should be able to do the first log-in by using the credentials provided by the admin.

2. 📅 Calendar Management
The admin can define availability by adding personal training slots to a shared calendar.

These available slots must be visible to members when booking.

3. 📝 Booking System
A member can request a booking based on the visible time slots.

All new bookings remain in a "pending" state until reviewed by the admin.

4. 📩 Booking Approval & Notification
The admin can approve or reject any pending booking.

Once approved:

The member receives a confirmation notification via email or SMS (based on user preference or availability).

5. 🔄 Booking Management
The admin can reschedule an existing reservation by:

Bringing it forward, or

Postponing it to a later time.

Members must be notified of any rescheduling or changes made.