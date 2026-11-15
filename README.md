# Hand Gripper

🦾 Designing a gear-driven gripper from scratch in Autodesk Fusion

I wanted to learn CAD by building a real mechanism, not just a single part. So I designed this two-finger gripper where meshing gears and linkages work together to open and close the jaws.

How it’s built:
⚙️ Gears: meshing spur gears synchronize the motion, so both sides move together
🔗 Connector links + pins: these turn the gear rotation into the jaw movement
🧱 Frame: holds everything in position
🪞 Mirrored parts: I modeled one side and mirrored it, which keeps the design symmetric and saves time

The final assembly has separate parts (Frame, Gripper, Connector, Gear, Pin) connected with joints, so I could test whether the mechanism really moves before building anything physical.

The biggest lesson: in mechatronics, a mechanism that looks right isn’t enough. It has to move right. Joints and tolerances decide that.

Next: I want to add an actuator (a servo or stepper motor), connect it to a controller, and maybe 3D print the gripper to test it for real. 🚀

You can find and download my Hand Gripper design drawing file(.PDF), design file(.DXF) and for 3D printing(.STL) file tool.I hope it may helpful.
