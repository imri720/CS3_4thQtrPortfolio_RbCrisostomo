Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.

 When the sidebar’s positioning is changed to relative, the distance between it and the top/left/right/bottom of its current position becomes equal to the number of pixels you apply.

Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?

Unlike relative positioning, A	fixed positioning makes it so that the footer follows the screen when you scroll up or down the page. This is because the entire point of fixed positioning is that it stays in its fixed position no matter where you are on the page, contrasting with the relative positioning.

Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?

Absolute positioning changes the distance of the main content from the center by the same amount of pixels you apply in each cardinal direction (top/right/left/bottom). As opposed to fixed, which is dependent on the actual screen, setting it to absolute position keeps it in its place relative to the center of the page and does not rely on the user's screen.

Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?

The notice appears above the main content, because it has a greater z-index, which means it becomes the upper layer that overlaps the main content. If you were to swap the z-index values, the main content is the one that overlaps the notice due to the higher z-index.

Challenge:
What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
Try to change the position of .content to relative then to fixed. What do you observed each time?
What do you observe on about the effect of z-index on .notice and .content boxes?









Reflection: 

a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?

Static - It is completely relative to nothing, it is the base position of a CSS element.
Relative - It moves from the current position away from the cardinal directions, equal to the amount of pixels applied.
Absolute - It moves from the center towards the cardinal directions, equal to the amount of pixels applied.
Fixed - It is reliant on the user’s screen.

b. How does absolute positioning depend on its parent element?

It depends on the parent element as it turns into the center. It acts as a reference point for 

c. How do you differentiate sticky from fixed (you can research on sticky)?

Sticky is simply the combination of fixed and relative, it stays in its set position relative to the cardinal directions until the user scrolls past a certain point, making it then stick to a position on the user’s screen.


d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples.

I would make sure that things like notices or notifications have a higher z-index and are sticky. I would keep my headers and footers fixed.


