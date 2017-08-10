# EN.601.714: Advanced Computer Networks

## Logistics

- Instructor: [Xin Jin](http://www.cs.jhu.edu/~xinjin/)
- Teaching assistants: ?
- Lecture time: Tuesday and Thursday, 1:30-2:45pm
- Location: 228 Malone Hall
- Office hours: Tuesday 3-4pm
- Credits: 3 credits
- Area for MSE and PhD requirements: Systems

## Course Description

This is a graduate-level course on computer networks. It provides a comprehensive overview on advanced topics in network protocols and networked systems. The course will cover both classic papers on Internet protocols and recent research results. It will examine a wide range of topics, e.g., routing, congestion control, network architectures, datacenter networks, network virtualization, software-defined networking, and programmable networks, with an emphasize on core networking concepts and principles. The course will include lectures, paper discussions, programming assignments and a research project.

## Prerequisites

One undergraduate course in computer networks (e.g., EN.601.414/614 Computer Network Fundamentals or the equivalent), or permission of the instructor. The course assignments and projects assume students to be comfortable with programming.

## Announcements

- Monday, August 7: Welcome to the course.

## Course Syllabus

| Date    | Topics  | Readings | Notes   |
| :------ | :------ | :------  | :------ |
| | **Classics** | | |
| Tue 09/05 | Course Overview | How to Read, You and Your Research | |
| Thu 09/07 | End Host | Packet Switching, E2E Argument | |
| Tue 09/12 | Control Plane | Design Philosophy, E2E Routing Behavior | |
| Thu 09/14 | Data Plane | Click, 50Gbps Router, RMT/P4 | |
| Tue 09/19 | Overlay Networks | Chord, CAN, Pastry | Tapestry |
| Thu 09/21 | No class, but work on assignment 1 and forming groups | | Assignment 1 due Mon 09/25 |
| | **Datacenter Networking** | | |
| Tue 09/26 | Datacenter Architectures | VL2, PortLand, Jupiter Rising | |
| Thu 09/29 | Optical Datacenters | Helios, FireFly, ProjecToR | |
| Tue 10/03 | Resource Allocation | DRF, Carbyne, Varys | |
| | **Congestion Control** | | |
| Thu 10/05 | Datacenter Congestion Control | DCTCP, PDQ, pFabric | |
| Tue 10/10 | RDMA | DCQCN, RoCEv2, Design Guidelines | |
| | **Software-Defined Networking** | | |
| Thu 10/12 | SDN Control Plane | Ethane, ONIX, FlowVisor | |
| Tue 10/17 | Wide Area Networks | B4, SWAN, OWAN | |
| Thu 10/19 | Traffic Engineering | BwE, FFC, Footprint | Project Proposal due Mon 10/23 |
| Tue 10/24 | Network Update | Abstraction, zUpdate, Dionysus | |
| | **Network Verification** | | |
| Thu 10/26 | No class, but work on assignment 2 | | Assignment 2 due Mon 10/30 |
| Tue 10/31 | Data Plane Verification | HSA, VeriFlow, Delta-net | Mutable |
| Thu 11/02 | Control Plane Verification | BatFish, Propane, Mineseeper | |
| | **Network Measurement** | | |
| Tue 11/07 | Network Telemetry | NetSight, EverFlow, Pingmesh | |
| Thu 11/09 | Sketch | OpenSketch, UnivMon, SketchVisor | |
| | **Middleboxes** | | |
| Tue 11/14 | Frameworks | SIMPLE, E2, NetBricks | |
| Thu 11/16 | Load Balancers | Ananta, Duet, SilkRoad | |
| Tue 11/21 | Thanksgiving Vacation | | Gobble, gobble! |
| Thu 11/23 | Thanksgiving Vacation | | Gobble, gobble! |
| | **Networking for Big Data** | | |
| Tue 11/28 | Distributed Storage | IOFlow, SwitchKV, NetCache | |
| Thu 11/30 | Wide Area Analytics | JetStream, Iridium, Clarinet | |
| Tue 12/5 | Performance Modeling | Ernest, CherryPick, PARIS | |
| | **Project Presentations** | | |
| Thu 12/7 | Talks by project groups | | Project Report due Mon 12/11 |

## Assignments

- [Assignment 1](assignments/assignment1.md): Use iperf3 and wireshark to explore TCP.
- [Assignment 2](assignments/assignment2.md): TBD.

## Project
- Final project: Novel research with a system-building component  - Open-ended research problem  - Can work alone or in small teams, i.e., 1-5 people  - Must involve writing some software  - Idea: Come up with your own, or talk to me- Can overlap with other projects, with permission  - Undergraduate research projects  - PhD qualifying research projects- Deliverables  - Two-page short proposal: Oct 23  - Project presentation: Dec 7 (last class)  - Six-page final report: Dec 11

## Policies

### Academic Integrity Policy

This course strictly enforces the university and department policies on academic integrity. The details can be found on the [department website](https://www.cs.jhu.edu/academic-integrity-code/).

### Late Policy

25% off for each 24 hours late, rounded up

## Grading

- Class participation: 10%
- Paper reviews: 20%
- Homework assignments: 30%
- Project report and presentation: 40%

