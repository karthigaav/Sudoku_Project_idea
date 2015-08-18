# Sudoku_Project_idea

<b>About Sudoku Game:</b></br>
A Sudoku puzzle uses a 9 × 9 grid in which each column and row, as well as each of the nine 3 × 3 subgrids, must contain all of the digits 1 · · · 9.</br>

<b>Project Objective:</b></br>
To design a multithreaded application that determines whether the solution to a sudoku puzzle is valid.</br>

<b>How many threads needed to check the validity:</b>
<ul>
<li>A thread to check that each column contains the digits 1 through 9</li>
<li>A thread to check that each row contains the digits 1 through 9</li>
<li>Nine threads to check that each of the 3 × 3 subgrids contains the digits 1 through 9</li></ul></br>

Therefore, from the above logic we can conclude there would be 11 seperate threads. However, it is possible to have more that 11 threads in this project.For example, rather than creating one thread that checks all nine columns, you could create nine separate threads and have each of them check
one column.But, you may ask if too many threads will make the program or logic to be not effcient. Yes, that may or may not so I am planning to give a complete observation on two versions(i.e one application with 11 threads and another application with .<br>

<b>Software Requirements:</b></br>
Java, JavaApplet, Eclipse IDE Editor

<b>System Requiremnts:</b></br>
You can develop the program in Windows, MAC or Linux since Java is a platform independent. I am going to develop it using Windows operating system.</br>

<b>Why using multiple threads for applications is good than using a single process or thread:</b>
Theoritical Explanation: The process with multiple threads make a great server for example printer server. Threads can share common data, they do not need to use interprocess communication.</ br>




