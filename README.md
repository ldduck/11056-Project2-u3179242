# 11056 Front-end Web Design
## Project 2: Outside the Grid
### Lachlan Duck - u3179242

---

### Initial Concept

As a fan of utilitarian and brutalist architecture I wanted to incorporate those aesthetics into my website. I decided on a building gallery that showcases different brutalist structures across the planet. To compliment their often harsh shapes and materials, I chose a minimalist style, using simple type, shapes, placement, and colours to sell the feel and to keep consistency across the entire website. Initially I attempted to use the AI to create a gallery that was styled to look like a window on a much larger building. As is explained later in the 'prompts' section, it did not produced what i asked for but instead just gave me a window. This changed the entire concept as I could lean into minimalism by using the background as blank concrete canvas and the window gallery as a way to 'look in' to the world of utilitarian and brutalist design. Inspired by the Nakagin Capsule Hotel and megastructural design I wanted to impliment the idea of a modular system, thankfully due to the nature of a *div* it is easy to add more structures to the page, extending the 'window'.
 
### AI Prompts

I used 6 main prompts for my initial framework/working prototype.
1. **Using separate html and css can you write code that creates a gallery that looks like a window on a building?**
-  This prompt gave moderate success in intention. This prompt created the grid where the building images sit. Likely due to user error it did not produce what my intention was, however it created a new concept that I found interesting and wanted to experiment with.
2. **Can you write code to zoom in on the image when you hover over it?**
-  This prompt was successful, this was applied to each individual image inside the window. The AI automatically added a transition effect.
3. **Add css to align the images to they all fit the same.**
-  This prompt was successful in aligning the images as initially they were aligned inside the generated flexbox but not with each other.
4. **Please write separate HTML and CSS code that gives me a media query that makes a website compatible with standard desktop, tablet and mobile sizes.**
-  Successful in creating a responsive media query. I cross-referenced previous work, the internet and tested it using the web development tools on firefox.
5. **Write me css that changes the colour of text when you hover over it.**
-  Successful outcome, frankly, this was something I understood how to do. However, I was unsure if it would work the same way as changing the colour of links. Furthermore, I did not utilise this outcome as it did not work well on touchscreen devices.
6. **Using your code in response 1, can you rewrite it so that there is only 1 pane?**
-  this prompt was successful, this was used to reform the main gallery into a single image when entering individual building pages. Additionally, I wanted to test the AI's ability to remember previous prompts.

### AI Utilisation notes
- I found the AI the most useful when asked to write small groups of code for certain outcomes or combinations. However doing so requires you to figure out how to integrate the new code into the website, which can be a challenge for HTML. As a result, I continuously asked the AI to seperate HTML and CSS as I found it easier to integrate the sections.
- I was impressed with its ability to remember previous prompts and create new outcomes based on its old prompts, this was useful when adding in an idea later in development.

### Successes

- I believe I successfully implemented the original concept of using type, shapes, placement and colours to push a minimalist presentation of utilitarian/brutalist design.
- Solid commenting on the styles.css files, including good grouping for each component.
- Fine initial use of the AI to create something simple but effective. Navigation is hidden however, exploring the website quickly uncovers how to navigate.

### Improvements

- Further exploration with the green title's typography would likely fix up a slight, awkward feeling in its positioning and font. Additionally, reducing the width of the informational paragraph text on the building focus pages might have made it feel more condensed and inline with the rest of the page structure.
- Experimenting with more complex prompts could have brought interesting ideas into play.