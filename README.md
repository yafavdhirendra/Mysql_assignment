# MySQL Club Management System

This project demonstrates database normalization (1NF, 2NF, 3NF)
using MySQL 8.0 in Docker And also learn about basic of mysql

Tables:
- Student
- Club
- Membership

Includes JOIN operations and ER Diagram.

# Entities
**1. Student**

- StudentID (Primary Key)

- StudentName

- Email

- Department

**2. Club**

- ClubID (Primary Key)

- ClubName

- ClubRoom

- ClubMentor

**3. Membership**

- MembershipID (Primary Key)

- StudentID (Foreign Key)

- ClubID (Foreign Key)

- JoinDate

**Relationship Explanation**

- One student can join many clubs.

- One club can have many students.

- This creates a many-to-many relationship.

- The Membership table acts as a bridge entity.

**Relationship Structure:**

Student (1) —— (M) Membership (M) —— (1) Club

- Primary Keys

- StudentID

- ClubID

- MembershipID

** Foreign Keys**

- StudentID references Student(StudentID)

- ClubID references Club(ClubID)

# Author
- **Dhirendra Yadav** - 1st year Student
- Softwarica College og IT and E-Commerce Kathmandu (**NEPAL**)
