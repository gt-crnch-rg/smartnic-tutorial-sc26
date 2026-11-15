# In-Network Computing with SmartNICs for HPC Applications

Tutorial on SmartNICs for Supercomputing 2026

**Held on**: Sunday, November 15, 8:30 AM - 5:00 PM Central Standard Time; Room W193b

[Event website and Program](https://sc26.conference-program.com/presentation/?id=tut161&sess=sess175)

![Chicago River](fig/chicago_river.jpg)

## Audience Tutorial Survey

Please fill out the this short (3 question) attendee survey here in addition to the ISC survey. This survey will let you give us direct feedback and follow up for future SmartNIC-related opportunities!

- [SC 2026 Survey](https://submissions.supercomputing.org/?page=SessionEval&new_year=sc26&id=sess175&eval_stype=stype185)
- [DPU Tutorial Content Feedback Survey](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=u5ghSHuuJUuLem1_Mvqgg82dnXP1iqRHvc472TcBXahUQ0lXWTRJMUFHMTJNUFFMS08yVFRGQ01PQy4u)

## Presenters

* Elie Kfoury [(University of South Carolina)](https://sc.edu/study/colleges_schools/engineering_and_computing/faculty-staff/elie_kfoury.php)
* Jeffrey Young [(Georgia Institute of Technology)](https://crnch-rg.cc.gatech.edu/)
* Richard Graham [(NVIDIA)](https://www.nvidia.com/)
* Antonio Peña [(Barcelona Supercomputing Center)](https://www.bsc.es/pena-antonio)
* Paul Ruth [(University of North Carolina at Chapel Hill)](https://www.unc.edu/)
* Jorge Crichigno [(University of South Carolina)](https://sc.edu/study/colleges_schools/engineering_and_computing/faculty-staff/jorge_crichigno.php)
* Jennifer Kim [(Internet2)](https://internet2.edu/)

**Abstract:** The past few years have witnessed an increased level of support for and deployment of programmable network adapters, known as "SmartNICs." These enhanced network devices offer standard packet processing capabilities as well as advanced "in-network" computing features built around programmable lightweight processing cores, FPGAs, and even CPU- and GPU-based platforms capable of running separate operating systems. SmartNICs have gained rapid adoption for data center tasks, including infrastructure management, packet filtering, and I/O acceleration. Increasingly these devices are also being explored for high-performance computing (HPC) and AI application acceleration. This tutorial provides an in-depth exploration of the state of the art in SmartNICs and the emerging software ecosystems that support them. Attendees will participate in hands-on exercises designed to demonstrate how SmartNICs can be leveraged to accelerate HPC and AI applications. Topics include packet processing frameworks such as P4, I/O acceleration techniques, MPI offloading, and algorithmic adaptations for utilizing SmartNIC processors. Participants will have the opportunity to run these exercises on cutting-edge platforms, including NVIDIA BlueField-3 Data Processing Units (DPUs), using cloud-based environments such as USC’s NETLAB and the FABRIC testbed. The tutorial will also highlight additional strategies for optimizing applications to effectively use SmartNICs as communication accelerators in HPC systems.

## Agenda (Tentative)

| Time (CST) | Topic | Details |
| ---------- | ----- | ------- |
| 8:30-8:40 | Introduction | Attendee survey; intro to hands-on activities |
| 8:40-8:55 | Communication Offloading | SmartNIC overview, DPU examples, and DPU programming models |
| 8:55-9:15 | SmartNIC Use Cases | Packet processing, cybersecurity, and AI/HPC |
| 9:15-9:35 | Infrastructure Software – DOCA and P4 Introduction | Brief introduction to DOCA/P4 |
| 9:35-10:00 | Hands-on DOCA/P4 | Attendees follow along in compiling and running test examples |
| **10:00-10:30** | **BREAK** | |
| 10:30-11:00 | HPC Programming – Part 1 | MPI offload; DPA programming |
| 11:00-12:00 | Hands-on with DPA Programming | Additional hands-on with DOCA/P4 |
| *12:00-1:30* | *LUNCH* | |
| 1:30-2:00 | HPC Programming – Part 2 | OpenMP offload |
| 2:00-3:00 | Hands-on HPC Demo – OpenMP/MPI Offload with ODOS | Additional hands-on time with DOCA/P4/DPA |
| **3:00-3:30** | **BREAK** | |
| 3:30-3:40 | Tutorial Survey | |
| 3:40-4:00 | Storage Acceleration | Discussion of use cases for SmartNICs with storage systems for AI |
| 4:00-5:00 | Continued Hands-on Activities | Time to work with the instructors on the presented demos and test cases |

## Hands-on Examples

We have the following examples we will be working through in the tutorial using the FABRIC testbed:

- DOCA examples - from USC Netlab training
- DPA examples - from USC Netlab training
- P4 examples - from USC Netlab training 
- ODOS examples - from BSC

For instructions on how to log in to the cluster and run the examples, please see the [hands-on README](https://github.com/gt-crnch-rg/smartnic-tutorial-sc26/blob/main/hands-on/README.md).

## Slides

Slides will be shared under the [slides] folder the morning of the tutorial!
