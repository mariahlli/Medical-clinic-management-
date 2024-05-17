# Medical clinic system managent in java
This project is written in JAVA using the database MySQL.
## How to Run the project:
1. **Download the project**: Clone or download the project folder from the repository.

2. **Extract the project folder**: If you downloaded a zip file, extract it to a location of your choice on your computer.

3. **Open the project folder in a java ide**: Locate and open the folder with any java ide as eclipse or netbeans.

4. **Add MySQL connector**: Once the project opened right click on it then click priorities then java build path
 <img width="417" alt="Screenshot 2024-05-09 at 22 33 27" src="https://github.com/mariahlli/Medical-clinic-management-/assets/118778107/d3caace1-7640-44ce-b1d1-904066993266">
 
 now add these jars that you find in the project following this path Hospital Management/dist/lib to external jars in java build path.
 
5. **Setting the database**:

   1- Download MySQL command line.
   
   2- Once Downloaded open terminal and run the command : **mysql -u root**.

   3- Create a database named hospital using the command :**CREATE DATABASE hospital;**.

   4- Now run the sql scrpit in the project using the command :**source yourpath;**

   5- Run this commnd to set a password to the database:**ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '12';**
   (you can change the password but then you gotta change it in the source code too).
6. **Run the code**:Now that everything is set you can run the code.
  ## Report
  For a detailed report about the project, please refer to the accompanying PDF file titled `medicsl_clinic_managment_Report.pdf`.
  ## Dependencies
  - all required **JAVA** **MySQL command line** and **JAVA Ide** the necessary classes are in **src**.
- it's better if you open it in eclipse ide .
