Download Link: https://assignmentchef.com/product/solved-jac444-workshop-6
<br>
<strong>Description:</strong>

The following workshop lets you practice basic java coding techniques, creating classes, methods, using arrays, Java I/O, inheritance, polymorphism, Exceptional Handling, JavaFx (GUI), Lambda expressions, Functional Interface.




<strong>Task 1:</strong>

The details for the task are as follows,

<ul>

 <li>The popularity ranking of baby names from years 2009 to 2018 is downloaded from www.ssa.gov/oact/babynames and stored in files named <strong>txt</strong>, <strong>babynamesranking2010.txt</strong>, . . . , <strong>babynamesranking2018.txt</strong>.</li>

 <li>Each file contains one thousand lines/ records.</li>

 <li>Each line contains a <strong>ranking</strong>, a <strong>boy’s name</strong>, <strong>number for the boy’s name</strong>, a <strong>girl’s name</strong>, and <strong>number for the girl’s name</strong>.</li>

</ul>

For example, the first two lines in the file <strong>babynameranking2010.txt </strong>are as follows:




<ol>

 <li>Jacob 21,875 Isabella 22,731</li>

 <li>Ethan 17,866 Sophia 20,477</li>

</ol>




So, the boy’s name Jacob and girl’s name Isabella are ranked #1 and the boy’s name Ethan and girl’s name Sophia are ranked #2. 21,875 boys are named Jacob and 22,731 girls are named Isabella.




<strong>Note:</strong> There are some common names for both boys ang girls as well.




You have to write a program that asks the user to enter the year, gender, and followed by a name, and displays the ranking of the name for the year. Here is a sample run:

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Task 2: (Lambda Practice) </strong>




This task asks you to write a few lambda expressions and a function that returns a lambda expression as its value.




Suppose that a functional interface named <em>ArrayProcessor </em>is defined as




@Functional Interface  public interface ArrayProcessor {  double apply( double[] array );

}




<ul>

 <li>Write a class that defines <u>four</u> <em>public static final </em>variables of type ArrayProcessor that process an array in the following ways:</li>

</ul>




<ol>

 <li>find the maximum value in the array</li>

 <li>find the minimum value in an array</li>

 <li>find the sum of the values in the array</li>

 <li>find the average of the values in the array.</li>

</ol>

<ul>

 <li>In each case, the value of the variable should be given by a lambda expression.</li>

</ul>




The class should also define a function

public static ArrayProcessor counter( double value ) { …




<ul>

 <li>This function should return an ArrayProcessor that counts the number of times that <em>value </em>occurs in an array.</li>

 <li>The return value should be given as a lambda expression.</li>

 <li>The class should have a <em>main</em>() routine that tests your work.</li>

 <li>Ask the user to give array elements.</li>

</ul>

<strong> </strong>

Workshop Header




/**********************************************

<strong>Workshop #  </strong>

<strong>Course:</strong><em>&lt;subject type&gt; – Semester </em>

<strong>Last Name:</strong><em>&lt;student last name&gt; </em>

<strong>First Name:</strong><em>&lt;student first name&gt; </em>

<strong>ID:</strong><em>&lt;student ID&gt; </em>

<strong>Section:</strong><em>&lt;section name&gt; </em>

<em>This assignment represents my own work in accordance with Seneca Academic Policy. </em>

<em>Signature </em>

<strong>Date:</strong><em>&lt;submission date&gt; </em>

**********************************************/




<strong> </strong>

Code Submission Criteria:

Please note that you should have:

<ul>

 <li>Appropriate indentation.</li>

 <li>Proper file structure</li>

 <li>Follow java naming convention</li>

 <li>Document all the classes properly</li>

 <li>Do Not have any debug/ useless code and/ or files in the assignment</li>

 <li>Do not have everything in the <em>main method</em>.</li>

 <li>Have a separate TestClass with the main method in it.</li>

 <li>Check your inputs if the user is not entering garbage inputs.</li>

 <li>Use exceptional handling or other methods to let the user know if the inputs are incorrect.</li>

</ul>




Deliverables and Important Notes:




<strong>All these deliverables are supposed to be uploaded on the blackboard once done. </strong>

<strong> </strong>

<ul>

 <li>You are supposed to create video/ record voice/ detailed document of your running solution. <strong>(50%)</strong>  o Screen Video captured file should state your last name and id, like</li>

</ul>

Ali_123456.mp4 (or whatever the extension of the file is) o Record voice clip should also include a separate word file with the screen shots of your program’s output, state your last name and id, like Ali_123456.mp3 (or whatever the extension of the file is)

o Detailed document should include screen shots of your output, have your name and id on the top of the file and save the file with your last name and id, like Ali_123456.docx (or whatever the extension of the file is)

<ul>

 <li>A word/ text file which will reflect on learning of your concepts in this workshop. Also include the instructions on how to run your code.                                 <strong>(30%)</strong>

  <ul>

   <li>Should state your Full name and Id on the top of the file and save the file with your last name and id, like Ali_123456.txt</li>

  </ul></li>

 <li>Submission of working code.                                                                         <strong>(20%)</strong>

  <ul>

   <li>Make sure your follow the “<strong>Code Submission Criteria”</strong> mentioned above.</li>

   <li>You should zip your whole working project to a file named after your Last Name followed by the first 3 digits of your student ID. For example, zip.</li>

  </ul></li>

 <li>Your marks will be deducted according to what is missing from the above-mentioned submission details.</li>

 <li>Late submissions would result in additional 10% penalties for each day or part of it.</li>

 <li>Remember that you are encouraged to talk to each other, to the instructor, or to anyone else about any of the assignments, but the final solution may not be copied from any source.</li>

</ul>




<strong> </strong>