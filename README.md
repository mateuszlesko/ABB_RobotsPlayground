<h1>ABB robot programming playground</h1>
<p>
The porpouse of this repository is to document my progress in doing the course "Welcome to the RobotStudio Video Tutorials Library of University of Skövde!"
</p>
<h2> General information: </h2>
<p>Platform: ABB</p>
<p>Robot Model: </p>

<h2>Table of content: </h2>
<h3>Basics 1: Robot motions:</h3>

<h3>Bacics 2: Jog Robot:</h3>

There are several types of jogs:
<p><i>Jog Joint</i> = move different axes of robot; move only one element</p>
<p><i>Linear Joint</i> = move active tool along the selected coordinate system; move in a straight line</p>
<p><i>Jog Reoriented</i> = rotate the tool center point; useful function for robot interacting with other object for example changing position to avoide collisions with other objects</p>
<p><i>Multi Robot Jog</i> = move several mechanisms at the same time</p>
<b>Every options from Freehand is used when we don't need high accurency!</b> <br>
If high accurency is needed there are other functions:
<p><i>Mechanism Joint Jog</i> = contains a very high detail movement options; we can see TCP coordinates, and set a step which object position will increase or decrease</p>
<p><i>Mechanism Linear Jog</i> = not as accurate as Mechanism Joint Jog, it uses a range inputs to control the position</p>

Joints are located between the links and they are used to control the movements of the links.
I have 7 links, so there I have 6 joints
<h4>Robot structure: </h4>
<h5>Robot Arm</h5>
Links 1 - 3 make up the robot arm
<h5>Robot rist</h5>
Links 4 - 6 make up the robot rist