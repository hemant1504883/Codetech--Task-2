Name: Hemant Baghel
Company: CODTECH IT SOLUTIONS 
ID: CT4J3940
Domain: Java programming 
Duration: 5 July to 5 August
Mentor: Neela Santhosh Kumar


Overview of the Project

Project: Creating Student Tracker using Java Programming

The key objective of the StudentGrades program is to allow a user to input grades for various subjects and then perform several operations based on those inputs:
Adding Grades: The program allows the user to input grades for different subjects until they choose to exit. Each grade input consists of a subject name and a corresponding score.
Calculating Average Grade: After all grades are inputted, the program calculates the average grade based on the scores entered.
Determining Letter Grade: Using the calculated average grade, the program determines the corresponding letter grade ('A', 'B', 'C', 'D', or 'F') based on predefined grade ranges.
Displaying Grades: Finally, the program displays all entered grades, the calculated average grade, and the corresponding letter grade.
Grade Class (static class Grade):
Represents a single grade entry with fields for subject (String) and score (double).
StudentGrades Class:
Constructor (StudentGrades()): Initializes an empty ArrayList to store Grade objects.
addGrade(String subject, double score): Adds a new Grade object to the grades list with the provided subject and score.
calculateAverage(): Calculates the average score from all grades stored in grades.
calculateLetterGrade(double average): Determines and returns the letter grade based on the provided average score.
displayGrades(): Prints out all grades stored in grades, calculates and prints the average grade, and calculates and prints the corresponding letter grade.
main(String[] args): The main method where the program execution begins. It uses a Scanner object to read user input for subject names and grades, stores them using addGrade(), and finally displays the results using displayGrades().
Technologies Used:
Java Standard Library (java.util):
Object-Oriented Programming (OOP):Classes and Objects-The program defines a Grade class as a static nested class within StudentGrades. Each Grade object encapsulates data related to a specific subject and its score.
Encapsulation: grades ArrayList and its operations (addGrade(), calculateAverage(), calculateLetterGrade(), displayGrades()) are encapsulated within the StudentGrades class, promoting modular and reusable code.
Control Flow and Logic-Looping and Conditional Statement
Console Output:System.out.println
