Download Link: https://assignmentchef.com/product/solved-ece4550_5550g-project-1
<br>
<span class="kksr-muted">Rate this product</span>

To gain experience in writing and debugging a simulator that implements the most used real-time scheduling algorithms.

1 Logistics

You are to work in a team of 1-2 members. You and your teammate should be able to independently describe the solutions.

2 RM and EDF Simulator

Using your favorite programming language, write a simulator that generates a schedule for the following scheduling algorithms: RM and EDF. Your program should read from an input file, which contains the following information.

• Number of tasks

• Simulation time length

• For each task, the following attributes are specified – ID

– Execution time– Period (with implicit deadline)

To an output file, your program will show the corresponding RM and EDF schedules, clearly indicating when a job is being preempted and when a job misses its deadline. Jobs that miss their deadlines should be dropped at their respective deadlines. The output format of the schedule is up to you but should be easy to understand. At the end of the simulation, your program will also include a summary, indicating the number of preemptions and deadline misses per task and in total.

3 Handling Aperiodic Tasks

Extend your RM simulator to include a deferrable server to handle aperiodic requests. Output the average response time of the aperiodic requests in addition to the original printouts.

4 Implementation of a Real-Time Scheduling Algorithm on an RTOS (Optional + Extra Credits)