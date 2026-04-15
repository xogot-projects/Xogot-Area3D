# Area3D & Signals (Xogot 3D Tutorial)

This project contains the example scenes and assets used in the  
**Xogot 3D Modular Series – Area3D & Signals** tutorial by **Erin Uptegrove**.

It demonstrates how to use **Area3D** in **Xogot** — the iPad and iPhone port
of the Godot Engine — to detect when objects enter or exit a trigger zone, and
how to connect those events to scripts using **signals**.

The project includes a practical example of a “fall sensor” in a platform
scene, along with simple scripts that print debug output and reload the current
scene when the player enters the area.

---

## Features

* Add and configure an **Area3D** node in a 3D scene  
* Use **CollisionShape3D** to define an Area3D trigger zone  
* Understand how Area3D works like a sensor  
* Connect **body_entered** and **body_exited** signals to scripts  
* Use signals to let nodes communicate cleanly  
* Follow the “**call down, signal up**” scripting approach  
* Print debug output when a body enters an area  
* Reload the current scene when a trigger is activated  
* Preview trigger behavior directly in example scenes  

---

## Notes

This project focuses on **Area3D setup and signal-based interactions**, not
advanced gameplay systems.

Key ideas demonstrated include:

* Area3D tracks what enters and exits its collision space  
* Area3D can be used for triggers, portals, hit boxes, hurt boxes, and goal zones  
* An Area3D does not need a visible model to function  
* Signals are a clean way for nodes to communicate  
* Local scene signals are a good foundation for more advanced game logic  

---

## Video Tutorial

Watch the full walkthrough on the [Xogot YouTube Channel](https://youtube.com/@xogot):

**Area3D and Signals in Xogot – Game Development in Godot on iPad**  
https://youtu.be/GmH1RmXieZQ

---

## How to Use

1. Download or clone this repository:

   ```bash
   git clone https://github.com/xogot-projects/Xogot-Area3D.git

2. Open the project in [Xogot](https://apps.apple.com/us/app/xogot-make-games-anywhere/id6469385251) on iPad or iPhone.

3. Explore the example scenes

4. Preview the project and test the Area3D trigger behavior

5. Review the scripts connected to the Area3D signals

## Learn More

[Xogot](https://xogot.com)
[Documentation:](https://docs.xogot.com/documentation/xogot/)
[Tutorials](https://docs.xogot.com/tutorials/xogot-tutorials/)

Built with Xogot on iPad