Download Link: https://assignmentchef.com/product/solved-cse240-homework-5-array-of-structs-and-enum-types
<br>
<h1>Introduction</h1>

The aim of this assignment is to make sure that you understand and are familiar with the concepts covered in the lectures, including basic C syntax, using structures and enumeration types.  By the end of the assignment, you should have

<ul>

 <li>understood the concepts and operations of enumeration type, arrays, structures, and array of structures, and files.</li>

 <li>written a program using enumeration type and an array of structures.</li>

</ul>

<strong>Reading</strong>: Textbook Chapter 2, sections 2.5, and 2.6, and lecture slides covered.

<strong>Exercising</strong>: Complete the multiple choice questions in Textbook Section 2.10. The answers of the questions are available in course Web page.

You are expected to do the majority of the assignment outside the class meetings.   Should you need assistance, or have questions about the assignment, please contact the instructor or the TA during their office hours.

You are encouraged to ask and answer questions on the course discussion board.  However, do not share your answers or code in the course discussion board. <strong>Do not cooperate with your peers in doing the individual assignments.  </strong>Programming Assignment

<ol>

 <li>You are given a partially completed program hw05q1.c. You should follow the instructions given in the program to complete the functions so that the program executes as instructed. The program declares a struct ‘bookDetails’ with elements for book name, publication year, library name and number of copies You will be completing a program that creates a list of books (array of structures). It is a menu-driven program where the user is given the following options:</li>

 <li>Add a new book to the list. When adding a new book to the list, the user is prompted for book name, publication year, library name and number of copies of the book. The book should be added at the end of the list. If the name of the book to add already exists in the list, then you should not add the book to the list. The library name is enum type.</li>

 <li>Display the list of books.</li>

 <li>Sort the list of books alphabetically by book name. The sorting should happen within the list. You should not create a new list of books having sorted books.</li>

</ol>

There is a save() already implemented to write the book list to a file ‘Book_List.txt’. save() is executed at the end of the program when the user quits the program. You need to implement load() which is called at the start of the program. This function will read the saved file and fill in the array of structures. You need to read the file in the same order and manner that it is saved in save().

Expected output of each function:

<strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/580.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/580.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/137.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/137.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript> <img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/342.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/342.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></strong>

<strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/969.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/969.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript>load</strong><strong><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/210.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/05/210.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong><u></u>