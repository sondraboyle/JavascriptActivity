# JavascriptActivity
Day Two of Learning Javascript: Using the DOM to Change Your HTML

1)	Give all the links the class of “links”
  a.	Create a variable to store the links (use the DOM)
  b.	Create a loop where each link is given a new class name

2)	In the same loop, change the destination of the links
  a.	Change the href attribute of the links

3)	Make the title become the input text when you click the button
  a.	Store Title in a variable
  b.	Store the button in a variable
  c.	Story the input value from the title-input field in a variable
  d.	Create an onclick function for the button
      i.	Place the input value variable inside the function
      ii.	Change the title text to equal the input value

4)	Update the number of likes when you click the “like” button
  a.	Create a variable that holds the like-button
  b.	Create a variable that represents the number of likes starting at 0
  c.	Create a variable that hold the <span> tag in the likes <div>
  d.	Create a function where clicking the button adds a like, and changes the span tag to equal the number of likes

5)	Make the story progress when you press the “Next” Button
  a.	Store the paragraph tag for the story text in a variable using the DOM
  b.	Store the next-button element in a variable using the DOM
  c.	Make an onlick function for the button 
      i.	Inside the function, make the innertext of your paragraph equal storyText[storyProgress]
      ii.	Also inside the function, add one to storyProgress

6)	Create an if statement so that the story starts over when they reach the end and click the button
  a.	Place this if statement inside the onclick function
  b.	HINT: Find out what index number is for the end. The beginning is 0.


