Download Link: https://assignmentchef.com/product/solved-comp1410-assignment-3-text-analysis
<br>



The availability of computers with string-manipulation capabilities has resulted in some rather interesting approaches to analyzing the writings of great authors. Much attention has been focused on whether William Shakespeare ever lived. Some scholars find substantial evidence that Christopher Marlowe actually penned the masterpieces attributed to Shakespeare. Researchers have used computers to find similarities in the writings of these two authors. Regardless of this particular controversy, this assignment examines three methods for analyzing texts with a computer.

<strong>Your task is to:  </strong>




Write a complete, well documented C program that reads several lines of text and prints three tables indicating:

<ul>

 <li>the number of occurrences of each letter of the alphabet in the complete text</li>

 <li>the number of one-letter words, two-letter words, three-letter words, and so on, appearing in the complete text</li>

 <li>the number of occurrences of each different word in the complete text Note that the term “complete text” used above refers to all characters in all lines of inputted text.</li>

</ul>




<strong>Requirements and Hints:  </strong>




<ol>

 <li>Given several lines of text, your program should implement <u>at least</u> the following functions (in other words, additional functions may be useful, depending on the approach used):</li>

 <li><strong>void letterAnalysis( )</strong>, that gets several lines of text and the number of lines of text as input parameters and prints a table indicating the number of occurrences of each letter of the alphabet in the complete text.</li>

 <li><strong>int wordLengthAnalysis( )</strong>, that gets several lines of text, the number of lines of text and a <u>length</u> as input parameters and returns the number of occurrences of words with that <u>length</u> appearing in the text. The main() function should call this function with different word lengths and then prints a table indicating the number of one-letter words, two-letter words, three-letter words, and so on, in the text. The maximum word length may be assumed to be 20 letters.</li>

 <li><strong>void wordAnalysis( )</strong>, that gets several lines of text and the number of lines of text as input parameters and prints a table indicating the number of occurrences of each different word in the text. The program should include the words in the table in the same order in which they appear in the text. <strong> </strong></li>

</ol>

<strong>Input:  </strong>




Input is a number (say, int N) and several (i.e. N) lines of text from a file (using input redirection) or from the user (using standard keyboard input). For this, first the number (N) of text lines should be read, and then each line of text should be read individually. The maximum number of lines is 10 but each text line might have different lengths (however, the maximum number of characters in any individual line is 80).




<strong>Hint</strong>: You can use <u>a two dimensional array</u> or <u>an array of pointers</u> to save the text lines.




For example

<strong>4 </strong>

<strong>To be, or not to be? That is the question: </strong>

<strong>Whether ’tis nobler in the mind to suffer </strong>

<strong>The slings and arrows of outrageous fortune, Or to take arms against a sea of troubles, </strong>




<strong>Output: </strong>

The table below is intended to illustrate the output for this assignment, but it is presented for visual convenience only.  Your program will actually produce the output reports so that various outputs are generated one after another (First output, followed by Second output, followed by Third output).  In particular, note the formatting issues to be dealt with.  For the First output, the letter count must be right justified in a column of prescribed width.  For the Second output, the word “<strong>word</strong>” is used only if the number of words is 1, otherwise “<strong>words</strong>” is used.  Finally, for the Third output, “<strong>times</strong>” is used only when the number of occurrences is greater than 1.

<strong> </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="224">First output</td>

   <td colspan="2" width="224">Second output</td>

   <td width="224">Third output</td>

  </tr>

  <tr>

   <td width="224"><strong>Total letter counts: </strong>a: 10 b:  4 c:  0 d:  2 e: 15 f:  5 g:  3 h:  6…</td>

   <td width="42">1108452121 </td>

   <td width="182"> word of length 1  words of length 2  words of length 3  words of length 4  words of length 6  words of length 7  word of length 8  words of length 9  word of length 10</td>

   <td width="224">“To”   appeared 1 time“be,”   appeared 1 time“or”   appeared 1 time“not”   appeared 1 time“to”   appeared 3 times“be?”   appeared 1 time“That”   appeared 1 time“is”   appeared 1 time …</td>

  </tr>

  <tr>

   <td width="224"></td>

   <td width="42"></td>

   <td width="182"></td>

   <td width="224"></td>

  </tr>

 </tbody>

</table>




Note: You do not have to separate punctuation marks (such as comma, dot, or question mark) from the words. For example, both “<strong>be,</strong>” and “<strong>be?</strong>” counted as a three-letter words above.  <strong> </strong>


