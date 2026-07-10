# Mechanical Wings Journal

## Project Overview

**Project:** Mechanical Wings  
**Design Time:** Approximately 42 hours  

This journal documents the design process behind the development of my wings. During this, I researching existing mechanisms, developed a functional concept, selected materials, planned the mechanical movement system, and learned about how the wiring works. The goal of the project was to create a pair of wings that could mechanically open and close through motorized movement.

## Research and Initial Analysis (10 hours)

As I started this project, I went online and looked up as many tutorials and resources as I could about existing motorized wings. I'm a beginner in hardware, and I honestly had no idea how to start the design by myself. I learned about how people made their structure for their wings, and I also took a look at the engineering principles behind their wing movements. 

These are a few of the notes I made as I watched and read these tutorials.
<img width="715" height="336" alt="image" src="https://github.com/user-attachments/assets/23e4b03b-f943-4429-ab63-d60761a058c1" />

I took a lot of notes as I went through all of the tutorials (almost 3 pages worth!), but a lot of them can only be understood by me. This took me about 5 hours.

As I was looking through tutorials, one caught my eye. Willow Creative had made a build log, which was not actually a tutorial but I could see that she documented her work very well. Most of the wings I had seen were stationary: they could only move up and down, and they were very limited in motion. However, hers were a lot different. The way her wings were structured made it so that not only could her wings flare and retract really well, but they could also imitate flapping motions (with manual input). I absolutely loved this design, and I knew this was the one I was going to make. 

I mainly used her build log as a reference for how wearable wings could be structed. I also took some information from techniques other people used, since I was trying to figure out how I was going to make my own wings. I had to do an indepth study into how linear actuators worked, what pivot mechanisms were, how linkage systems transferred motion, and how different types of materials affected motion. This also took me about 5 hours.

One of the main challenges I had was with understanding how linear actuators could be used for the wings. I saw how linear actuator could only move in a straight line, while wings required a rotational motion to open and close. Studying mechanical linkages and pivot points took a long time, since it took me a while to understand how these motions worked. Eventually, I worked out how the wing structures could transfer the actuator’s movement into a larger wing motion. I also read a lot about how wing size and weight have a major effect on the amount of force required because wings act as large levers. The farther the weight extends from the pivot point, the greater the torque required to move and support the wings.

## Concept Development and Mechanical Planning (6.5 hours)

After researching existing designs, I came up with multiple mechanical concepts for creating the wing movement. Some involved placing the linear actuator at the side of the wings, and others were mainly me experimenting with the wing structure. I spent around 2 hours trying to experiment with designs.

In the end however, I did fall back onto the design I saw in Willow Creative's log. It was extemely well done, and I couldn't come up with anything better. I spent about 4 hours fully studying her design and what she did. I did experiment around with her design itself and how she did it, but it was hard because I needed the physical materials with me to figure out if the designs could actually work.
<img width="822" height="538" alt="image" src="https://github.com/user-attachments/assets/c3b9d3a5-cd8b-4021-88fb-7aa2c6d68bcc" />
I took a few pictures of her design and put them in a whiteboard for me to work on. Here, I looked at the extreme specifics of how her design worked. I tried to figure out exactly how the motion transferred through her wings and why they specifically retracted to the position they were in. I tried to see if I could improve the design a little by figuring out how to make the wings retract even more so they could be compact. I came up with a few solutions with a friend, one of which being the gas springs were blocking the wings from going down. When I get to building them, I'm going to test this theory out. I also wanted to see if I could either angle some of the pipes different or add a few extra pipes to the wings. I wanted to make the wings have more plumage, since I felt like they would look better if they were more filled out. It was hard to see if this was possible on paper, so I'm going to also see if I can do this once I get my materials in real life.

For about an hour, I cross-referenced all my notes and tutorials to come up with some main design points. The wings needed to be wearable, capable of symmetrical movement, controlled remotely, lightweight enough to carry, and constructed from materials that were accessible and easy to modify. This took about half and hour.

## Structural Design and Hardware Planning (9.5 hours)

Here is where I put in the most amount of time. I started to actually sketch what I wanted to build. Although I thought this would be easy, it was not.

<img width="3000" height="2402" alt="image" src="https://github.com/user-attachments/assets/935c4751-e57e-4ed0-bb7e-e92e0cad489f" />
<img width="3011" height="2370" alt="image" src="https://github.com/user-attachments/assets/dbe91e1f-7ed7-438b-835a-6bccceae2687" />

THese designs were the first ones I worked on. These were done in tandem because I constantly had to reference the other to see if what I was drawing was correct. I went through a lot of different versions of them, and they had to be redrawn constatnly because I kept angling either the pipes wrong or the little trianglar plate at the top wrong. I heavily referenced all of my notes on linkages while making these. I didn't make them to scale, but I did try to keep the sizing of the pipes on the frame consistent. In total, these sketches honestly took about 6 hours to make. 

While making these designs on paper, I also thought a lot about the materials I wanted to use for this project. I needed a lightweight but durable frame. I eventually decided on PVC tubing after some recommendations from others, mainly because it is affordable, easy to cut, lightweight, and readily available. ABS plastic was selected for the mounting plate because it provides a stronger and flatter surface for attaching mechanical components while remaining lightweight.

I decided to attach the pipes together using M6 bolts, washers, and lock nuts. A lot of people used these in the tutorials I referenced, so I researched about these and found out that they were the best option. The washers help reduce friction between moving components while also distributing pressure across the PVC. Lock nuts were selected instead of standard nuts because the wings will experience repeated movement and vibration, which could cause regular nuts to loosen over time. I may use switch back to standard nuts when I actually get the materials if I need to. It took me about 2 hours to research and see what I could do for this.

I also made a version of the wings with plumage, so people could see how the wings would look in real life. This took me about 1.5 hours, mainly because I made half of the sketch during my earlier versions of the previous sketches. I had to change a lot of the pipe positions.
<img width="3280" height="2104" alt="image" src="https://github.com/user-attachments/assets/0639d1ce-cff5-4658-8ea8-ab9bb3e46a1d" />

## Electrical Planning (7.5 hours)

<img width="3232" height="1848" alt="image" src="https://github.com/user-attachments/assets/92bfb86d-0da2-4b9f-8d4e-d7d02e4ee84e" />

I had to learn how to make wiring diagrams from scratch here, and it took me about 3 hours to do so. 

The electrical system was designed to power and control the two linear actuators. The selected system consists of a 12V rechargeable battery, a wireless two-channel motor controller, and two 12V linear actuators.  A linear actuator contains a DC motor, meaning its direction changes depending on the polarity of the electricity supplied. When the controller sends power in one direction, the actuator extends. When the polarity is reversed, the actuator retracts. This allows the remote control to operate the wings without manually changing any wiring.

While doing this, I also had to figure out how I'd go about wiring the whole thing. I have zero experience with wiring, so I had to talk to a lot of people and do a lot of research on how to wire stuff. I figured out that I'm going to need to use cables to connect the DC motor to the battery and the linear actuators. I'm going to have to connect wires through a screw terminal to connect the battery and the DC motor, and I'm going to have tol solder wires together to connect the linear actuators and the DC motor. This honestly took me about 4.5 hours to figure out because I was starting from scratch with no knowledge about this topic. I had to learn a lot about the different ways to wire something.

## Material Selection and Final Design Planning (5 hours)

I spent a lot of time choosing what to purchase for my project. Since I'm on a time constraint, I have to use amazon for all my stuff, which severely limits my selection of items. 

I took about 1.5 hours to make a list of everything I needed. This took me a long time because along with materials, I had to think about the different tools I may need for this project. I'm a total beginner in hardware, so I don't really have any tools I may need to make my project at home currently.

Finding all of the items and where I could get them from took me around 3.5 hours. I had to compare and contrast a lot of brands when trying to buy tools while also looking for the cheapest items. Finding materials was also hard because a lot of them shipped too late, so I had to settle with questionable items. I didn't have much trouble buying electronics, but buying things like cloth took me a long time to figure out.

## Final Design Summary + Additional Concepts (3.5 hours)

I had finally finished my whole design concept, which consisted of a wearable backpack-mounted animatronic wing system powered by two 12V linear actuators. The mechanical system used PVC tubing, ABS mounting components, and linkage mechanisms to create controlled wing movement. The electrical system used a rechargeable 12V battery, wireless motor controller, and actuator system to provide remote operation. I made a few detailed sketches online to truly showcase the final design.

<img width="3011" height="2370" alt="image" src="https://github.com/user-attachments/assets/96791c53-0d14-4234-916f-9a0e0fa12ec9" />

These sketches took me around 3 hours to make.

I also felt as though I wanted to add additional features to my design.
<img width="864" height="555" alt="image" src="https://github.com/user-attachments/assets/a8c48657-1e41-4e30-a203-d4bd0fe7d041" />

<img width="533" height="401" alt="image" src="https://github.com/user-attachments/assets/89aad141-6c0b-4cbd-9399-36e70967182a" />

I made these two concepts, which I'm going to implement in real life if I get the time. I'm also going to be experimenting a lot more with the structure and general placement of the rods once I get my supplies. These took me about half an hour to do.




