---
layout: page
title: Design Manifesto
subtitle: A Reflection
---

# Overview #

I never thought that one day I would ever consider myself as a "designer." Whenever I thought about "design" I thought about aesthetic features of an object, such as colors and material on clothing, or the shiny and sleek architecture of an iPhone. But ever since I started this course Human-Computer Interaction (HCI) everything about my perspective of design changed. I started to see design everywhere, because design isn't just about aesthetics. Design has principles, processes, techniques, and its own philosophy. There is a clear line between good design and bad design. And design becomes more than its functions and abilities -- we start to see the effect that it has, and the consequences that arise when certain aspects are overlooked.

During this semester I had a semester-long project with my classmates Landon and Chris, and created a prototype of something we call [**heART**](https://londonmeanswild.github.io/museum-experience/): a mobile platform that allows curators to connect with visitors and easily understand the vast amounts of data being collected ("*heART makes data useful*"). To best understand what we learned through readings and lectures, we applied the skills and methods of UX design to our own projects. This experience truly opened my eyes to the world of UX design, and why it is starting to become more of a necessity in any scientific and technological aspects. There are five main points I want to share that makes me believe that the world must run on good design:

- Designers should never assume what the users might want and apply these assumptions to their designs,
- Designers should not have to rely on the complexity of a design to accommodate users,
- Designers should always take into open arms critical feedback,
- Designers should consider all types of users, including those that have disabilities, and
- Designers should always keep in mind the Code of Ethics.

Let's dive right in.

### We are not the user. ###

If someone asked me, "What is one thing you've learned from the HCI course?" my answer would be this: we are not the user. This statement, in a designer's perspective, is about how the designer should not assume what a user prefers or understands. A designer for doors, for instance, cannot just put a handle on it and assume a user would know whether to push or pull. Every single choice that a designer makes for a product should be clear and concise.

There were many instances where our group failed to consider this. One of them has to do with how we came up with this idea in the first place.

In our [initial project proposal](https://londonmeanswild.github.io/museum-experience/2018/09/28/initial-proj-proposal/), we proposed that we wanted to develop sort of a "museum data enhancer" by not just putting in information about an artwork, but also how an audience reacted to the artwork, specifically emotional responses:

> "Our vision is to create an application that will allow people to search for art based on emotions and feelings. Our current plan is to help people who are bad at being romantic or expressing their feelings, be better at it through artwork... We will deepen the existing museum database by adding user experiences."

When our focus was shifted from an audience to an actual museum curator, we figured that they would find emotional responses of audiences to be the most useful data when, for example, deciding which exhibit to put up next. So we designed our questions for our contextual inquiries to be about emotional responses of an artwork. However, when we actually did our [contextual inquiries](https://londonmeanswild.github.io/museum-experience/groundwork/research/2018/10/04/CI-writeups/), the curators claimed that

> "...audience/visitor emotion is rarely a criterion for choosing a piece of art since it is so subjective that it is too difficult to use as a measure of art quality. However, she did say one of her goals was to find pieces that invoke intriguing ideas and unexpected discussion points. Therefore, if our design is to aid curators, emotion alone may not be the most helpful data for them."

This made us realize that the data our product collects should not be, for instance, the word "happy" under a JSON property "audience response" in an artwork database. We needed to display information in unique ways that would help curators understand what about the artwork intrigued the audience.

There were other instances when we realized that we are not the user. Our [heuristic evaluations and usability testings](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/) with our first paper prototype gave us a lot of feedback on our design. This table is an overview of all the criticisms we received:

!["Criticisms of our paper prototypes received from heuristic evaluations and usability testings"](https://londonmeanswild.github.io/museum-experience/images/prototyping/usability-feedback-table.png)

Everything from sorting and buttons, which we assumed the users would understand, to functions and displayed analytics, which we assumed users would want to see, were criticized as unclear or unnecessary. Most of the things we assumed about the user were wrong! And that's the takeaway. **Designers think differently about a product they are designing than users that actually use the product.** Users don't have a mind like the designers because they have not thought about generating the idea of the product or have been part of the process of making it -- their only jobs are to use it. I found it personally useful to have a test user be involved in the design process, a UX method called "Participatory Design": one of our testers, an art history professor, suggested key elements to our design that clarified a lot of things, such as what and how data should be displayed and visualized. 

### Keep it simple but functional. ###

What is the difference between our first official paper prototype:

!["First paper prototype"](https://londonmeanswild.github.io/museum-experience/images/prototyping/pp-all-flow.jpg)

and our last one?:

!["Last paper prototype"](https://londonmeanswild.github.io/museum-experience/images/prototyping/final-overview.JPG)

The answer: the number of screens decreased by 33%. We had nine screens in the beginning, and ended with six of them.

Why did this happen? The most obvious answer is that we, the designers, overthought about what the users preferred (relating to my first point above) and how we should accommodate the user so that one can have the most comfortable time possible when using our product. 

Our home page initially had an "All feedback" button, a "Questions and Suggestions" button, and a "Comments" section. Our thought process behind this was that this would allow the users to clearly distinguish the different types of feedback. After our usability and heuristic evaluations, we decided that we could just put everything into the "All feedback" section and have "Questions," "Suggestions," and "Comments" buttons for the user to filter the different types of feedback. This is reflected in our digital mockup, as we have just one button for "View Visitor Responses" in the home page, and buttons for different types of responses on the responses page:

!["Digital mockup: home page"](https://londonmeanswild.github.io/museum-experience/images/prototyping/digital_mockup/home-screen.jpg.png) !["Digital mockup: responses page"](https://londonmeanswild.github.io/museum-experience/images/prototyping/digital_mockup/exhibits-all-responses.jpg.png) !["Digital mockup: questions page"](https://londonmeanswild.github.io/museum-experience/images/prototyping/digital_mockup/questions-all-responses.jpg.png)

The last page shows only questions because the user pressed on the "Questions" filtering button.





3. Keeping it simple but functional
   - Our initial prototype had way more screens and functions to "accommodate" the user
   - We realized that test users would never reach a given goal
        - Confusing buttons, weird layouts, unnecessarily information...
   - We cut it short. Got rid of half the screens. Made the layout simple. Concise, specific information
   - Related to first point: don't assume users need more help than they need...
4. Don't be afraid of feedback
   - Feedback is one of the most important things in designing
   - Personally, I made sure that I got everything done at once instead of taking steps to ensure that I don't get much negative feedback
   - But that led to wasting time and also receiving negative feedback anyways
   - But negative feedback helps us fix our problems, make our design better
5. Make it accessible -- for all types of users
   - We chose very simple colors -- pink and white color scheme, so nothing is too complicated for colorblind users
   - Buttons on reachable positions on the screen so people with mobility problems don't have too much trouble
   - All artworks/exhibits/buttons are labeled for screen readers
   - It's important to accommodate for all sorts of people so that there aren't a lot of problems for a certain type of user
6. Everything has an ethical consequence
   - How much information that we gather are considered private? How much information do we use in general?
   - Our design doesn't cause any harm -- but it's important to keep it in mind
   - ACM Code of Ethics & The Signal Code from Harvard are very useful to constnatly have in mind
   - Personal points of ethics:
        - Citation for using intellectual property of others
        - Privacy and Protection
        - A user's access of their own data is a right
        - Do not harm others
7. Conclusion
