Download Link: https://assignmentchef.com/product/solved-csci204-mcs9204-csci804-object-and-generic-programming-in-c-laboratory-exercise-6
<br>
Task: A template function (1.0)




<ul>

 <li>Create a function template named <strong>average(…)</strong>. It accepts two arguments of the same type and computes their arithmetic average. The average is returned as a <strong>double </strong></li>

 <li>Overload <strong>the average(…)</strong> function to work correctly with three arguments.</li>

 <li>Create a class named <strong>CollegeCourse</strong> with fields for the course ID (e.g. ‘ENG101’), your grade (e.g. ‘A’) and the credits earned for the <strong>CollegeCourse</strong> (e.g. 3). <strong> </strong>

  <ul>

   <li>The <strong>CollegeCourse</strong> constructor accepts values for these fields as arguments, and calculates a forth field named <strong>honorPoints</strong>. Calculate honorPoints as the product of the grade points (4 for an A, 3 for a B, 2 for a C and 1 for a D) and the credits.</li>

   <li>The <strong>CollegneCourse</strong> has a manipulator <strong>setValues(…)</strong> accepts values for these fields as arguments, and calculates the forth field named honorPoints.</li>

   <li>Overload the <strong>+ operator</strong> so that honor points for courses can be summed to create a summary <strong>CollegeCourse</strong> object whose course ID is “Total” and grade is determined by ratio of the total honor points and the total credit point. The grade is ‘F’ if the ratio is less than 1.</li>

   <li>Overload the <strong>/ operator</strong> so that a <strong>CollegeCourse</strong> object’s honorPoints can be divided by an integer</li>

   <li>Overload the <strong>&lt;&lt; operator</strong> to display the details of a <strong>CollegeCourse</strong>.</li>

  </ul></li>

</ul>




Save the implementation as <strong>Averages.cpp</strong>. Download the file <strong>testAverages.cpp</strong> in which declares several integers, doubles and <strong>CollegeCourses</strong> and verifies that both versions of <strong>average(…)</strong> work correctly with different arguments.




Compile the program like g++ testAverages.cpp  Run the program like.

./a.out




average of 7 and 26 is 16




average of 39.25 and 2.01 is 20.63




average of

ENG101 Grade: A Credits: 3 Honor points: 12

PSY251 Grade: B Credits: 3 Honor points: 9

10.5




average of 7, 26 and 100 is 44




average of 39.25, 2.01 and 4.2 is 15.1533




average of

ENG101 Grade: A Credits: 3 Honor points: 12

PSY251 Grade: B Credits: 3 Honor points: 9

HIS301 Grade: D Credits: 4 Honor points: 4

8.33333





