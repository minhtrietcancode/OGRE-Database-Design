# OGRE Database Design

This repository contains the design and implementation of a database infrastructure for OGRE (Open Generative-AI Responsible Environment), a unified platform enabling ethical and cost-effective access to generative AI technologies. The project is based on ER modeling concepts and focuses on designing a relational database in MySQL to support various functionalities for platforms, sessions, users, and administrators. This project is part of Assignment 1 for INFO20003 2024 at the University of Melbourne.

## Overview
The project delivers both a conceptual model using Chen’s notation and a physical model in Crow’s foot notation, ensuring a robust database structure for managing the following key features:

1. **Platforms and Sessions**
   - Records information about GenAI platforms, including their vendors and technology partners.
   - Tracks user sessions with attributes like duration, cost, region, and usage details.
   - Supports restricted platforms that require manual application approvals for ethical compliance.

2. **Prompts and Reviews**
   - Stores user-generated prompts, their attributes (e.g., potential risks), and results.
   - Allows administrators to review prompts for compliance and ethical auditing.

3. **Users and Connections**
   - Maintains detailed user profiles, including payment methods, warnings for violations, and affiliations.
   - Tracks user connections to foster a community of responsible GenAI usage.

4. **Administrators**
   - Manages administrator assignments to platforms, their training status, and employment history.
   - Ensures neutrality by linking administrators with their declared user accounts and preventing conflicts of interest.

5. **Applications**
   - Supports an application system for restricted platforms, including manual approval and auditing by administrators.
   - Tracks application status, user quotas, and approvals linked to specific sessions.

## Documentation
For detailed description, please refer to `INFO20003 2024 A01 v1.2.pdf`.

## Applications
This database is designed to address real-world needs, including:
- Tracking resource usage and costs for generative AI platforms.
- Ensuring ethical and legal compliance in GenAI usage.
- Supporting auditing and transparency in administrative actions.

## Deliverables
- **Conceptual Model**: Hand-drawn ER diagram using Chen’s notation.
- **Physical Model**: MySQL Workbench ER model in Crow’s foot notation.

