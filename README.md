# Restaurant Management System (RMS)

A restaurant management system for taking orders, sending tickets to the kitchen and bar,
billing, and viewing daily sales. It is modelled on how a real restaurant works.

Second-year project (SYP) – Sanskar Shrestha, Itahari International College (London Met), 2026/27.

## Features (planned)

- **Public pages:** restaurant home page and a read-only menu opened by a QR code
- **Staff:** tables screen, personal 4-digit codes, take and edit orders, move tables
- **Kitchen & Bar screens:** KOT (food) and BOT (drinks) tickets that refresh automatically
- **Cashier:** billing with discount limit and VAT, payment methods
  (Cash, Card, Fonepay, eSewa, Khalti), cancellation approvals, daily collection
- **Owner:** menu, staff, tables and profile management, today's dashboard, order history and change log

## Tech stack

| Part      | Technology                              |
|-----------|-----------------------------------------|
| Backend   | Python, Django, Django REST Framework   |
| Frontend  | React (Vite), Tailwind CSS              |
| Database  | PostgreSQL                              |

## Project structure

```
restaurant_management_system/
├── backend/    # Django project 
└── frontend/   # React app 
```

## Setup

The full setup guide will be added on end.
Secrets such as the database password and `SECRET_KEY` go in a `.env` file, which is never committed.

## Status

🚧 In development
