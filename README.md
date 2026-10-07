# Group-4-University-Course-Registration-
Scenario: Develop a system that manages students, academic courses and course registration. different categories of courses have different requirements or fee calculations.
Minimum Functional Requirements 
1. Register students. 2. Add courses with unique course codes. 3. Register a student for a course. 4. Prevent duplicate registration for the same course. 5. Drop a registered course. 6. Display all courses taken by a particular student. 7. Display students registered for a particular course. 8. Search for courses and students. 9. Calculate applicable course charges or workload according to course category.
 Object-Oriented Design Requirement A possible hierarchy is an abstract Course class with subclasses such as TheoryCourse, PracticalCourse and ProjectCourse. A method such as calculate_workload() or calculate_course_charge() can be overridden to demonstrate polymorphism.

Common Requirements
1. Identify the main classes from the assigned problem and clearly define the responsibility of each class.
2. Use constructors to create objects and provide suitable attributes and methods for each class.
3. Demonstrate encapsulation using appropriate public, internal/protected and private attributes. Use @property and setters where controlled access or validation is required.
4. Demonstrate meaningful object relationships such as association, aggregation, composition or dependency. Do not create relationships merely to satisfy the requirement.
5. Draw a UML class diagram before implementation. The diagram must show classes, important attributes, methods, visibility, relationships and multiplicities.
6. Create at least one meaningful inheritance hierarchy with a suitable superclass and two or more subclasses.
7. Demonstrate method overriding and polymorphism by allowing different subclass objects to respond differently to the same method call.
8. Use abstraction appropriately. At least one abstract base class must contain an abstract method that subclasses are required to implement.
9. Provide a menu that allows a user to add/register records, perform the main transactions of the system, search or display records, and view a useful summary/report.
10. Include appropriate validation and clear messages for invalid operations.
11. Use objects to collaborate with one another rather than placing the entire program logic in the menu or in one large class. 
