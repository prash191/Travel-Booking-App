# Travel-Booking-App
Travel booking app created in Node.js, Express, React, TypeScript, MongoDB.

# natours-extended

A web application for tour booking with additional features and technical advancements.

## Features

- RESTful API supporting CRUD operations for tours, users, reviews, and bookings.
- Secure user authentication and authorization based on JWT.
- Advanced error handling with custom error classes and environment-specific handling.
- Server-side rendering for improved performance and SEO.
- Input validation and sanitization across all endpoints.
- Rate limiting and security middleware including Helmet and CORS.
- Pagination, filtering, and sorting capabilities on resources.

## Technical Aspects

- **Backend:** Node.js and Express.js with a modular MVC architecture.
- **Database:** MongoDB with Mongoose ODM for schema definition and validation.
- **Authentication:** JWT for stateless authentication with route protection middleware.
- **Error Handling:** Custom error classes (`AppError`) centralized error controller.
- **Project Structure:**
  - `/controllers` - Handles request logic.
  - `/models` - Mongoose schemas.
  - `/routes` - API routes organized by resource.
  - `/utils` - Helper utilities and services.
  - `/public` - Static assets for server-rendered pages.
- **Security:** Strong password hashing, HTTP security headers, CORS, rate limiting, and input sanitization.
- **Configuration:** Environment variables managed using dotenv for secrets and environment-specific settings.
- **API Endpoints:**
  - `/api/v1/tours` - Tour management endpoints.
  - `/api/v1/users` - User registration and profile management.
  - `/api/v1/reviews` - Review submission and retrieval.
  - `/api/v1/bookings` - Tour booking operations.

The project is built with best practices for scalability, security, and maintainability in the Node.js and MongoDB ecosystem.

