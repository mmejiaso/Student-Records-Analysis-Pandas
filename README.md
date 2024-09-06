# Student-Records-Analysis-Pandas
This project analyzes student records using Pandas, allowing users to display all records, filter by last name or graduation year, and generate summary reports. Developed in Google Colab with error handling for smooth user interaction.
# Group Member: Maria Mejia  
# ReadMe File 

# Introduction to Project 
This project uses Pandas, a Python library, to analyze the data of a student records file named “students.txt”. The project allows the user to choose from four options to analyze the student records data. 

#Installation
This project requires the installation of Pandas library and upload of student.txt file to execute 

#Software 
This project was coded on Google Colab, a product from Google Research. Colab allows the execution of arbitrary python code through the browser, and is especially suited to machine learning, data analysis and education.

#Project Walk-through 
The project asks the user to input a number between 1-4 to choose what data the user wants the program to display. The four options are: 
1. Display All Records
2. Display Students With Last Name Beginning With A Letter
3. Display Students Graduating In A Chosen Year"
4. Display Summary Report Students Graduating On & After A Chosen Year

If user inputs 1, the program will display all Student Records in the data frame.

If user inputs 2, the program will ask the user to input the first letter of all students with last names beginning with that letter. After the user inputs a letter, the program will display all students with a last name beginning with the chosen letter and their matching student records. 

If user inputs 3, the program will ask the user to input the year of the students graduating in that certain year. After the user inputs the graduating year, the program will display all students graduating on the inputted graduating year and their matching student records.

If user inputs 4, the program prompts the user to input a grad year. Then, the program calculates the percentage of students of each specific grad program graduating on the inputted year and every year after until 2021 (since the records go until 2021). 
●	To do so, the program creates a data frame using pd.DataFrame from the GradYear selected by the user and stores it under value df_c4 (dataframe_column4).
●	If the user inputs any number greater than 2021, the program lets the user know that there’s no data record available. 

#Additional Information 
The program uses a try and except error to prevent any ValueError given the different data types used in the different choices of the program. 
