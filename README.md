# Traffic Light Controller with Emergency Override

## 1. Project Overview

The Traffic Light Controller with Emergency Override is a digital system designed to manage traffic signals efficiently while prioritizing emergency vehicles and pedestrian safety.

The system uses a **Finite State Machine (FSM)** to control traffic signal transitions. It provides normal traffic sequencing, pedestrian crossing support, and an emergency override mechanism that allows emergency vehicles to pass safely.

## 2. Objectives

- Automate traffic signal sequencing.
- Reduce traffic congestion through systematic signal control.
- Provide priority to emergency vehicles.
- Include pedestrian crossing functionality.
- Improve traffic management and road safety.
- Implement the control logic using an FSM-based architecture.

## 3. Features

- Automatic traffic light sequencing.
- Emergency vehicle detection and priority handling.
- Pedestrian crossing request support.
- Controlled state transitions.
- Timer-based signal delays.
- Safe transition between traffic signal states.

## 4. System Architecture

The system consists of the following modules:

1. **Finite State Machine (FSM):** Controls the overall operation and transitions between traffic states.
2. **Traffic Signal Controller:** Manages RED, YELLOW, and GREEN signals.
3. **Emergency Override:** Detects emergency requests and provides priority.
4. **Pedestrian Controller:** Handles pedestrian crossing requests.
5. **Timer/Delay Controller:** Controls the duration of each traffic signal.

## 5. FSM Design

The project follows a **Moore Finite State Machine** approach.

In a Moore machine, the output depends only on the present state and not directly on the input.

This approach provides predictable output behaviour and simplifies traffic signal control.

## 6. Working Principle

1. The controller starts in its initial traffic signal state.
2. Traffic signals change according to predefined timing intervals.
3. When an emergency request is detected, the controller prioritizes the emergency vehicle through the override mechanism.
4. Pedestrian requests are processed according to the designed control sequence.
5. After completing the priority operation, the controller returns to normal traffic operation.

## 7. Technologies Used

- Hardware Description Language: Verilog HDL
- Design Methodology: Finite State Machine
- FSM Type: Moore Machine
- Simulation Tool: [Add simulation tool]
- Implementation Platform: [Add FPGA board, if applicable]

## 8. Simulation and Verification

The design can be verified using simulation by testing:

- Normal traffic signal transitions.
- Emergency vehicle activation.
- Pedestrian crossing requests.
- Timer-based state transitions.
- Reset operation.
- Correct signal outputs during different operating conditions.

## 9. Applications

- Smart traffic management systems.
- Emergency vehicle prioritization.
- Intelligent transportation systems.
- Pedestrian-friendly traffic intersections.

## 10. Future Enhancements

- Integration with real-time vehicle detection sensors.
- Multiple-intersection coordination.
- IoT-based traffic monitoring.
- Adaptive traffic signal timing.
- GPS-based emergency vehicle detection.

## 11. Conclusion

The Traffic Light Controller with Emergency Override demonstrates an FSM-based approach to intelligent traffic signal management. By incorporating emergency vehicle priority and pedestrian crossing support, the system aims to improve traffic efficiency, safety, and reliability.

---

**Project:** Traffic Light Controller with Emergency Override  
**Domain:** Digital Electronics and VLSI Design  
**Design Approach:** Moore Finite State Machine
