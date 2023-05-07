Download Link: https://assignmentchef.com/product/solved-multithreading-in-java
<br>
Multithreading in JavaDESCRIPTION:

Implementation of a set of classes and associated test program for synchronized, runnable objects of a particular type.PROBLEM:

You are to create a Java abstract class named displayCount that contains a public method named display() that is implemented to call its protected abstract method called genNext(). This method is to be implemented as a private method in the (concrete) subclasses to generate the next number (as a word) in a particular language. The displayCount class should also implement the Runnable interface. Its run method should be implemented to call the display method each time it is called (as a running thread).All concrete subclasses must implement the genNext() method to display a next number (up to ten), displayed as a word, each time called, e.g,one, two, three, four, …., tenCreate a set of three (concrete) subclasses of the displayCount class that each implements the counting of numbers in a different language (e.g., displayCountEnglish, displayCountSpanish, displayMandarin, etc.). Besides English, you may use any other two languages that you want.Finally, develop a class named bilingualDisplayCount that is designed to display the counting from one to ten in two languages, such that the secondary language is displayed in parentheses as given below,English/Spanishone (uno), two (dos), three (tres), four (quarto), …., ten (diez)English/Mandarinone (yi), two (er), three (san), four (si), five (wu), six (liu), seven(qi), eight (ba), nine (jiu), ten (shi)Whether the words are displayed in parentheses or not is determined by the way that the concrete classes are constructed. Develop a test program that displays what is shown above, for all combinations of the three languages (e.g., English/Spanish, Spanish/English, English/Mandarin, Mandarin/English, Mandarin/Spanish, etc.) This is a link to information on Java threads, with examples that are closely related to what needs to be done for this Assignment https://www.tutorialspoint.com/java/java_multithreading.htm

CLASS DIAGRAM: The class diagram for this assignment is given below.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/04/322.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/04/322.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>