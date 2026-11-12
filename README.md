# Is the Jedi Force Pull Method Effective? Evaluating Eye-Tracked Object Grabbing in VR
A virtual reality research project comparing eye-tracked object interaction with distance-hand and close-up grabbing techniques.

Authors: Naznin Sharmin Shishir and Richard Zhao
Publication: Proceedings of the 20th International Conference on the Foundations of Digital Games (FDG '25)
DOI: 10.1145/3723498.3723695

## Project Overview
This project investigates whether eye tracking can make selecting and grabbing distant objects in virtual reality faster and easier than hand-based interaction.

It compares three interaction techniques:
- Eye-Tracked (ET): The participant looks at a distant object to select it, then uses a pinch gesture to bring it to the hand.
- Distance Hand (DH): The participant reaches toward a distant object to select it, then uses a pinch/grab gesture.
- Close-Up (CU): The participant moves closer to the object and grabs it using a natural close-range interaction.
The study evaluates interaction time, mistakes, participant preferences, and perceived workload.

## Research Objectives
- Evaluate whether eye-tracked object selection improves interaction speed in VR.
- Compare eye-tracked interaction with distance-hand and close-up interaction.
- Measure selection time and selection-and-grab completion time.
- Examine interaction mistakes, participant preferences, and perceived workload.

## Experimental Study
The study involved 21 participants who completed three object-interaction tasks: color, size, and shape.

Each task was evaluated using all three interaction techniques: ET, DH, and CU. The study measured selection time, selection-and-grab completion time, mistakes, participant preferences, and workload using the NASA Task Load Index (NASA-TLX). Task order was randomized, and participants completed a practice session before the study tasks. Each session lasted approximately 60 minutes.
## Key Findings
Object selection time
Eye-tracked interaction was significantly faster than distance-hand interaction for object selection in all three tasks.
Task	Eye-Tracked (ET)	Distance Hand (DH)
Color	10.16 s	20.64 s
Size	9.48 s	16.92 s
Shape	8.07 s	16.24 s


## Selection-and-grab completion time
Eye-tracked interaction had the lowest average completion time across the three techniques.
Task	Eye-Tracked (ET)	Distance Hand (DH)	Close-Up (CU)
Color	14.20 s	23.52 s	25.78 s
Size	13.46 s	18.44 s	22.54 s
Shape	12.62 s	18.22 s	23.31 s


## Mistakes and participant feedback
- Close-up interaction produced the fewest mistakes overall.
- 19 of 21 participants agreed that interacting with 3D models was easier with eye-tracked interaction.
- 19 of 21 participants believed the tasks took the least time with eye-tracked interaction.
- Eye-tracked interaction received the lowest average NASA-TLX ratings across all six workload factors. Physical demand, effort, and frustration were significantly lower.
- 12 participants reported feeling less confused when using eye-tracked interaction.
Overall: The findings suggest that eye-tracked interaction can improve the speed and perceived ease of distant object interaction. Close-up interaction, however, produced fewer mistakes; eye tracking should therefore not be described as the most accurate technique overall.

## Technologies and Tools
- Unity
- C#
- Meta Quest Pro
- Oculus Integration SDK 57.0.1
- Eye tracking and hand interaction

## Running the Project
The publication identifies Unity, C#, Meta Quest Pro, and Oculus Integration SDK 57.0.1 as project technologies. The exact Unity Editor version and full setup procedure are not specified here.

## Setup instructions:
1. Install the Unity Editor version used to develop the project.
2. Set up the required Meta Quest development environment and device permissions.
3. Install or import the required Oculus integration packages, subject to their license terms.
4. Open the project in Unity.
5. Build and deploy to the supported Meta Quest headset.
Verify these steps on a clean checkout and replace this outline with the exact versions and configuration used. If publishing research documentation only, state that the Unity source project is not included.

## Limitations and Future Work
The study involved a relatively small university sample and a limited set of tasks in simple environments. Future work could include more diverse participants, more complex interactions and environments, and additional interaction approaches such as speech-based and fully hands-free interaction.
## Publication and Citation
Shishir, N. S., & Zhao, R. (2025). Is the Jedi Force Pull Method Effective? Evaluating Eye-Tracked Object Grabbing in VR. Proceedings of the 20th International Conference on the Foundations of Digital Games (FDG '25).

Read the published paper

Please cite the published paper when referring to the research findings.
