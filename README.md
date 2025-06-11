# Hospital Management System

## Overview

This Hospital Management System is a relational database project designed to manage core hospital operations such as patient records, staff details, admissions, appointments, medical records, and room assignments. It is built using SQL and adheres to standard database normalization practices.

## Features

- Patient registration and record management
- Staff and department organization
- Medical history tracking
- Appointment scheduling
- In-patient admission and discharge handling
- Room availability and assignment system

## Entities and Relationships

- **Patient**: Contains personal information about patients.
- **Staff**: Includes hospital employees like doctors, nurses, and administrative staff.
- **Department**: Defines various hospital departments.
- **Medical Record**: Logs diagnosis and treatment history.
- **Admission**: Records patient stays and room assignments.
- **Appointment**: Schedules patient visits with doctors.
- **Room**: Tracks room details and availability.

### Key Relationships

- One patient can have many medical records, appointments, and admissions.
- Staff are assigned to one department.
- Admissions link patients to rooms.
- Appointments associate patients with staff (typically doctors).

## Technologies Used

- **Database**: MySQL / PostgreSQL / SQL Server *(choose based on your implementation)*
- **Design Tools**: Draw.io / Lucidchart (for ERD)
- **SQL Language**: DDL & DML queries

## Constraints and Integrity

- Primary and foreign keys enforce data integrity
- Unique constraints on fields like room number and department name
- Check constraints on gender, room type, etc.
- Normalized up to 3NF to reduce redundancy

## Getting Started

1. Clone or download this repository.
2. Set up your SQL environment.
3. Run the provided SQL schema to create tables.
4. Use sample queries or UI (if applicable) to test functionalities.

## Future Enhancements

- Web-based user interface
- Role-based authentication (admin, doctor, receptionist)
- Billing and pharmacy modules
