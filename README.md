# Analytical Investigation of Dynamic Source Routing (DSR) in Mobile Ad Hoc Networks (MANETs)

## Project Overview

This project presents an in-depth analysis of Mobile Ad Hoc Networks (MANETs) employing Dynamic Source Routing (DSR) for efficient packet transfer. Using NetSim version 14, the project simulates the dynamic topology of MANETs and visualizes the DSR protocol's route discovery and maintenance processes.

## Table of Contents

- [Abstract](#abstract)
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Implementation](#implementation)
- [Results and Analysis](#results-and-analysis)
- [Conclusion](#conclusion)
- [References](#references)

## Abstract

This project delves into the intricacies of establishing connections in dynamic environments typical of MANETs, focusing on the DSR protocol's route discovery and maintenance processes. We use NetSim version 14 to simulate scenarios and analyze various performance metrics.

## Introduction

A Mobile Ad Hoc Network (MANET) is an autonomous system of mobile nodes. Information transport services are built over a set of arbitrarily located nodes, which are possibly mobile. The DSR protocol is designed specifically for use in multi-hop wireless ad-hoc networks of mobile nodes.

## Methodology

### Tools & Technology

- **NetSim Version 14**: Used for simulating the MANET.
- **Simulation Configuration**: Scenarios set up with a predetermined number of wireless nodes arranged in a defined area.
- **Protocol Settings**: UDP for Transport Layer and DSR for Network Layer.
- **Path Loss Configuration**: Set to high to simulate realistic conditions.
- **Data Analysis**: Metrics like Application Throughput, Link Throughput, and Packet Trace were analyzed.

### Techniques

- **Simulation-Based Analysis**: Creating a controlled environment for studying the DSR protocol's behavior.
- **Descriptive Statistics**: Analyzing performance metrics.
- **Visualization**: Using packet animation and other tools in NetSim.

## Implementation

### Step-by-Step Implementation

1. **Simulation Setup**: Set up a MANET scenario using NetSim version 14.
2. **Create Scenario**: Define wireless nodes and configure them to run a voice application.
3. **Protocol Configuration**: Set Transport Layer protocol as UDP and Network Layer protocol as DSR.
4. **Path Loss Settings**: Adjust path loss figures to high values.
5. **Enable Packet Trace, Event Trace & Plots**: Set all network logs and additional logs for detailed analysis.
6. **Simulation Execution**: Conduct multiple simulation runs to gather comprehensive data.

## Results and Analysis

### Metrics Tables

- **Application Metrics**: Includes Packets generated/received, throughput, delay, and jitter.
- **Link Metrics**: Includes data/control packets transmitted, errored and collided packets, bytes, payload, and overhead transmitted.

### Packet Trace Visualization

Detailed packet trace files provide insights into packet transmissions, receptions, and routing paths.

## Conclusion

The project successfully visualized the DSR protocol's route discovery and maintenance processes, demonstrating its effectiveness in dynamic MANET environments.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
