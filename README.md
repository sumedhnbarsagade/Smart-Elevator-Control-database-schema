# LiftGrid Smart Elevator System ERD

## Overview
This project contains a database design for a smart elevator control system used in large buildings like malls, airports, and corporate towers.

## Features
- Supports multiple buildings
- Tracks elevators and floors
- Handles ride requests and allocations
- Stores ride logs for analytics
- Tracks maintenance history
- Real-time elevator status monitoring

## Design Highlights
- Separation of static and dynamic data
- Many-to-many relationship using Elevator_Floor_Map
- Scalable and production-ready design

## Entities
Building, Floor, Shaft, Elevator,
Elevator_Floor_Map,
Ride_Request, Ride_Assignment, Ride_Log,
Elevator_Status, Maintenance_Record

## Author
Sumedh Barsagade
