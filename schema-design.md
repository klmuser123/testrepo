echo "# Database Schema Design

This document outlines the schema design for the Smart Clinic Management System.

## Tables

- **Patients**: Stores patient details
- **Doctors**: Stores doctor profiles and specialties
- **Appointments**: Links patients and doctors with time slots
- **Prescriptions**: Records medication issued per appointment
- **Users**: Authentication and role-based access
- **Tokens**: Session and security tokens

## Relationships

- One doctor can have many appointments
- One patient can have many appointments
- Each appointment can have one prescription

## ER Diagram

_(Insert diagram or link here)_

## Notes

- All tables use `id` as primary key
- Foreign keys are indexed for performance
- Timestamps are stored in UTC

" > schema-design.md
