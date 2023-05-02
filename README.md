Download Link: https://assignmentchef.com/product/solved-cop3330-object-oriented-programming-euchre-project-part-5-assignment-scope
<br>
For this assignment students will continue developing the front end, or User Interface, portion of the Euchre game.  Based on my professional experience working in the industry I have <strong><em>always</em></strong> had to develop a UI for every application, therefore I translate that experience to students so they can have the same opportunity and be prepared professionally.




Typically, there is a one-to-one correlation of back end functionality to front end UI component.  Depending upon the design of the application it doesn’t always correlate perfectly, however with Euchre, it works well.




<table>

 <tbody>

  <tr>

   <td width="312"><strong>Back-end functionality</strong></td>

   <td width="312"><strong>Front-end UI component</strong></td>

  </tr>

  <tr>

   <td width="312">AiPlayer.java</td>

   <td width="312">AiPlayerUi.java</td>

  </tr>

  <tr>

   <td width="312">Card.java</td>

   <td width="312">CardUi.java</td>

  </tr>

  <tr>

   <td width="312">Game.java</td>

   <td width="312">GameUi.java</td>

  </tr>

  <tr>

   <td width="312">HumanPlayer.java</td>

   <td width="312">HumanPlayerUi.java</td>

  </tr>

 </tbody>

</table>




The goal is to develop the front-end components of the game Euchre by creating or updating classes:

<ol>

 <li>java</li>

 <li>java</li>

 <li>java</li>

 <li>java</li>

</ol>




The UI will be developed in multiple assignments, it is <strong><em>not</em></strong> expected that for Part 5 the fully functioning UI is complete.




The image that follows is a what my version of the UI will looks like.  It does <strong><em>not</em></strong> have to be an exact match.  The rubric will provide guidance and recommendations on how to accomplish this, however feel free to be creative in developing the look and feel of the UI.










To accomplish this:

<ol>

 <li>Reference the tasks below for the specifics of the source code requirements.</li>

 <li>Compress a project and submit to Webcourses</li>

 <li>Decompress compressed project and verify it is a Netbeans project</li>

</ol>




<strong>References</strong>

<ol>

 <li>docx</li>

 <li>Setting up a project in Netbeans.docx</li>

 <li>Netbeans right click menu help.docx</li>

</ol>

<strong> </strong>

<strong>Deliverables</strong>

To complete this assignment, you must submit your <strong>compressed Netbeans project </strong>to Webcourses.




Please keep in mind that the tasks are guidance to accomplish the goals of the assignment.  At times students will be required to do additional research (e.g. Google That S**T (GTS)!) to find implementation options.  In the industry, software engineers are <strong><u>expected</u></strong> to be very self-sufficient to find the best solution for the task at hand.




<strong><em>I have provided multiple code examples on Webcourses that shows how to implement numerous of the tasks below, please reference those code examples prior to asking me for help!    </em></strong>

<strong> </strong>

<strong>Tasks and Rubric</strong>

<table width="682">

 <tbody>

  <tr>

   <td colspan="3" width="682"><strong>Activity</strong></td>

  </tr>

  <tr>

   <td width="180"><strong>euchre package</strong></td>

   <td width="502"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>core package</strong></td>

   <td width="502"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>Game.java</strong></td>

   <td width="502">1.      Update class to add the following member variablea.       GameUi ui</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">2.      Add method setGameUi to do the followinga.       Return type voidb.      One parameter of data type GameUic.       Set member variable ui equal to parameter3.      Add method getTeams to do the followinga.       Return type ArrayList&lt;Team&gt;b.      Empty parameter listc.       Returns the member variable of data type ArrayList that contains elements of class Team4.      Add method getTrump to do the followinga.       Return type Cardb.      Empty parameter listc.       Returns the member variable of data type Card that represents the trump card for the dealt hand</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>Player.java</strong></td>

   <td width="502">1.      Update class to add the following member variablea.       JPanel ui2.      Generate a getter/setter for the member variable ui</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>images package</strong></td>

   <td width="502">1.      Add package images to the project2.      Add images for the cards to the package</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>userInterface package</strong></td>

   <td width="502"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>GameUi.java</strong></td>

   <td width="502">1.      Update the class to add the following member variablesa.       JPanel trumpPanel (if you added bidPanel in the last assignment, please rename it)b.      JLabel teamOneScoreLblc.       JLabel teamOneScored.      JLabel teamTwoScoreLble.       JLabel teamTwoScoref.        JLabel trumpCard</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">2.      Update initComponents to do the followinga.       Instantiate the member variable of class ArrayList containing elements of class JLabel that represents the card each player plays on the table JPanelb.      Loop through the four players and do the following1.      Instantiate an instance of class JLabel2.      Based on the position of the player set the size of the JLabel using class Dimension to be horizontal or vertical width and height3.      Instantiate an instance of class CardUi passing the JLabel from step 1 as an argument4.      Set the instance of class JLabel from step 1 equal to method call getLabel() on class CardUi5.      Add the instance of class JLabel from step 1 to the member variable of call ArrayList containing element of class JLabel representing the cards played on the tablec.       Add each instance of class JLabel stored in the ArrayList containing elements of class JLabel representing the cards played so that1.      Human player JLabel for card played is in the SOUTH2.      The remaining AI players have a JLabel placed in from of their position at the table</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>AiPlayerUi.java</strong></td>

   <td width="502">1.      Update the class to add the following member variables1.      CardUi cardUi;2.      int width;3.      int height;</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">2.      Update method initComponents() to do the followinga.       Set the member variables width and height based on the orientation of the cards, vertical or horizontal</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">3.      Update method displayCards() to do the followinga.       In the for loopi.      Instantiate the instance of class CardUi passing as arguments1.      The instance of class Card in the player’s hand at the looping variable’s index2.      The instance of class JLabel created inside the for loop3.      The Player’s position at the tableii.      Set local variable of class JLabel representing the card equal to method call getLabel() on class CardUiiii.      Comment out the call to method setText() on the instance of class JLabel</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>HumanPlayerUi.java</strong></td>

   <td width="502">1.      Update the class to add the following member variables1.      CardUi cardUi;</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">2.      Update method displayCards() to do the followinga.       In the for loopi.      Instantiate the instance of class CardUi passing as arguments1.      The instance of class Card in the player’s hand at the looping variable’s index2.      The instance of class JButton created inside the for loopii.      Set local variable of class JButton representing the card equal to method call getButton() on class CardUiiii.      Comment out the call to method setText() on the instance of class JButton</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>CardUi.java</strong></td>

   <td width="502">1.      Add member variablesa.       Card card;b.      ImageIcon imageIcon;c.       JButton button;d.      JLabel label;e.       int position;</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">2.      Generate getters for member variablesa.       Of class JButtonb.      Of class JLabel</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">3.      Write a custom constructor that do the followinga.       Receives two parametersi.      Class Cardii.      Class JButtonb.      Set member variable of class Card to the passed parameterc.       Set member variable of class JButton to the passed parameterd.      Call method selectFrontImage()</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">4.      Write a custom constructor that does the followinga.       Receives three parametersi.      Class Cardii.      Class JLabeliii.      Intb.      Set member variable of class Card to the passed parameterc.       Set member variable of class JLabel to the passed parameterd.      Set member variable of primitive data type int to the passed parametere.       Based on the position of the player call method selectVerticalBackImage() or selectHorizontalBackImage()</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">5.      Write a custom  constructor that does the followinga.       Received one parameter of class JLabelb.      Set member variable of class JLabel to the passed parameterc.       Calls method selectHorizontalBackImage()</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">6.      Write method selectFrontImage() to do the followinga.       Instantiate an instance of class String to represent the file name of the image file set equal to explicit text “../images/”b.      Write a switch statement that evaluates the face of the instance of class Cardi.      Based on the naming convention of your image files, concatenate to the String instantiated in step a with the appropriate valueii.      For example, I named my files as such “AceHearts”, “AceEuchre”, “AceDiamonds”, “AceClubs”iii.      Therefore, I concatenate to the String instance “../images/” the explicit text “Ace”c.       Write a switch statement that evaluates the suit of the instance of class Cardi.      Based on the naming convention of your image files, concatenate to the String instantiated in step a with the appropriate valued.      Concatenate the explicit file extension to the String instance that represents the filename based on your naming convention, the String instance should look something like “../images/AceClubs.png” when finishede.       Instantiate an instance of class URL set equal to the static method call getClass().getResource() passing the String instance as an argumentf.        Using exception handling (i.e. in a try block)i.      Check if the instance of class URL is not null1.      If true, Instantiate the member variable of class ImageIcon passing the instance of class URL as an argument2.      Instantiate the member variable of class JButton passing the instance of class ImageIcon as an argumentg.      In the catch blocki.      Output an error message that the resource if not foundii.      Set the instance of class ImageIcon equal to null</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">7.      Write method selectVerticalBackImage() to do the followinga.       Instantiate an instance of class String set to explicit text “../images/backVertical.jpg” or whatever you named the back image of the cardb.      Instantiate an instance of class URL set equal to the static method call getClass().getResource() passing the String instance as an argumentc.       Using exception handling (i.e. in a try block)i.      Check if the instance of class URL is not null1.      If true, Instantiate the member variable of class ImageIcon passing the instance of class URL as an argument2.      Instantiate the member variable of class JLabel passing the instance of class ImageIcon as an argumentd.      In the catch blocki.      Output an error message that the resource if not founde.       Set the instance of class ImageIcon equal to null</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">8.      Write method selectHorizontalBackImage() to do the followinga.       Instantiate an instance of class String set to explicit text “../images/backHorizontal.jpg” or whatever you named the back image of the cardb.      Instantiate an instance of class URL set equal to the static method call getClass().getResource() passing the String instance as an argumentc.       Using exception handling (i.e. in a try block)i.      Check if the instance of class URL is not null1.      If true, Instantiate the member variable of class ImageIcon passing the instance of class URL as an argument2.      Instantiate the member variable of class JLabel passing the instance of class ImageIcon as an argumentd.      In the catch blocki.      Output an error message that the resource if not foundii.      Set the instance of class ImageIcon equal to null</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>Euchre application</strong></td>

   <td width="502"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502"> </td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>Test Cases </strong></td>

   <td width="502">Test Cases pass</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">Source compiles with no errors</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">Source runs with no errors</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong> </strong></td>

   <td width="502">Source includes comments</td>

   <td width="0"> </td>

  </tr>

  <tr>

   <td width="180"><strong>Total</strong></td>

   <td width="502"><strong> </strong></td>

   <td width="0"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Perform the following test cases</strong>

<table width="638">

 <tbody>

  <tr>

   <td colspan="3" width="638"><strong>Test Cases</strong></td>

  </tr>

  <tr>

   <td width="97"><strong> </strong></td>

   <td width="250"><strong>Action</strong></td>

   <td width="291"><strong>Expected outcome</strong></td>

  </tr>

  <tr>

   <td width="97"><strong>Test Case 1</strong></td>

   <td width="250"><strong>Rregression Testing: Initial JOptionPane displays </strong></td>

   <td width="291">JOptionPane is similar to figure 1</td>

  </tr>

  <tr>

   <td width="97"><strong>Text Case 2</strong></td>

   <td width="250"><strong>Regression Testing: JOptionPane Prompts User Name</strong></td>

   <td width="291">JOptionPane is similar to figure 2</td>

  </tr>

  <tr>

   <td width="97"><strong>Test Case 3</strong></td>

   <td width="250"><strong>Euchre Initial UI displays</strong></td>

   <td width="291">Game UI looks similar figure 3 where:1.      The human player’s cards show the appropriate image associated with each card in their hand2.      The AI players’ cards show a back image3.      The table has a place holder for each player when they play a card</td>

  </tr>

  <tr>

   <td width="97"><strong>Test Case 4</strong></td>

   <td width="250"><strong>Project view</strong></td>

   <td width="291">Project view matches figure 4</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

Figure 1 Intro JOptionPane

<strong> </strong>




Figure 2 Prompt for User’s Name




Figure 3 Euchre Initial UI













Figure 4 Project View