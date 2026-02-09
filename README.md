# EventGO Frontend

Modern, responsive web application for the EventGO event management platform, built with React and Vite.


## Overview

EventGO Frontend is a single-page application (SPA) that provides an intuitive interface for browsing events, purchasing tickets, and managing event attendance. It features separate dashboards for regular users and event organizers.

### Key Capabilities

- **Event Discovery**: Browse, search, and filter events
- **Ticket Purchase**: Secure ticket purchasing with multiple payment methods
- **User Dashboard**: Manage tickets, view transaction history
- **Organizer Dashboard**: Create and manage events, view analytics
- **Waitlist Management**: Join waitlists for sold-out events
- **Responsive Design**: Mobile-first, works on all devices

---

## Features

### For Users
- Browse upcoming and past events
- Advanced search and filtering
- Purchase tickets with instant confirmation
- Join waitlists for sold-out events
- Request ticket refunds
- View purchase history
- Manage profile settings

### For Organizers
- Create and edit events
- Define multiple ticket types
- View real-time sales analytics
- Monitor ticket sales and revenue
- Manage attendee refunds
- Export event reports

### General
- JWT-based authentication with automatic token refresh
- Responsive mobile-first design
- Toast notifications for user feedback
- Loading states and error handling
- Protected routes based on user roles

---

## Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite
- **Routing**: React Router DOM v6
- **HTTP Client**: Axios
- **Styling**: CSS3 with CSS Modules
- **Icons**: React Icons
- **Notifications**: React Toastify
- **Date Handling**: date-fns / native JS Date
- **Charts**: Recharts (for analytics)


---

## Related Projects

- **Backend**: [EventGO-backend](https://github.com/mpokorn/EventGo-backend) (local: `../EventGO-backend/`)
- **Mobile App**: [EventGO-mobile-app](https://github.com/mpokorn/EventGo-mobile-app) (local: `../EventGO-mobile-app/`)

---
