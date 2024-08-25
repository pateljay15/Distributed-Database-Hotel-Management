# Distributed Database for the Hospitality Industry

This README outlines a project developed for the CSCI 5408 Data Management course, focused on creating a distributed database system designed specifically for the hospitality industry. The project utilizes Java and is hosted on Google Cloud Platform's Cloud SQL service.

## Overview

The hospitality industry's diverse and complex data requirements make it an ideal candidate for implementing distributed database systems. This project covers the entire lifecycle from initial design to deployment, specifically crafted to cater to the varied data management needs of hospitality services including hotels, resorts, and theme parks.

## Key Features

### Entity-Relationship Diagram (ERD)

- **Initial and Final ERDs:** The project provides comprehensive visualizations of the data structure, showcasing initial and final ERDs that reflect the intricate relationships within the hospitality domain.

### Fragmentation Logic

- **Specialized Database Instances:** The database is divided into two specific fragments, each tailored to handle distinct aspects of hotel operations and business management, optimizing performance and efficiency.

### Global Data Catalog (GDC)

- **Metadata Management:** A central GDC is implemented to manage metadata, ensuring efficient data retrieval and system integrity across the distributed database.

### Java Code Implementation

- **Backend Operations:** Java is used to facilitate backend operations, including database interaction and query handling, ensuring robust data management and operational continuity.

## Design Issues

- **Fan Traps and Time Variant Design Issues:** Initial ERD design challenges such as fan traps and changing attributes over time were meticulously addressed, with schema revisions to ensure data integrity and clarity.

## Normalization

- **Ensuring Data Integrity:** The database schema is carefully normalized to avoid partial and transitive dependencies, adhering to 2NF and 3NF principles. This ensures that all data anomalies are avoided and that the system maintains a clear, manageable structure.

## System Architecture

- **Database Fragmentation:** The database is strategically divided into two fragments. Each fragment is hosted on a separate Google Cloud Platform (GCP) Cloud SQL instance. The Global Data Catalog (GDC), which contains essential metadata, is located in one of these instances to facilitate data management and retrieval.
![Distributed Database Architecture](https://github.com/pateljay15/Distributed-Database-Hotel-Management/blob/main/Distributed%20Database.drawio.png)

## Conclusion

The Distributed Database for the Hospitality Industry project showcases an effective implementation of a distributed database system, demonstrating how such systems can significantly enhance data accessibility and performance in real-world industry applications.
