# student-enrollment-system-sql/University Database Management System

A relational database implementation designed to manage university records, focusing on data integrity, complex multi-table joins, and advanced analytical reporting.

## Overview
This project establishes a robust schema for a university environment, linking departments, students, courses, and enrollments. It demonstrates the use of SQL constraints, relational mapping, and data aggregation to transform raw data into academic insights.

## Database Schema
The system consists of four primary entities:
- **DEPARTMENT**: Stores department names and locations.
- **STUDENT**: Contains student profiles linked to their respective departments.
- **COURSE**: Details academic subjects and credit hours.
- **ENROLLMENT**: A junction table tracking student-course registrations and performance (marks).

## Key Features & SQL Techniques
- **Data Integrity**: Implementation of `PRIMARY KEY`, `FOREIGN KEY`, and `CHECK` constraints (e.g., marks between 0-100).
- **Relational Joins**: Extensive use of `INNER JOIN` and `LEFT JOIN` to retrieve data across multiple tables.
- **Data Analysis**: Usage of `GROUP BY` and `HAVING` for department-wise and course-wise statistics.
- **Advanced Filtering**: Implementation of pattern matching (`LIKE`) and range filtering (`BETWEEN`).


## Sample Queries Included
- Top 3 students by average marks.
- Department-wise student distribution.
- Course-wise performance statistics (Avg, Max, Min marks).
- Enrollment status for all students (including those not yet enrolled).
