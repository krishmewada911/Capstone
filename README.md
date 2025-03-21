# Hands By Hands Service Website

## Overview
Hands By Hands is a service website designed to instantly connect consumers with local service providers for tutoring, house repairs, cleaning, and more. The platform enables users to search for, reserve, and evaluate services while allowing providers to manage bookings, showcase their skills, and grow their business. This project aims to enhance user convenience, promote local service economies, and ensure secure, reliable transactions.

## Business Purpose
The project exists to simplify the process of locating trustworthy service providers. By bringing consumers and providers together on a single platform, Hands By Hands will support local businesses, improve customer satisfaction, and contribute to community economic growth.

## Features
- **User Registration & Login:** Secure sign-up and login functionality.
- **Service Filtering & Search:** Easily search services by ratings, location, and category.
- **Booking System:** Make reservations with real-time booking confirmations.
- **Review & Rating System:** Rate and review service providers.
- **Dashboard for Providers:** Manage profiles, bookings, and availability.
- **Payment Integration:** Secure payment processing using Stripe and PayPal.
- **Admin Panel:** Manage users, services, and disputes.

## Technical Architecture
- **Frontend:** WordPress and CSS for a responsive and dynamic interface.
- **Backend:** Node.js with Express.js for server-side logic and API development.
- **Database:** MySQL for storing user data, service details, and reviews.
- **Payment Gateway:** Stripe and PayPal for secure payment processing.
- **Version Control:** Git and GitHub for collaborative development and version management.

## System Objectives
- **Scalability:** Handle up to 10,000 concurrent users.
- **Security:** Encrypt all user data and ensure GDPR compliance.
- **Response Time:** Maintain a sub-2-second response time for critical transactions.
- **Availability:** Achieve 99.9% uptime.
- **Integration:** Seamlessly integrate with third-party payment gateways and mapping services.

## Getting Started

### Prerequisites
- **Node.js:** Version 14.x or higher.
- **MySQL:** Installed and running.
- **Git:** For version control.

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/hands-by-hands.git
    cd hands-by-hands
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Database Setup:**
    - Create a MySQL database.
    - Import the provided schema located in `/database/schema.sql`.

4. **Environment Variables:**
    - Create a `.env` file in the root directory.
    - Add the following variables:
      ```env
      PORT=3000
      DB_HOST=localhost
      DB_USER=your_username
      DB_PASS=your_password
      DB_NAME=your_database_name
      STRIPE_API_KEY=your_stripe_key
      PAYPAL_CLIENT_ID=your_paypal_client_id
      PAYPAL_CLIENT_SECRET=your_paypal_client_secret
      ```

### Running the Project

1. **Start the Server:**
    ```bash
    npm start
    ```

2. **Access the Website:**
    - Open your browser and navigate to `http://localhost:3000`.

### Testing
- Run tests using:
    ```bash
    npm test
    ```

## Team Members & Roles
- **Fatema Alkhateeb:** Website design, UI/UX, and usability testing.
- **Abdulazeem Ajibola:** Lead Developer responsible for coding, technical architecture, and feature integration.
- **Krish Mewada:** Project Planner managing timelines, use cases, and client documentation.

## License
This project is licensed under the MIT [LICENSE](./LICENSE).
