# 🤖 *PRO 2025* | **Project Namnama**

### *Engineering the future, driven by hope* — we are Team B of PCLU SiribTech Future Engineers.

# Lists of Contents
- [1. Introduction](#1-introduction)
    - [1.1 About Us](#11-about-us)
    - [1.2 Team Management](#12-team-management)
    - [1.3 Reasons to Participate](#13-reasons-to-participate)

# 1. Introduction   
## 1.1 About Us

<div align="center">
    <img width=80% src="t-photos/TEAM B ROBOTICS FE.jpg"></img>
    <h3 align="center"> Team's name: <i><b>SiribTech</b></i> | Car's name: <i><b>Namnama</b></i> | Match Name: <b><i>A Self-Driving Car Challenge</i></b> </h3>
</div>

| Name | Age | Role | Socials | Fun facts: |
| :---: | :---: | :---: | :---: | :--- |
| Aliana Marie L. Marquez | 16 | Robot Builder and Prototyper |  <a href="https://facebook.com/aliana.marquez.165" target="_blank">@aliana.marquez.165</a> | A hobby that I enjoy doing the most is sketching during my free time or whenever I am bored. I also like to entertain myself sometimes by playing online games. |
| John Kenneth P. Valbuena | 16 | Robot Programmer and Technical Writer | <a href="https://facebook.com/kntheen04" target="_blank">@kntheen04</a> | I play sports. One of my most cherished sport is Volleyball. I spend most of my time on my computer since I am very interested in ICT. |
| Kryztal Gale R. Rivera | 15 | Robot Builder and Technical Writer | <a href="https://facebook.com/cryztkjlr" target="_blank">@cryztkjlr</a> | I sing, I write, and in my free time/days, I play badminton. I am fascinated about exploring and diving into new stuff. |

## 1.2 Team Management
With curious minds, small steps fueled by creativity and teamwork, our project is the result of our team's joint endeavor. As students from <a href="https://facebook.com/PCLUBasicEducationDepartment" target="_blank"><b>Polytechnic College of La Union (PCLU)</b></a> representing the Robotics Club in the category of Future Engineers, we applied our knowledge and skills in designing, building and programming a robot that emphasizes on creating innovative robot solutions. Throughout this journey, we learned the importance of perseverance and considering our own capabilities in doing such tasks to create a successful project.<br><br>
Team Supervisor: **Kryztal Gale R. Rivera**<br>
Team Coach: **Bong John Abraham Agno** & **Michael James Estipular Ergino**

## 1.3 Reasons to Participate
For us, this project is more than just fighting for an honorable spot in the world of Robotics. It is more than just a competition. Here, we've indulged ourselves in discovering our fullest potentials by taking little steps and moving onto greater heights with full confidence and by enjoying the flow of the process. We've created a robot knowing it'll soon serve its purpose in the future.<br><br>Being a part of this Olympiad made us realize how great it is to seek answers or solutions for worldwide problems. The process also helped us realize how we should manage our talents/skills in the scope of Robotics. It is truly fascinating how a person can discover—such things about themselves while trying to discover for other people too.

# 2. Abstract / About the Car

## 2.2 Flow Diagram
> [!NOTE]
> For a comprehensive overview of the system’s configuration, including open and obstacle diagrams, wiring diagrams, and schematic representations, please refer to the contents of the [schemes](/schemes/) directory.


```mermaid
flowchart TD
    A("Start: Initialization of
    motors and sensors") --> B("Run constant loop")
    B --> C("Drive straight")
    C --> D{"Check what direction
    to turn"}
    D -- Orange Line --> E["Clockwise turn"]
    D -- Blue Line --> F("Counter-clockwise turn")
    E --> G("Lap counting")
    F --> G
    G --> H("Remain distance
    from the wall")
    H --> I{"Detect obstacles"}
    I -- Green --> J("Go to left")
    I -- Red --> K("Go to right")
    J --> G
    K --> G
    G --> L("Stop to starting positon")
    L --> M("End program")
```
