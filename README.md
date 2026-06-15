# CNRoutingAssignment

## Overview
[cite_start]This repository contains the practical assignment submissions for the **Computer Networks** module at NSBM Green University[cite: 2]. [cite_start]The project demonstrates the configuration of routers, implementation of static routing, and the deployment of dynamic routing protocols (RIP and EIGRP) using Cisco Packet Tracer[cite: 6].

**Author:** Peli Arachchillage Nesandu Nimadith Samararathna  
**Student ID:** [Your Student ID]  
[cite_start]**Module:** Computer Networks [cite: 2]

## Repository Contents
[cite_start]This repository includes three separate Cisco Packet Tracer (`.pkt`) files, each corresponding to the specific tasks outlined in the assignment brief[cite: 106]:

### 1. `Task1_and_Task2_StaticRouting.pkt`
This file contains the implementations for both Task 1 and Task 2.
* [cite_start]**Task 1 (Basic Configuration):** * Configured the router hostname to follow the format `KandyNSBM_[Your Student ID]`[cite: 11, 12].
  * [cite_start]Secured console access by setting the password to `NSBM` and enabling console login authentication[cite: 15, 16].
* [cite_start]**Task 2 (Static Routing):** * Set up a network topology consisting of three routers (ComputingRouter, BusinessRouter, ScienceRouter) and three separate local area networks[cite: 35, 36, 41, 42, 43].
  * [cite_start]Configured IP addressing for all devices[cite: 45].
  * [cite_start]Implemented static routes on all routers to ensure full network connectivity[cite: 46].

### 2. `Task3_PartA_RIP_Routing.pkt`
This file contains the first part of the dynamic routing implementation.
* [cite_start]**Topology:** Three routers (KandyNSBM, ColomboNSBM, GalleNSBM) connecting distinct networks[cite: 71, 72, 73].
* [cite_start]**Protocol:** Configured RIP version 2 routing across all routers to enable dynamic route sharing and full network communication[cite: 77, 78, 79].

### 3. `Task3_PartB_EIGRP_Routing.pkt`
This file contains the second part of the dynamic routing implementation.
* **Topology:** Same three-router setup as Part A.
* [cite_start]**Protocol:** The previous RIP configuration was removed, and EIGRP routing was successfully configured and verified across the network[cite: 80, 81, 82].

## Verification
[cite_start]Full connectivity for all topologies has been verified via ICMP ping tests between the end-user PCs in the different networks[cite: 47, 53, 79, 82, 89]. [cite_start]Detailed screenshots of the configurations, routing tables, and successful ping tests are available in the accompanying Assignment Report PDF[cite: 7, 52, 87, 88].
