# Movie Ticket Booking Management Application

## 📌 Project Overview

The **Movie Ticket Booking Management Application** is a case-management application developed using the **Pega Platform**.

The application is designed for CineWave Entertainment to manage movie ticket booking requests across theatres and locations. It provides a structured workflow for handling booking requests, checking show and seating availability, calculating booking costs, obtaining approval, processing bookings, and notifying customers.

## 🎯 Project Objectives

The main objectives of this project are:

- Design a case lifecycle for movie ticket booking.
- Allow customers to submit movie ticket booking requests.
- Enable staff to manage movie and show information.
- Check seating and show availability.
- Calculate the booking cost.
- Capture customer confirmation before final booking.
- Process and track booking requests.
- Provide approval and rejection handling.
- Notify customers about booking confirmation.
- Configure business logic and automation using Pega.

## 🛠️ Technology Used

- **Pega Platform**
- **Pega App Studio**
- **Pega Blueprint Portal**
- **Pega Infinity**
- Case Management
- Data Modeling
- Business Process Automation

## 🔄 Case Lifecycle

The application follows a structured case lifecycle:

### 1. Submit Movie Ticket Request

Customers provide the required movie booking details and submit a ticket request.

### 2. Check Availability

The system manages ticket inventory and checks seat availability for the selected show.

### 3. Approval

The booking request goes through an approval process before final processing.

### 4. Booking Execution

The approved booking is processed and customer-related activities are handled.

## 📋 User Stories

The project contains the following user stories:

- **US-001:** Submit Movie Ticket Request
- **US-002:** Check Show Availability
- **US-003:** Calculate Booking Cost
- **US-004:** Confirm Booking Request
- **US-005:** Maintain Movie and Show Data
- **US-006:** Review Booking Details
- **US-007:** Process Ticket Booking
- **US-008:** Notify Booking Confirmation
- **US-009:** Define Booking SLA
- **US-010:** Route Booking Request by Show Type

## 📊 Data Model

The Movie Ticket Request case contains data fields required for managing the booking process, including:

- Movie
- Show
- Customer
- Attendee
- Confirmation Number
- Event Name
- Ticket Price
- Ticket Quantity
- Number of Tickets
- Payment Method
- Booking Cost
- Booking Confirmation Status
- Booking Risk Score
- Booking SLA Breach
- Seating Availability Status
- Show Type
- Venue Capacity
- Discount Code
- Routing Status
- Customer Notification Timestamp
- Notes
- Description

## ⚙️ Business Process

The application manages the booking process through multiple stages:

```text
Customer Request
       ↓
Submit Movie Ticket Request
       ↓
Check Show Availability
       ↓
Calculate Booking Cost
       ↓
Confirm Booking Request
       ↓
Approval
       ↓
Booking Execution
       ↓
Booking Confirmation
       ↓
Customer Notification
