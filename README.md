# Employee Records Management System (ERMS)

A comprehensive system for managing employee records, attendance, performance, and HR operations.

## Features

- **Employee Profile Management**: Personal details, employment history, emergency contacts
- **Document Management**: Upload contracts, IDs, certifications with expiry alerts
- **Attendance & Leave Tracking**: Daily logs, leave requests, vacation balances
- **Performance Management**: Reviews, goal tracking, feedback
- **Training & Development**: Training history, skill tracking
- **User Roles & Access Control**: Role-based permissions (HR, Manager, Employee)
- **Compliance**: Audit trails, policy acknowledgments
- **Reporting & Analytics**: Custom reports, HR dashboards

## Tech Stack

### Frontend
- React.js 18
- TypeScript
- Material-UI (MUI)
- React Router
- Axios for API calls
- React Query for state management

### Backend
- Java 17
- Spring Boot 3.x
- Spring Security
- Spring Data JPA
- MySQL Database
- JWT Authentication

## Project Structure

```
Finalopt/
├── frontend/          # React.js application
├── backend/           # Spring Boot application
├── database/          # Database scripts
└── docs/             # Documentation
```

## Getting Started

### Prerequisites
- Node.js 18+
- Java 17+
- MySQL 8.0+
- Maven 3.6+

### Installation

1. **Clone the repository**
2. **Backend Setup**
   ```bash
   cd backend
   mvn clean install
   mvn spring-boot:run
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Database Setup**
   - Create MySQL database: `erms_db`
   - Run scripts in `database/` folder

## API Documentation

The backend API will be available at `http://localhost:8080`
The frontend will run at `http://localhost:3000`

## Default Users

- **HR Admin**: admin@company.com / admin123
- **Manager**: manager@company.com / manager123
- **Employee**: employee@company.com / employee123 