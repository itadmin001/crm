# crm
### Jeremy Hester, Luis Ramirez, Matthew LaGreca

Matthew - Modals and How it works page content
Luis - Landing/How it works page content
Jeremy - Landing/How it works page content

# commentary from Matthew:
We decided that instead of making the sign-up and sign-in their own pages, to turn them into modals to pop up when their respective buttons are pressed
I volunteered to work on the sign-up and sign-in modal:s: I took a modular approach to design each one by themselves in modal_test.html, and Jeremy made it easy to work on them
by using JavaScript to configure the modal open automatically whenever the page was loaded, so that I wouldn't have to click the button to open it everytime a change was made.
I had the initial designs done by night time on Friday so that Jeremy could put them into the landing and how it works pages

Saturday, I decided to work on the "How It Works" sections on the how_it_works.html page, by modifying code that was already created by Jeremy earlier on the landing page.  
After I had finished we found out that the modals somehow broke from moving them into their respective pages and Jeremy and I had to scramble to figure out why it was breaking;
when one of us fixed something, it seemed to break something for the other person.  That was hectic but we ended up leaving fixing the modals to me instead of us trying to solve it 
independently and now everything works as it should.  Please clap!

#Jeremy
The biggest issue I had with this was the nav and middle section title in the beginning...took me about an hour to figure out the utility class alignments. I used a combination of flex and grid to lay out my pages. Assisted with modals and content throughout and went ahead and fleshed out other pages with content and made responsive. Was able to use utility classes for the modals so did not have to use any JS aside from what I gave Matthew for holding the modal open so he could work on it without having to reload every time. I used bootstrap snippets from the components pages and from Code Pen to flesh out the other pages and styled them with CSS to match the theme of the site. For the upper section 3x3 grid I used divs and border-radius to create and then positioned the svg's. Tied in all buttons to modals and added a chat modal for the Chat With Us buttons.

#Luis 
I worked on the bottom portion of the "Landing" page. I spent more time than expected getting the page formatted correctly, and even then I reached out to Matthew and Jeremy when I hit roadblocks. I enjoyed using Bootstrap where I could -cards, font weight, padding, etc.- but I got tunnel vision relying on it and struggled with aspects that needed CSS - images/background, positioning.