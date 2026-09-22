Data Validation System



About The Project



This project is a desktop application built using Java Swing. Its main purpose is to capture user information and ensure that all entered data is valid before being accepted. The application verifies that every field is completed correctly and meets the specific validation rules set for it.



Key Features

The system is designed to validate the following user details:



* First name and last name 
* Identity number
* Age
* Gender
* Phone number
* Email address



How Validation Works 

To ensure data accuracy, the application performs several checks:



* Presence Check: Ensures no required field is left blank
* Type Check: Verifies that numeric fields only contain numbers and that name fields only contain letters.
* Length Check: Confirms that the ID number and contact number have the correct number of digits
* Format Check: Validates that the email address is in the proper format.
* Range Check: Makes sure the entered age falls within a realistic range of 1 to 120.



If any information is incorrect, the system shows a clear error message to guide the user.



Tools And Technologies

* Java
* Java Swing for the user interface
* NetBeans IDE
* Git and GitHub for version  control and hosting



Steps To Run The Application

1. Download the project from the GitHub repository
2. Open the project using the NetBeans IDE
3. Locate and open the file named DataValidationForm.java.
4. Run the application
5. Fill in all the required details on the form
6. Click the SAVE button to validate the data
7. Use Clear to reset all fields and EXIT to close the program



Project Structure

DataValidationSystem/

├── src/

│ ├── DataValidationForm.java

│ ├── DataValidationForm.form

│ └── datavalidationsystem/

│ └── DataValidationSystem.java

├── nbproject/

├── lib/

├── build.xml

├── manifest.mf

└── README.md



Author
Bonolo Mogorosi



Repository

This project is available on GitHub and was created as part of the Java Swing Data Validation System assignment.































