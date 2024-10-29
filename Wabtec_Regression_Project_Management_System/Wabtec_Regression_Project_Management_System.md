# Regression Project Entity Management System
*Internship Project at Wabtec*

## Overview
During my internship at Wabtec, I developed a Regression Project Entity Management System designed to streamline the organization and tracking of regression testing projects. This system provided project managers and ITT personnel with an accessible way to manage project data, link projects to key operational files, and handle modifications efficiently.

## Objective and Purpose
The system was designed to:
- Provide project visibility for CaSE Project Managers and ITT teams, enabling easy tracking of both current and archived regression projects
- Enable seamless creation, modification, and association of projects with operational plans and locomotive configurations
- Deliver a user-friendly experience aligned with Wabtec Volt design standards for intuitive navigation

## Key Features & Use Cases

### Project Listing and Filtering
- Implemented comprehensive list views of active and completed regression projects with status-based filtering
- Developed toggle functionality between current and archived projects for effective lifecycle management

### Efficient Project Creation and Editing
- Built functionality for creating new regression projects with comprehensive data entry fields
- Implemented project modification capabilities with direct updates to the PostgreSQL database
- Created auto-population features for enhanced user efficiency

### Linking to Operational Plans and Configurations
- Developed system for associating projects with operational plans and locomotive configurations
- Implemented configuration management through Excel uploads and list selection
- Added functionality to designate configurations as Preliminary or Actual

### Calendar View
- Created calendar interface for timeline visualization of projects
- Implemented project emphasis capabilities directly from calendar view

### Role-Based Permissions
- Integrated Okta login system for secure, user-specific access
- Implemented permissions-based data entry fields based on user roles

### Action Buttons and Core Functionalities
- Developed core features including project creation, cloning, and viewing
- Implemented calendar view integration for timeline management

## Technical Stack
- **Frontend**: React with Wabtec Volt design standards
- **Backend**: Flask for API handling
- **Middleware**: C# and Python Docker services
- **Database**: PostgreSQL
- **Authentication**: Okta

## Development Tools
- **IDEs**: Visual Studio Code
- **Container Platform**: Docker
- **Package Management**: NPM
- **Version Control Process: Leveraged Git for version control, utilizing branching strategies and commit best practices to ensure project updates were tracked effectively and collaboratively.**


## Key Development Areas and Challenges

### Database Schema Definition
- Implemented Schema 2 – ProjectDefinition in PostgreSQL for regression project details
- Created "Hours" table structure for project time tracking

### Data Retrieval and Display
- Developed efficient functions for project detail presentation
- Optimized data retrieval through pgAdmin debugging

### C# Testing Integration
- Implemented comprehensive unit and integration tests
- Validated core functionalities including saving, editing, and cloning projects

### UI Design with User-Centric Enhancements
- Created intuitive interface with dropdowns, search fields, and filters
- Developed efficient configuration selection through popup screens

## Outcome
The Regression Project Entity Management System successfully streamlined project management processes at Wabtec. Through robust C# testing and validation, the system provided project managers and ITT teams with enhanced visibility and organization of regression projects. The implementation of user-friendly interfaces and secure access controls ensured efficient project data management while maintaining system integrity.

The system effectively met its core objectives, providing Wabtec with a reliable platform for managing regression testing projects, demonstrating the successful application of modern development practices in an enterprise environment.
