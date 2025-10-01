# Here is what the class is going over from Oct 1 until about Oct 15th

## Fusion360
Every student has an Autodesk Student account that they can access from home.  This will allow them to login/download/install Fusion360

Autodesk Link = https://www.autodesk.com/education/edu-software/overview?sorting=featured&filters=individual

## 1) Control Knob = https://www.youtube.com/watch?v=apkUQKNwHIo&authuser=0
Timeline = 1 days
## 2) Lego Block = https://www.youtube.com/watch?v=DrLOPJq_stc&authuser=0
Timeline = 2 days
Underside Sketch - This one is tricky, make sure you selected the underside face and not the top of the block accidentially.
## 3) Bird House = https://www.youtube.com/watch?v=58epiN-Ki58&authuser=0
Timeline = 1-2 days
## 4) Snap Fit = https://www.youtube.com/watch?v=E0NVC8xhf3I&authuser=0
Timeline = 2-3 days
    You will also need to download a Raspberry Pi 4 Model B File
    OPENING .F3D FILES

* Step 1 - Download the .f3d file
* Step 2 - Open it in Fusion360, and save it within fusion.
* Step 3 - Back in your Untitled tab, save the empty Untitled tab.
* Step 4 - If the above steps have been done correct, Make sure the Untitled Tab is highlighted, when you right click on the .f3d file on the dashboard (left side), and select Insert Into Current Drawing, it should bring in the Raspberry Pi model as one large component to position and rotate as needed.
* Step 5 - You'll probably notice it appears on its side, so rotate the board 90 degrees to lay the green side face-down.  Press [OK].
## 5) Nuts n' Bolts = https://www.youtube.com/watch?v=Xho87HJ-XDo&authuser=0   and https://www.youtube.com/watch?v=aGWrFeu8Hv0&authuser=0
Timeline = 1-2 days
### Part 1 - Hex Nut
Using the Hole command instead of the thread command, you are able to cut the hole and thread it in one step.  It has the added advantage of including the tap settings you would use the make the hole.  This method is recommended for those threads that will have real screws or real nuts attached to them.

### Part 2 - Screw and Nut
This part is less about making the threads and more about making threads that work with each other.  When you create threads in a model and then 3D print it, the accuracy of the print will make a cold-forged nut with a rolled thread often bind.   This difference in manufacturing process is less than ideal, but as designers we can account for this by tweaking the gaps and edges to increase the allowance/spacing for the nut to thread on.
## 6) Black Pipe Lamp = https://www.youtube.com/watch?v=JFJwadAK6pw&authuser=0
Timeline = 2-3 days
        Don't worry about the bulb until you return to class.  Watch out for the grounding of a component, remember you can always undo, and redo groundings.
        McMaster-Carr
Using premade factor components is great, especially when you have the ability to order them directly from McMaster-Carr.   If you need multiple copies of a part, don't import multiple copies.  Instead import the first and then when you need a second, just copy their first.  This is done by selecting the part and pressing Move, then make sure the XYZ movement is selected, and then select the Create Copy and move the part a little.  From there you free to move it around and place it where it needs to go.  

**Moving and Aligning**
With premade parts, its important to move and align carefully.  Eyeballing is too risky and often frustrating later.  When moving a component, if you mouse over the part and hold down Ctrl, you'll have the ability to click on special points (i.e. origin of circles).  Select the point on the part you want to move, and then the point on the part you want to end up at.  It should move and align for you.

**Drawings and Parts Lists**
If you followed the above process correctly, you will now have multiple copies of the exact same part.   This will pay off when you go into Drawing and insert a Part List.  There it will show quantities of a single part instead 2+ instances of the same part.
## 7) Surface Modelling = https://www.youtube.com/watch?v=NypRE2aFhh4&authuser=0
Timeline = 2 days
In this challenge you will tackle either the water bottle or the spark plug.  In both cases we are starting with a canvas, which is a 2D picture of the object that will be used as a guide to create the 3D model.  The best pictures are those that are profiles (front, side, top) of the object so that they can be placed in the workspace at 90 degrees to each other.  Any other pictures have their use as concept photos, but be cautious using those as your basiss to create a 3D model.

### Option 1 - Water Bottle (Surface Model)
Use the included .jpg file to follow along with the tutorial

#### TROUBLESHOOTING
Reverse Faces - If you need flip the faces to fix an issue, try Patch > Modify > Reverse Normal
Sometimes there are unforseen results from a standard action and sometimes you follow the tutorial perfectly only to find out that your results are not what the tutorial is showing.  Here are some "weirdnessess" that happen and how we fixed them.

    Stitching - Your model isn't becoming solid afterwards because there is a seam somewhere that is still showing red despite having the tolerance up at 10.00mm.  
