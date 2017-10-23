Sobel Sight
===
Browser based real time edge detection in VR video pass-through, for the visually impaired

Early demo: https://danruta.co.uk/sobel

---

In 2011, the world health organization determined that there are 246 million people who have low vision (Pascolini D, M. S., 2011). Navigation and pathfinding are issues they have to deal with every day. Solutions include sonar devices, canes, and carers.

On the web, people with low vision can turn on high contrast mode, to ease the strain and increase the detail perceived.

What if we took that concept and applied it to their lives outside of web surfing?

Sobel sight is a small experiment that sets out to explore and implement a system to help give visually impaired people a new perspective on life.

---
Pascolini D, M. S. "Global estimates of visual impairment." British Journal Ophthalmology, 2011, Accessed 10 Aug 2012.


#### To develop
There are currently two versions. A vanilla JavaScript version and a WebAssembly version. ```npm install``` the dependencies and run grunt to compile/minify into the dist folder. You must first install emscripten to develop the WebAssembly version.

#### To run
There is a demo ```index.html``` file included. You must serve this via the included ```server.js``` file which you can start with node.js.