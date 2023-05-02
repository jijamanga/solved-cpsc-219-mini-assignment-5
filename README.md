Download Link: https://assignmentchef.com/product/solved-cpsc-219-mini-assignment-5
<br>
CPSC 219: Mini-Assignment #5

Text only connections such as Putty won’t allow you to run programs that employ graphical user interfaces. If you have been working at home to complete assignments but haven’t installed JDK on your computer then you might want to either install a free file transfer program such as <a href="https://filezilla-project.org/">Filezilla</a> (server name: linux.cpsc.ucalgary.ca, port: 22) or perhaps a cloud based storage system such as<a href="https://www.dropbox.com/">www.dropbox.com</a>. To run your programs you can run ‘Java’ locally using JRE (unlike the JDK which includes the compiler you don’t have to worry about setting the ‘path’). Open up a command line on your home computer ‘cmd’ and use it to navigate to where you have your GUI code on your CPSC account. (. When you type ‘java Driver’ (or whatever the name of starting class is) your GUI will be run locally on your computer.

<h3>New Concepts to be applied for the assignment</h3>

<ul>

 <li>Implementing a simple graphical user interface with common GUI controls (JButton, JFrame) and event handlers (ActionListener).</li>

</ul>

<h3>Overview</h3>

<ul>

 <li>When the program runs it will create a JFrame containing a JButton the latter with some default text (Figure 1): <em>worth 1 mark</em></li>

 <li>When the button is pressed two things will happen:

  <ol>

   <li>The text of the button changes to a non-default value (Figure 2): <em>worth 1 mark</em></li>

   <li>Another JFrame window appears that contains the same non-default text contained in the button (Figure 3): <em>worth 1 mark</em></li>

  </ol></li>

 <li>The close behavior for both (no credit if you change one but not the other) JFrames (triggered when the close window control is clicked: Figure 4) is changed from hiding the window to the disposal of the control: worth <em>1 mark</em></li>

</ul>

<strong>Figure 1</strong>: Program initially run, JFrame contains a JButton with default text

<strong>Figure 2</strong>: Button pressed: the text of the button changes to a non-default value

<strong>Figure 3</strong>: Button pressed: a new  JFrame

<ul>

 <li>Unlike full assignments, min-assignments are only marked on program functionality (above).</li>

</ul>

<strong>Points to keep in mind:</strong>

<ol>

 <li><strong>Due time:</strong> All assignments are due at <strong>4 PM</strong> on the <a href="http://pages.cpsc.ucalgary.ca/~tamj/2017/219W/index.html">due dates</a> listed on the course web page.  Late assignments or components of assignments will not be accepted for marking without approval for an extension beforehand. The latest versions of the files that you have submitted in D2L as of the due date is what will be marked.</li>

 <li><strong>Extensions</strong> may be granted for reasonable cases by the course instructor with the receipt of the appropriate documentation (e.g., a doctor’s note). Typical examples of reasonable cases for an extension include: illness or a death in the family. Cases where extensions will not be granted include situations that are typical of student life: having multiple due dates, work commitments etc. Tutorial instructors (TA’s) will not be able to provide extension on their own and must receive permission from the course instructor first. (Note: Forgetting to hand your assignment or a component of your assignment in does not constitute a sufficient reason for handing your assignment late).</li>

 <li><strong>Method of submission: </strong>You are to submit your assignment using D2L [<a href="https://d2l.ucalgary.ca/shared/LE_Basics_Videos/index.htm">help link</a>]. Make sure that you [<a href="http://pages.cpsc.ucalgary.ca/~tamj/resources/Verifying%20D2L%20Submissions.pdf">check the contents of your submitted files</a>] (e.g., is the file okay or was it corrupted, is it the correct version etc.). It’s your responsibility to do this! (Make sure that you submit your assignment with enough time before it comes due for you to do a check).</li>

 <li><strong>Identifying information</strong>: All assignments should include contact information (full name and student ID number) at the very top of your program in the class where the ‘main()’ method resides. (Note other documentation is also required for most assignments).</li>

 <li><strong>Collaboration</strong>: Assignments must reflect individual work; group work is not allowed in this class nor can you copy the work of others.  For more detailed information as to what constitutes academic misconduct (i.e., cheating) for this course please read the following [<a href="http://pages.cpsc.ucalgary.ca/~tamj/2017/219W/assignments/misconduct.html">link</a>].</li>

 <li><strong>Execution</strong>: programs must run on the computer science network running Java 8.x. If you write you code in the lab and work remotely using a remote login program such as Putty or SSH then should already be using the correct version. If you choose to install Java on your own computer, then it is your responsibility to ensure that your program will run properly on the CPSC Linux computers. It’s not recommended that you use an IDE for writing your programs but if you use one then make sure that you submit your program in the form of text “.java” file or files. If you only submit your byte code files (e.g. Driver.class) then you will not be awarded any credit.</li>

 <li><strong>Use of pre-created Java libraries</strong>: unless otherwise told you are to write the code yourself and not use any pre-created functions from the Java libraries. For this assignment the usual acceptable functions include: System.out.print(), System.out.println(), the methods of the Console class and for some assignments the methods of the Random class. Look at the particular assignment description for a list of other classes that you are allowed to use and still get credit in an assignment submission.</li>

 <li><strong>Style conventions, programming decomposition</strong>: the marking points from the previous assignment also apply to this assignment. The one blanket exception is the use of a static debugging flag (or flags) if you choose to implement multiple flags.</li>

</ol>

<strong>D2L configuration:</strong>

<ul>

 <li>Multiple submissions are possible for each assignment: You can and should submit many times before the due date. D2L will simply overwrite previous submissions with newer ones.</li>

 <li><strong>Important</strong>!  Multiple files can be submitted for each assignment. I am allowing you to submit multiple files for each assignment so you don’t have to worry about archiving/compressing multiple files using a utility such as zip. However, this means that <strong>TAs will only mark the latest versions</strong> of each file submitted via D2L. Even if the version of a document that you want marked has been uploaded into D2L if it isn’t the latest version then you will only get marks for the latest version. (It’s unfair to have the TAs check versions or to remark assignments because marking is enough work as-is).</li>

</ul>

<h3></h3>

t: normal;”&gt;<strong> D2L configuration:</strong>

<ul>

 <li>Multiple submissions are possible for each assignment: You can and should submit many times before the due date. D2L will simply overwrite previous submissions with newer ones.</li>

 <li><strong>Important</strong>!  Multiple files can be submitted for each assignment. I am allowing you to submit multiple files for each assignment so you don’t have to worry about archiving/compressing multiple files using a utility such as zip. However, this means that <strong>TAs will only mark the latest versions</strong> of each file submitted via D2L. Even if the version of a document that you want marked has been uploaded into D2L if it isn’t the latest version then you will only get marks for the latest version. (It’s unfair to have the TAs check versions or to remark assignments because marking is enough work as-is).</li>

</ul>

<h3></h3>