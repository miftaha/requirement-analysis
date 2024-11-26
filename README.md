# Requirement Analysis in Software Development

Welcome to the **Requirement Analysis in Software Development** repository!

This repository's goal is to act as a comprehensive guide and resource for understanding and implementing the requirement analysis phase in the software development lifecycle (SDLC).

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

## Why is Requirement Analysis Important?

### Importance of Requirement Analysis in the SDLC:

- **Clarity and Understanding:**
  - Helps stakeholders and development teams establish a shared understanding of the project's goals.
  - Reduces ambiguities that could lead to project delays or failures.
- **Scope Definition:**
  - Clearly defines the scope of the project, which helps in preventing scope creep.
- **Basis for Design and Development:**
  - Provides a structured roadmap for the design and development phases
- **Cost and Time Estimation:**
  - Facilitates accurate estimation of project cost, resources, and time.
- **Quality Assurance:**
  - Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

## Key Activities in Requirement Analysis

- **Requirement Gathering:** is the process of collecting information from stakeholders, customers, and end-users to identify high-level system needs and expectations using interviews, surveys, and workshops.
- **Requirement Elicitation:** is the process of Extracting detailed requirements through structured interactions with stakeholders using methods such as brainstorming, focus groups, and use case analysis.
- **Requirement Documentation:** Creating a detailed document that lists all functional and non-functional requirements, writing user stories to describe functionalities from the user’s perspective, and developing use case diagrams to show interactions between users and the system.
- **Requirement Analysis and Modeling:** Prioritizing requirements based on their importance and impact on the project, assessing the feasibility of requirements in terms of technical, financial, and time constraints, and developing models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.
- **Requirement Validation:** Reviewing the documented requirements with stakeholders to ensure accuracy and completeness, defining clear acceptance criteria for each requirement to ensure they meet the expected standards, and establishing traceability matrices to ensure all requirements are addressed during development and testing.

## Types of Requirements

In this section, we will differentiate between **Functional Requirements** and **Non-functional Requirements** for the booking management project.

### Functional Requirements

Functional Requirements define the specific behavior or functionality of the system. Describes what the system should do.

#### Functional Requirements for the Booking Management System:

1. **Hotel Management Service**
   - Hotel managers must be able to update hotel information via a dedicated portal.
   - The system must allow managers to upload images and descriptions for their hotels.
2. **Customer Service (Search + Booking)**
   - Customers must be able to search for hotels.
   - Customers must be able to book a hotel and complete payment.
3. **View Booking Service**
   - Customers and managers should be able to view all booking details (current and past).
   - Notifications must be sent to customers and managers (successful bookings or new offers).

### Non-functional Requirements

Non-functional Requirements define the quality attributes or constraints of the system. Describe how the system performs.

#### Non-functional Requirements for the Booking Management System:

1. **Performance**
   - The system must handle high traffic efficiently by distributing requests via a load balancer.
2. **Scalability**
   - The microservices architecture must ensure the system can scale horizontally to accommodate increased user traffic.
3. **Reliability**
   - The messaging queue system (e.g., Kafka or RabbitMQ) must ensure reliable communication between services.
4. **Security**
   - The system must ensure secure payment processing through integration with trusted third-party services.
   - Sensitive customer data should be encrypted both at rest and in transit.
5. **Usability**
   - The user interfaces for hotel managers and customers should be intuitive and responsive.
   - The notification system must ensure that users are promptly informed of key updates.

## Use Case Diagrams

### What Are Use Case Diagrams?

Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases).

### Benefits of Use Case Diagrams:

- Provide a clear visual representation of system functionalities.
- Help in identifying and organizing system requirements.
- Facilitate communication among stakeholders and the development team.

### Use Case Diagram for the Booking System

The following use case diagram illustrates the interactions of **Hotel Managers** and **Customers** with the booking system:
![Use Case Diagram]('/alx-booking-uc.png')
