# Car Rental Management System

## Project Overview

This project is a Python-based Car Rental Management System developed as a console application. The system allows users to manage vehicle rentals, reservations, payments, and booking records efficiently.

The project demonstrates the implementation of Python fundamentals, data structures, functions, conditional statements, loops, and date handling for real-world business processes.

---

## Business Problem

Car rental companies need a simple system to:

- Manage vehicle availability
- Handle customer reservations
- Process payments
- Track rental schedules
- Prevent double bookings

This application helps streamline rental operations and improve booking management.

---

## Features

### Vehicle Availability
- Display available vehicles
- View daily rental prices
- Check current stock

### Reservation Management
- Create new reservations
- Generate booking records
- Calculate rental duration
- Apply discounts automatically

### Reservation List
- Display all booking information
- View payment status
- Monitor rental schedules

### Edit Reservation
- Update customer information
- Change vehicle selection
- Modify rental dates

### Cancel Reservation
- Remove reservations
- Manage booking records

### Payment Processing
- Calculate total rental costs
- Apply promotional discounts
- Handle payment validation
- Update payment status

---

## Technologies Used

- Python
- Datetime
- Tabulate

---

## Data Structure

### Vehicle Inventory

```python
car_stock = {
    "Toyota Fortuner": {
        "price": 1100000,
        "stock": 6
    }
}
```

### Reservation Data

```python
{
    "booking_id": "UR001",
    "name": "Customer Name",
    "unit": "Toyota Fortuner",
    "start_date": "18-07-2025",
    "finish_date": "20-07-2025",
    "payment_status": "Paid"
}
```

---

## Main Functionalities

1. Check Vehicle Availability
2. Create Reservation
3. View Reservation List
4. Edit Reservation
5. Cancel Reservation
6. Process Payment
7. Promotion Management
8. Exit System

---

## Business Rules

- Vehicle availability is validated before booking.
- Overlapping reservations are prevented.
- Rentals of 7 days or more receive a 5% discount.
- Payment status is updated automatically after successful payment.
- Rental duration is calculated based on start and finish dates.

---

## Learning Outcomes

Through this project, I practiced:

- Python programming fundamentals
- Functions and modular programming
- Data structures (Dictionary & List)
- Date and time manipulation
- Business logic implementation
- CRUD operations
- Input validation
- Console application development

---

## Project Structure

```
car-rental-management-system/
│
├── car_rental_management.py
└── README.md
```

---

## Author

**Ulfah Rosdiana**

- Accounting Graduate
- Aspiring Data Analyst
- Python Enthusiast

LinkedIn:
www.linkedin.com/in/ulfah-rosdiana-86165a255
