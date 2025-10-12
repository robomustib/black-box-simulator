# Blackbox Simulator

The Blackbox Simulator is an interactive web-based tool that visualizes and explores cause-and-effect relationships.  
It simulates a *black box* a system where inputs can be observed and manipulated, but its internal logic remains hidden.  
Learners can discover connections between inputs and outputs through experimentation.


---

## Purpose of the Project

This simulator serves as an educational tool for classrooms and workshops to illustrate key STEM and AI-related concepts:

- The black box principle in technology, computer science, and natural sciences  
- Systems thinking: observing input-output behavior without seeing the internal mechanism  
- Experimental learning:  forming hypotheses, testing, and refining  
- Development of problem-solving and logical reasoning skills


## How It Works

1. Inputs (Left Side): Click on one of the input ports (e.g., 1–4) to launch a red ball into the black box.  
2. Outputs (Right Side): Observe which output port (A–C) the ball exits from.  
3. Shake: Randomizes the internal connections between inputs and outputs.  
4. Rotate (90°): Rotates the entire box by 90°, preserving connections but changing orientation.  
5. Show Solution: Reveals the hidden paths between inputs and outputs.  
6. Reset: Creates a brand-new random configuration.  



## Learning Objectives

The simulator helps users understand:
- Hidden system behavior and inference through observation  
- Mapping and pattern recognition between inputs and outputs  
- The foundations of artificial intelligence models, which are often treated as black boxes  
- Easy scientific experimentation: hypothesis → test → observation → refinement  



## Functionality

- HTML, CSS, JavaScript  
- SVG Rendering
- Responsive Design
- CSS Animations



## Features

| Feature | Description |
|----------|-------------|
| Random Path Generation | Every “shake” generates new input-output connections |
| Rotation Control | Rotate the box by 90° to change your perspective |
| Show / Hide Solution | Reveal or hide the hidden connections |
| Interactive Simulation | Click to launch a ball and observe where it exits |
| Responsive Design | Works smoothly on desktop and mobile browsers |



## Demo
Click here to try out:[Blackbox-Simulator](https://www.mustafa-bilgin.de/black-box-simulation)

```bash
git clone https://github.com/robomustib/black-box-simulator.git
cd black-box-simulator
open black-box-simulator.html
```
