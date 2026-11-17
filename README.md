# CyberShield
Project Overview: 
CyberShield is a terminal-based C++17 cybersecurity project  where the user acts as the 
Cyber Defense Administrator of a virtual city. The city's network , including a Bank, Hospital, 
University, Government Center and Data Center, is represented as a graph containing 
different servers, databases and PCs. The program simulates incidents like abnormal traffic, 
malware spread and suspicious logins, and the detention system generates alerts. The 
administrator checks each alert and has to make decisions such as isolating a node, adding 
a firewall rule, rate limiting or recovering the affected node.The actions and events are 
recorded, and a final report shows the user’s performance . The project is made only for 
educational purposes. It does not use real network connections or interact with real systems.  
Problem Statement: 
Students often learn Cybersecurity concepts (intrusion detection, firewalls, incident 
response) and C++ concepts (OOP, STL, graph algorithms, file handling) separately. 
Practicing these concepts on real systems can be unsafe or impractical for students. Also, 
theory-based examples do not allow students to see how detection, response and recovery 
work together when there are limited resources. This project provides a safe environment 
where students can see simulated incidents, make defensive decisions and observe the 
results of their actions. It also demonstrates good software design through modular classes, 
OOP, data structures, algorithms and file handling.  
Objectives: 
1. Model a virtual city network using a graph (adjacency list) with different node classes: 
Workstation, Server, DatabaseServer, Router and Firewall.  
2. Simulate incidents step-by-step using events and a seeded random generator so that 
the same seed produces the same session.  
3. Detect anomalies by comparing normal values with current values and give each 
alert a severity level (LOW, MEDIUM, HIGH, CRITICAL). Alerts will be arranged 
using a priority queue.  
4. Allow the administrator to respond to incidents using investigation, isolation, firewall 
rules, rate limiting and recovery while managing a limited security budget. The 
system will then verify whether the response was successful.  
5. Apply graph algorithms such as BFS for infection spread and reachability, DFS for 
finding connected parts of the network, and Dijkstra for finding the lowest-latency and 
propagation paths.  
6. Record system activity and generate reports: Write an audit log (.txt /.csv) and 
generate a final report showing detection rate, containment rate, uptime and 
response efficiency.  
7. Use basic engineering practices such as modular design, input validation, exception 
handling and deterministic testing.  
Input: Seed value,network nodes,incidents,Alert and administration actions.   
Output: Alert details, node status,response results,audit log and final performance 
report. 
Steps to Achieve the objectives:  
1. Create the virtual city network using graph and different node classes. 
2. Generate repeatable security incidents using a seeded random generator. 
3. Detect anomalies and prioritize alerts based on severity. 
4. Investigate incidents and apply isolation, firewall, rate limiting or recovery. 
5. Use BFS, DFS and Dijkstra to analyze network connectivity and paths. 
6. Record activities in TXT/CSV and generate the final performance report. 
Conclusion:  
CyberShield provides a safe environment to learn cybersecurity through a 
simulated network. The project combines C++17, OOP, graph algorithms and 
incident response to detect threats and apply defensive actions. Overall, it 
helps students gain practical knowledge of cybersecurity and software 
development without using any real network system. 
References:  
● C++17 / cppreference 
● GeeksforGeeks – Graph Algorithms 
● NIST Cybersecurity Framework 
● Computer Security: Principles and Practice 
● C++ Standard Template Library (STL) 
