Task 1: Introduction
1. Ensure that you understand why these tools fall under active reconnaissance. Launch your AttackBox and ensure that it is ready. 
You will need it to answer the questions, especially in later tasks.
Answer: No answer needed

Task 2: Web Browser
1.Browse to the following website and ensure that you have opened your Developer Tools on AttackBox Firefox, or the browser on your computer. 
Using the Developer Tools, figure out the total number of questions.
Answer: 8

Task 3: Ping
1.Which option would you use to set the size of the data carried by the ICMP echo request?
Answer: -s
2. What is the size of the ICMP header in bytes? 
Answer:8
3.Does MS Windows Firewall block ping by default? (Y/N) 
Answer:y
4.Deploy the VM for this task and using the AttackBox terminal, issue the command ping -c 10 MACHINE_IP. How many ping replies did you get back?
Answer:10

TAsk 4: Traceroute
1. In Traceroute A, what is the IP address of the last router/hop before reaching tryhackme.com?
Answer:172.67.69.208
2. In Traceroute B, what is the IP address of the last router/hop before reaching tryhackme.com?
Answer:104.26.11.229
3. In Traceroute B, how many routers are between the two systems?
Answer: 26
4.Start the attached VM from Task 3 if it is not already started. On the AttackBox, run traceroute MACHINE_IP. Check how many routers/hops are there between the AttackBox and the target VM. 
Answer: No answer needed

Task 5: Telnet
1. Start the attached VM from Task 3 if it is not already started. On the AttackBox, open the terminal and use the telnet client to connect to the VM on port 80. What is the name of the running server?
Answer: apache
2. What is the version of the running server (on port 80 of the VM)?
Answer: 2.4.10

Task 6: Netcat
1. Start the VM and open the AttackBox. Once the AttackBox loads, use Netcat to connect to the VM port 21. What is the version of the running server?
Answer: 0.17

Task 7: Putting it all together
1. 
Ensure that you gain mastery over the different basic yet essential tools we presented in this room before moving on to more sophisticated tools
Answer: No answer needed
