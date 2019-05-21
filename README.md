# Final Project Ichiraku Ramen

## Team Member
1. Ferdinand Jason Gondowijoyo (05111640000033)
2. Jonathan Rehuel Lewerissa (05111640000105)
3. Frandita Adhitama (05111640000129)

## Table of Content
- [Final Project Ichiraku Ramen](#final-project-ichiraku-ramen)
  - [Team Member](#team-member)
  - [Table of Content](#table-of-content)
- [Project Topic : Redesigning monTA (Monitoring Tugas Akhir)](#project-topic--redesigning-monta-monitoring-tugas-akhir)
  - [System Description](#system-description)
  - [What's Bad About The Existing System](#whats-bad-about-the-existing-system)
- [Initial Contextual Inquiry](#initial-contextual-inquiry)
- [Prototyping - Iteration 1](#prototyping---iteration-1)
  - [Sketches](#sketches)
    - [Sketches with Invision (Low Fidelity)](#sketches-with-invision-low-fidelity)
    - [Version Differences](#version-differences)
    - [Selected Sketch](#selected-sketch)
    - [Design Rationale](#design-rationale)
  - [Asummptions](#asummptions)
    - [Hardware](#hardware)
    - [User](#user)
  - [Prototype](#prototype)


# Project Topic : Redesigning monTA (Monitoring Tugas Akhir)
## System Description
![HomePage-Monta](img/HomePage.png)
As an undergraduate in Indonesia, especially in Institut Teknologi Sepuluh Nopember Surabaya, an undergraduate is expected to complete a final assignment, or thesis, to complete their bachelor's degree. A series of steps should be conducted in order to complete this assignment, from the initial proposal of a thesis to the final thesis presentation. This series of steps, however, must be documented and monitored properly in order to properly finish the assignment.  

MonTA *(Monitoring Tugas Akhir)* is a system designed for monitoring the progress of an undergraduate's thesis. The system acts as a platform for students and lecturers to directly monitor their progress on completing their theses. The system also provides a platform for lecturers to promote their research that a student may take in order to complete their thesis.

## What's Bad About The Existing System
Our team have found some problems in the existing system. The first one is about finding information about theses in the system. The current system only provides a limited search capability that does not cover all of the needed information nowdays. The second one is the outdated user interface. The user interface, while functionally sufficient, does not provide a good experience for the users, especially for the first timers.

![SearchPage-Monta](img/SearchPage.png)

In this final project, our teams will look out for the main problems that causes the observations above and propose a solution that hopefully may fix the current problem.

# Initial Contextual Inquiry
[Initial Contextual Inquiry](./INITIAL-CONTEXTUAL-INQUIRY.md)

# Prototyping - Iteration 1
## Sketches
In this section, we are going to make **2** sketches with Invision App.

### Sketches with Invision (Low Fidelity)
- Sketches 1 (Low Fidelity - 1)
![Low-Fidelity-1](img/Low&#32;Fidelity.png)

- Sketches 2 (Low Fidelity - 2)
![Low-Fidelity-2](img/Low&#32;Fidelity&#32;2.png)

### Version Differences
- Sketch 1 :
  In this solution, we completely redesigned the MonTA user interface, starting from the placement of input search, search filters, table columns, and others.

- Sketch 2 :
  In this solution, we only redesigned the UI placement on the old MonTA website.

### Selected Sketch
We prefer solution 1 as the selected sketch. Because the design is simple, easy to be implemented, eye-catching, intuitive, and informative.

### Design Rationale
The main problem with the original website is the limited search capability, which sometimes can make someone frustated while using it. Therefore, we are trying to design a system with a better search capability.

## Assumptions
### Hardware 
1. Screen size : 15.6 inch
2. Screen resolution : higher that on equal to 1377 x 768 with ration 4:3 with color space RGB.
3. Computer with minimum requirement :
- Intel Dual-Core
- Intel HD Graphic
- 2 GB RAM
4. Using physical buttons (mouse / keyboard) or touch screen
5. Web browser available

### User
1. Familiar using web browser
2. User have medium-high experience on it.
3. Age ranged from 17 - 50 years old.
4. Student of Informatics Department.

## Prototype
This prototype is built using `react` as the main framework. In order to make this prototype work, please type this on terminal
```bash
sudo npm install -g serve
serve -s monta-prototype-1
```
After that visit : `http://localhost:5000` for demonstration.
Source of this prototype can be found in this [link](monta-prototype-1/)