# Backend Developer / Full Stack Java Engineer 

**Project**: BPCL Centralized Fuel Stock Management System
**Tech Stack**: Java 17, Spring Boot, Spring Security, Spring Data JPA, Thymeleaf, H2 Database (In-Memory), Maven, HTML/CSS.

### Summary
Designed and developed a scalable, role-based web application for Bharat Petroleum Corporation Limited (BPCL) to digitalize and centralize daily fuel stock reporting across multiple franchise locations. The system replaced manual tracking with an automated, secure portal for branch managers and central administrators.

### Key Contributions & Offerings:
*   **Role-Based Access Control (RBAC):** Implemented **Spring Security 7** to enforce secure, conditional UI routing. Engineered distinct operational flows for `ROLE_ADMIN` (Central Command) and `ROLE_USER` (Branch Managers).
*   **Data Aggregation & Persistence:** Architected the backend using **Spring Data JPA** to manage and query entities. Designed robust relational data models that successfully processed and aggregated daily stock metrics (Petrol, Diesel, Speed) from over 10 active branch locations in Kerala.
*   **Business Logic Validation:** Built robust REST-like Spring MVC controllers with internal validation features to ensure data integrity, such as preventing duplicate daily stock submissions by dynamically querying the database (`findByPumpNameAndDate`).
*   **Dynamic Data Templating:** Developed responsive, server-side rendered frontend views using **Thymeleaf**. Integrated dynamic model attributes to personalize the dashboard depending on the authentication principal.
*   **Rapid Prototyping & Setup:** Configured an embedded **H2 Database** combined with automatic `CommandLineRunner` bootstrapping to guarantee a zero-config, localized environment for immediate deployment and UAT testing.
*   **UI/UX Design:** Designed a modern, responsive, "Glassmorphism" interface employing Vanilla CSS and BPCL corporate branding, elevating the end-user experience for administrative staff.

### Impact:
*   Provided real-time data visibility to administrators, enabling centralized monitoring of refined petrol and high-speed diesel stocks across statewide pumping stations.
*   Streamlined the daily reporting workflow for branch managers into a secure, single-step operation.
