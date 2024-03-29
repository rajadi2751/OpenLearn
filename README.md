# Project: OpenLearn

## Introduction

### 1.1 Purpose

In the current landscape, educational platforms often impose substantial fees on educators, ranging from 15% to 20%, affecting their profits. This dilemma forces educators to either accept reduced earnings or inflate course prices. Our goal is to develop a fee-free teaching platform where educators can teach without incurring any platform fees. This initiative aims to make education more accessible by allowing educators to offer courses at lower costs.

### 1.2 Objective

#### 1.2.1 Eliminating Platform Fee
The primary objective is to create a platform where educators can offer courses without deductions, allowing them to retain their entire earnings.

#### 1.2.2 Affordable Education
By removing platform fees, the platform aims to provide affordable education, making high-quality courses accessible without inflated pricing.

#### 1.2.3 Flexibility for Educators
The platform intends to give educators the flexibility to set fair prices based on their expertise and the value they bring to students.

### 1.3 Scope

The project's initial scope focuses on developing a website, serving as the primary platform for this initiative.

#### 1.3.1 Front-End Technologies

1. Angular CLI: Essential for creating, building, and managing Angular projects.
2. Angular Material: UI components following Google's Material Design.
3. NgRx: State management for growing applications.
4. Angular Router: Navigation between components and views.
5. RxJS: Library for handling asynchronous operations and events.

#### 1.3.2 Database

1. YouTube: For storing videos by uploading them on YouTube in unlisted mode.
2. MongoDB: For additional database needs.

#### 1.3.3 Back-End Technologies

1. Express: Core framework for building the backend.
2. Mongoose: Node.js library for MongoDB interaction.
3. Passport.js: Flexible and modular authentication middleware.
4. yt-dl-core: Library for fetching videos from YouTube.
5. Helmet: Security-focused middleware for Express.
6. Express-validator: For validating and sanitizing data.
7. Cors: Handling Cross-Origin Resource Sharing.

#### 1.3.4 Payment Method

Choose one of the following or explore other options:

- **Stripe:** Widely used payment processing platform with strong security features.
- **PayPal:** Popular online payment system with wide user adoption.
- **Braintree:** Owned by PayPal, supports various payment methods with advanced fraud protection.
- **Square:** Payment processor catering to small and medium-sized businesses.

#### 1.3.5 Optional Module

- **Multer:** Middleware for handling multipart/form-data; optional for future use cases.

## Non-Functional Requirements

### 5.1 Security

Security measures include robust authentication, encryption for data transmission, secure storage practices, compliance with privacy regulations, and protection against potential vulnerabilities.

### 5.2 Performance

Optimizing page loading times, minimizing latency, ensuring responsiveness across devices, and efficient server resource management for a seamless user experience.

### 5.3 Scalability

Designing the platform to handle a growing user base, courses, and interactions. This includes scalable server infrastructure, database management, and load balancing mechanisms.

### 5.5 Reliability

Ensuring consistent service delivery without unexpected downtime or disruptions. This involves implementing redundant systems, failover mechanisms, and regular maintenance practices to minimize service interruptions. Reliability extends to data integrity, ensuring accurate and accessible user data and course information.