Download Link: https://assignmentchef.com/product/solved-prog1385-assignment-5-pioneer-carradio
<br>
In this assignment, you will be modifying your Assign-03 code to use <em>inheritance</em>.  I need you to create a class called <strong><em>PioneerCarRadio</em></strong> that inherits its radio operation functionality from the AmfmRadio class (so you could say that a <em>PioneerCarRadio</em> <strong>is an</strong> <em>AmFmRadio</em>).

One of the features that PioneerCarRadio adds is a user interface based on buttons (represented by keypresses obtained through a getch() function call) as follows.  There is no more menu driven input!

<strong>Keypresses: </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="261">On/Off</td>

   <td width="144">o (lower case “O”)</td>

  </tr>

  <tr>

   <td width="261">Volume up by 1</td>

   <td width="144">+</td>

  </tr>

  <tr>

   <td width="261">Volume down by 1</td>

   <td width="144">_ (underscore)</td>

  </tr>

  <tr>

   <td width="261">Scan up</td>

   <td width="144">=</td>

  </tr>

  <tr>

   <td width="261">Scan down</td>

   <td width="144">– (minus sign)</td>

  </tr>

  <tr>

   <td width="261">Switch band (e.g. am to fm to am)</td>

   <td width="144">b</td>

  </tr>

  <tr>

   <td width="261">Choose button 1 to 5</td>

   <td width="144">1 to 5</td>

  </tr>

  <tr>

   <td width="261">Set button 1 to 5</td>

   <td width="144">Shift+1 to Shift+5</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>You don’t have to worry about key repeat (i.e. whatever keys you receive, process).</li>

</ul>

<h2>Display</h2>

The user should never see the keystrokes that they enter (which is why you’re using getch() instead of getche()). <strong>After each <u>valid</u> keystroke</strong>, you should display the information in the following format (including spacing):

Pioneer XS440

Radio is on

Volume: 4

Current Station:  800 AM

AM Buttons:

1:  1000, 2:  1210, 3:   800, 4:   700, 5: 1300 FM Buttons:

1: 102.1, 2: 104.3, 3: 100.1, 4:  99.3, 5: 89.7

and (when the radio is off)

Pioneer XS440

Radio is off




<em>Learning From Your Elders … </em>




<strong>Guidelines: </strong>

<ul>

 <li>Start with the radio off.</li>

 <li>Do nothing for invalid keystrokes.</li>

 <li>Exit the program only when the user presses ‘x’.</li>

 <li>Move all keystroke handling code <strong>out of </strong><strong>main()</strong> and into the PioneerCarRadio class.

  <ul>

   <li>To do this, you’ll be developing a new method within the PioneerCarRadio class</li>

  </ul></li>

 <li>Do not display any kind of instructional menu saying what the keys do.</li>

 <li>The output should look <strong><u>exactly</u></strong> as above o I expect you to do this <strong><u>without changing</u></strong> the ShowCurrentSettings() method within the</li>

</ul>

AmFmRadio class o Also remember to have a print statement within your PioneerCarRadio’s destructor indicating that the PioneerCarRadio is being destroyed

<ul>

 <li>There should be <strong><u>no output</u></strong> from the <strong>AmfmRadio</strong> class o This is why you put in the code to turn off output in the previous assignment.</li>

 <li>Do <strong>not</strong> make or promote any data members of the AmfmRadio class to be protected and/or public.</li>

 <li>Put the source code for your new class in <em>cpp</em> and <em>PioneerCarRadio.h</em>.

  <ul>

   <li>Try to avoid changing the contents of AmFmRadio.cpp and AmFmRadio.h</li>

  </ul></li>

</ul>

&#x25aa;   the exception to this is fixing things that you did wrong in the previous assignment

<ul>

 <li>Put the test harness code for your new class in a source module named <em>cpp</em>.</li>

</ul>

<h2>Style and Convention Requirements</h2>

<ul>

 <li>Make any new data items that you create private.</li>

 <li>Your code must not unnecessarily duplicate similar code segments.</li>

 <li>We are going to continue to use the <em>Classic</em> commenting style in this assignment (i.e. not DOXygen) o Add full class header comments in each of your source files (even the .h file). For the descriptions of each, describe what the purpose of the class is, what the class can do (generally), what its purpose is, etc.

  <ul>

   <li>Add full method header comments on each method you develop and don’t forget your inline comments as well</li>

   <li>As discussed in class – also make sure to comment your private data members and any constants (private or public) as well</li>

   <li>Make sure that all comments that exist in the example are correct.</li>

  </ul></li>

</ul>

<h2>Other Stuff</h2>

<ul>

 <li>ZIP up all the source files : AmFmRadio.h, AmFmRadio.cpp, PioneerCarRadio.cpp, PioneerCarRadio.h and carDriver.cpp. Submit the ZIP to the appropriate eConestoga Dropbox by the deadline.</li>

</ul>


