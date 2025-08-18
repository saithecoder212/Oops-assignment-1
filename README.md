Course Catalog Project

Overview

This project implements a simple CourseCatalog in Python that allows users to add multiple courses and search for courses by name.

Features

Add courses to the catalog.

Search for courses by name (case-insensitive).

Display search results.


Classes

Course

Represents a single course.

Attributes:

CourseCatalog

Stores multiple courses and allows searching.

Methods:

add_course(course): Add a Course object to the catalog.

search_by_name(keyword): Search courses containing the keyword in their name.



Example Usage

# Create a course catalog
catalog = CourseCatalog()

# Add courses
catalog.add_course(Course("Math"))
catalog.add_course(Course("Physics"))
catalog.add_course(Course("Computer Science"))

# Search for courses
results = catalog.search_by_name("math")
for course in results:
    print(course.name)

Requirements

Python 3.x


Author

SELVADHARSHINI 
