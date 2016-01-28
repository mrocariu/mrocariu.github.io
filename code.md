---
layout: page
permalink: /code/
title: Code and Resources
tags: [code]
modified: 3-10-2014
comments: false
---

For my research I develop formulations, some code, and instances. I will share some of them here, so my work is easier to reproduce or in case it can help someone in their research.

## Parking slot Assignment Problem (PAP)

![Parking Slot Assignment Problem](/images/pap.png)

- [Formulation](/files/PAPform.zip) with continuous time (as a VRP). In our [article](http://www.sciencedirect.com/science/article/pii/S0305048315000845) we describe the problem and propose a formulation and 4 different objective functions. Here you can download these formulations.


- [Instances](/files/PAPinst.zip) for PAP. Randomly generated instances based 

- [Separation of SEC](/files/PAPsubtour.zip). Implementation of Subtour Elimination Constraints (SEC) for the PAP formulation as a VRP.

-  [Heuristic](/files/PAPheur.zip). Implementation of an Heuristic to solve the PAP. 


## Shared Customer Collaboration Vehicle Routing Problem (SCC-VRP)

![alt text](/images/sccvrp.png "Shared Customer Collaboration VRP")


- [Instances](/files/SCCinstCordeau.zip) for SCC-VRP, reduced instances from [Cordeau](http://neo.lcc.uma.es/vrp/vrp-instances/multiple-depot-vrp-instances/) for MDVRP 

- [Instances](/files/SCCinst.zip) for SCC-VRP, randomly generated. 


## Urban Consolidation Centers (UCC)
![alt text](/images/ucc.png "Shared Customer Collaboration VRP")

- [Summary](/files/UCCform.pdf) of UCC formulations

- [Compact formulation](/files/UCChom.zip) for UCC

- [Non-homogeneous formulation](/files/UCCnon.zip) for UCC