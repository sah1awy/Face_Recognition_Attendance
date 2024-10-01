# Face_Recognition_Attendance

This Tkinter-based application allows businesses to register new employees and efficiently track their attendance. It features a simple GUI for adding employee details, storing the data in a log file, and marking attendance in real-time. The app also provides reports on employee attendance for managerial review. This tool is designed to streamline HR operations and ensure accurate attendance tracking.  

## Project Phases
The development of this Tkinter-based employee management system was done in several steps, ensuring both functionality and a user-friendly interface.

**Step 1: Design the User Interface**
I began by designing the application's interface using Tkinter. The aim was to create a clean and intuitive GUI that allows users to easily interact with the system. Key components of the design included input fields for employee registration, buttons for submitting information, and an area for displaying attendance status. This phase focused on ensuring that the user could navigate the app smoothly.

**Step 2: Create the util.py File**
To improve code reusability and maintainability, I developed a `util.py` file that contains the core functionalities needed to work with Tkinter. This file includes helper functions to manage the layout, buttons, labels, and interactions within the app. The purpose was to modularize the code, allowing for easy modifications and expansions in the future.

**Step 3: Integrate Face Recognition for Attendance**
Once the interface and utility functions were set, I integrated a face recognition system into the app. The face recognition library was used to detect whether an employee's face already existed in the database. If the system did not recognize the face, it would automatically register the new employee and store their details. If the face was recognized, the app would log their attendance for that day, ensuring an efficient and seamless check-in process.

This step involved setting up a database to store employee information, including their face data, and developing the logic to differentiate between new and existing employees.

