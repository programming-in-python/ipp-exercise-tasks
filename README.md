# Intro to Programming in Python - Lab Module Tasks

## Overview

This project captures the Lab Module exercises and associated requirements for my Introduction to Python course at Northeastern University. Lab Modules are designed to be implemented sequentially - in order - from Lab Module 01 to Lab Module 12. Some of the content is derived from the Python examples in my O'Reilly Media book, [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401), which may be a useful reference for those taking this course.

All Lab Module exercises can be found here (NOTE: The tasks contained in this repository are 'issues' which are ordered within the Kanban Board listed below):

- [Intro to Programming in Python Kanban Board](https://github.com/orgs/programming-in-python/projects/1)

### Project Objectives

This repository captures the Lab Module task descriptions to be used in my Intro to Python Programming course. There are three primary objectives of this project:

(1) Provide an orderly walk through of the Python programming language (Python 3, specifically) with hands-on development exercises someone new to the language can work through, implement, test, and use in their own projects.

(2) Cover the relevant aspects of software design, component organization, and DevOps to assist the user with designing their own applications and capabilities in the future.

(3) Provide a Python-based technology platform for my Northeastern University College of Engineering graduate students (and me) to use for experimentation.

### Helpful Links

IPP Kanban Board: [Intro to Programming in Python Requirements](https://github.com/orgs/programming-in-python/projects/1)

Please see the following links for some helpful information about the IPP exercises and other associated repositories. Please note that many of the exercises and sample source code in this repository is based on some of the patterns and exercises from my book, [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).
 - Intro to Programming in Python (IPP) specific:
   - [Intro to Programming in Python - Lab Module Exercise Tasks (aka the IPP Kanban Board)](https://github.com/orgs/programming-in-python/projects/1)
   - [Intro to Programming in Python - Lab Module Exercise Components](https://github.com/programming-in-python/ipp-exercise-components/)
 - Other reading links:
   - [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/)

## Usage

- Step 1: Review the [Kanban Board](https://github.com/orgs/programming-in-python/projects/1) - this contains all exercise tasks within an ordered board
  - Available here: [Intro to Programming in Python Kanban Board](https://github.com/orgs/programming-in-python/projects/1)
    - There are dozens of exercises listed, and while many can stand alone, the intent is for the reader to work through each exercise in order. This approach will ensure later exercises are understandable for the reader, as some concepts covered in earlier lab modules will be necessary to execute later lab modules successfully.

- Step 2: Review the primary code repository:
  - PEC - [Intro to Programming in Python - Python Exercise Source Components](https://github.com/programming-in-python/ipp-exercise-components/)
    - This repository contains the Python-based templates and configuration information needed for those taking my Introduction to Python Programming course.

- Step 3: Clone the repository and start Programming in Python:
  - Implement each lab module described in the [Intro to Programming in Python Kanban Board](https://github.com/orgs/programming-in-python/projects/1)
    - Run the tests described in each module to verify functionality works as expected
  - Have fun building!

## Organization

The requirements contained within this repository are captured as a simple list of dozens of tasks and activities - some are documentation-specific while most are programming-specific - and labeled according to activity category, chapter, and implementation order.

### Lab Modules, Milestones and Labels Navigation

Lab Modules are organized into 'parts', which are intended to represent categories of exercises that are related, yet are also designed to be implemented in sequence, as each part is intended to be implemented in sequence (e.g., Part 01 first, with each lab module implemented in order, followed by Part 02, etc.) Lab module details are currently under development and will be linked here when available.

While subject to change, the course syllabus will generally align to the following schedule (assuming a 16-week semester): 
  - [Part 01: Foundations](https://github.com/programming-in-python/ipp-exercise-tasks/issues/4)
    - Introducing Computer Programming and the Python Language
    - Python Syntax (primitive types, variables, operators, string formatting)
    - Functions and Control Flow (application state, declarations, parameters, loops, exceptions)
    - Review and Quiz No. 1 (for those taking my course)
  - [Part 02: Data Structures, Classes, and Concurrency](https://github.com/programming-in-python/ipp-exercise-tasks/issues/5)
    - Data Types (non-primitive types - array, list, set, dict, tuple)
    - Objects and Classes (modules, classes, inheritence, encapsulation, polymorphism)
    - Concurrency (multi-threading, asyncio)
    - Review and Quiz No. 2 (for those taking my course)
  - [Part 03: Data Handling and Presentation](https://github.com/programming-in-python/ipp-exercise-tasks/issues/6)
    - I/O (file, network, DB)
    - Data Processing (Numpy, Pandas)
    - Data Visualization (Matplotlib)
    - Review and Quiz No. 3 (for those taking my course)
  - [Part 04: Problem Solving with Python](https://github.com/programming-in-python/ipp-exercise-tasks/issues/7)
    - Use Cases (sample problems to solve using Python)
    - Project Work #1 (lab week)
    - Project Work #2 (lab week: NOTE that this is only if 16 weeks of class meeting time are available for the semester)
    - Project Presentations

Each exercise within a given Lab Module is labeled using one or more of the following categories:
  - [build](https://github.com/programming-in-python/ipp-exercise-tasks/labels/additional): Build and / or DevOps related task (e.g., checkout a new branch).
  - [configuration](https://github.com/programming-in-python/ipp-exercise-tasks/labels/configuration): Configuration related task (e.g., install some software).
  - [documentation](https://github.com/programming-in-python/ipp-exercise-tasks/labels/documentation): Documentation related task (e.g., write-up your approach).
  - [exercise](https://github.com/programming-in-python/ipp-exercise-tasks/labels/exercise): Required exercise related task (i.e., you should implement this).
  - [additional](https://github.com/programming-in-python/ipp-exercise-tasks/labels/additional): Optional (additional) exercise task (i.e., if you're a student in my class, you should implement this, although it is currently optional).
  - [integration](https://github.com/programming-in-python/ipp-exercise-tasks/labels/integration): Test and integration related task (e.g., test connection between apps).
  
### About Naming and Numbering Conventions

Exercises and notes are named according to the following convention:

*{project name}-{category}-{lab module #}-{sequence #}*

This naming convention is designed to help you navigate through the requirements in each Lab Module sequentially, building your solution in a step-by-step manner. The naming breakdown is as follows:
  - project name:
    - ipp: The project name (Programming the in Python).
  - category:
    - DOC: General documentation that provides a summary overview of the section or lab module.
    - INF: An informational note.
    - STU: A student-specific requirement, usually documentation-related (this is relevant if enrolled in the Connected Devices course, for example).
    - CFG: A configuration requirement.
    - PEC: An Python Exercise Component-specific requirement. These are the Python-specific exercises that are part of each lab module.
    - INT: An integration requirement that may depend upon other requirements specific to those labeled as CFG, EDA and / or DTA.
  - lab module #:
    - 01 - 10: Depicts the order of implementation for the various lab modules.
  - sequence #:
    - 001 - 099: Depicts the order in which the requirements should be implemented. Note that sequence #'s 000 and 100 are reserved, as indicated in the NOTE below.

The structure of each chapter's notes and requirements are sequenced based on the ordered guidelines listed below:
  - FIRST: Read the information (INF) notes to help guide you through the exercises.
    - Example (INF): IPP-INF-01-001 is the first (001) note in Lab Module 01 associated with Programming in Python (IPP), and is for informational (INF) purposes.
  - SECOND: If you're a student in a IPP-specific course (e.g., Building Digital Twins), read through the STU category requirements to prepare for each exercise. Else, skip to the THIRD guideline.
    - Example (STU): IPP-STU-02-001 is the first (001) student-specific task in Lab Module 02 associated with Programming in Python (IPP).
  - THIRD: Read and implement the configuration (CFG) requirements to prepare for each exercise.
    - Example (CFG): IPP-CFG-02-001 is the first (001) configuration-specific task in Lab Module 02 associated with Programming in Python (IPP).
  - FOURTH: Read and implement each exercise related to the Python Exercise Components (PEC).
    - Example (PEC): IPP-PEC-01-001 is the first (001) PEC task in Lab Module 01 associated with Programming in Python (IPP). It only applies to the given Python programming exercise.
  - FIFTH: Read and implement any integration exercise(s) to verify your functionality is working properly.
    - Example (INT): IPP-INT-05-001 is the first (001) integration task in Lab Module 05 associated with Programming in Python (IPP). Unless otherwise specified, it should be implemented AFTER all CFG and PEC related tasks.

NOTE: As alluded to previously, an exception to the numbering sequence scheme is made for build-specific tasks related to the PEC repository. The initial build requirement (check out a new branch) is numbered '000' for each component (e.g., IPP-PEC-02-000) and should be implemented before any other component-specific requirement, and '100' for the final build requirement (e.g., IPP-PEC-02-100), which should be implemented after all other component-specific requirements.

## Other things to know

### Pull requests

PR's are disabled while the codebase is being developed.

### Updates

Much of this repository, and in particular unit and integration tests, will continue to evolve, so please check back regularly for potential updates.
Please note that API changes can - and likely will - occur at any time.

# REFERENCES

## Tools and Specifications (subject to change)

- [ipp-exercise-tasks](https://github.com/programming-in-python/ipp-exercise-tasks)
  - Reference: Andrew D. King. Programming in Python Lab Module Exercise Tasks (PET). (2025) [Online]. Available: https://github.com/programming-in-python/ipp-exercise-tasks.
- [ipp-exercise-components](https://github.com/programming-in-python/ipp-exercise-components)
  - Reference: Andrew D. King. Programming in Python Lab Module Exercise Components (PEC). (2025) [Online]. Available: https://github.com/programming-in-python/ipp-exercise-components.
- [Visual Studio Code](https://code.visualstudio.com/)
  - Reference: Microsoft. Visual Studio Code. Available: https://code.visualstudio.com/. Accessed 15Nov2023.
- [Wireshark](https://www.wireshark.org/)
  - Reference: G. Combs et al. Wireshark. Available: https://gitlab.com/wireshark/wireshark. Accessed 15Nov2023.

## Content

- [The Python programming language](https://github.com/python/cpython)
  - Reference: "The Python programming language.", Python Software Foundation. Available: https://github.com/python/cpython. Accessed 15 July 2025.
- [Python for beginners](https://www.python.org/about/gettingstarted/)
  - Reference: “Python for Beginners.”, Python Software Foundation, Available: https://www.python.org/about/gettingstarted/. Accessed 15 July 2025.
- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
  - Reference: "The Python Tutorial.", Python Software Foundation. Available: https://docs.python.org/3/tutorial/index.html. Accessed 15 July 2025.
- [The Python Standard Library](https://docs.python.org/3/library/index.html)
  - Reference: "The Python Standard Library.", Python Software Foundation. Available: https://docs.python.org/3/library/index.html. Accessed 15 July 2025. 

# IMPORTANT NOTES

This code base is under active development.

If any code samples or other technology this work contains, describes, and / or is subject to open source licenses or the intellectual property rights of others, it is your responsibility to ensure that your use thereof complies with such licenses and/or rights.

All trademarks referenced herein are property of their respective holders.

# LICENSE

Please see [LICENSE information in IPP-DOC-LIC](https://github.com/programming-in-python/ipp-exercise-tasks/issues/2) for more information. In summary:

*Documentation - Usage and License*

This project's [written instructions and non-source code documentation](https://github.com/orgs/programming-in-python/projects/1) - all Notes, Instructions and Cards contained within this Kanban board - are available under the following license:
 - Documentation: Copyright &copy; 2025 by [Andrew D. King](https://andyking.me). Licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/ " target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0 <img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a>.
 - See [LICENSE](https://github.com/programming-in-python/ipp-exercise-tasks/blob/main/LICENSE) for details.

*Source Code Solutions and Examples - Usage and License*

This project contains embedded sample source codes representing examples and solutions. Unless otherwise represented, these embedded source codes (C# and Python) are available under the following license:
 - Source Codes: Copyright &copy; 2025 [Andrew D. King](https://andyking.me). Licensed under [The MIT License](https://opensource.org/licenses/MIT).
 - See [LICENSE-CODE](https://github.com/programming-in-python/ipp-exercise-tasks/blob/main/LICENSE-CODE) for details.
