# Assignment-2-Network-Models---Project-Management

MSDS 460 Assignment 2 - Garo Bazarbachian

Part 1: 
In Appendix A, I have attached a screenshot of the updated Excel spreadsheet of tasks, completion times, and per-hour costs. Below I have a breakdown of the total hours and average hourly rate to complete this project.
TOTAL (Hours):
Best Case: 135
Expected: 204
Worst Case: 276
Average Hourly Rate: $80
The estimates provided for task durations (best case, expected, worst case) are subject to uncertainty. Actual completion times may vary depending on various factors such as unforeseen technical challenges, changes in project scope, and individual productivity. The hourly rates assumed for each worker role are based on averages and may vary depending on the specific skills and experience of individuals hired for the project. I will need to closely monitor progress and adjust plans accordingly to mitigate any risks or delays.
In Appendix B, I have attached the directed graph diagram for the project which breaks down each task and the predecessor connection of each task. I have also included the code that generated the graph in my repository. 

Part 2: 
The linear programming (LP) model for the project plan specifies the scheduling of activities while considering both time and cost estimates. The model utilizes the critical path analysis technique to identify the sequence of tasks that determine the minimum duration required to complete the entire project. Each activity in the project plan is represented as a decision variable, with its start and end times being optimized to minimize the project's overall duration. Additionally, the LP model incorporates constraints to ensure that activities are completed within the specified best-case, expected, and worst-case duration limits, as well as respecting the dependencies between tasks.
The objective function of the LP model is to minimize the total time spent on tasks, effectively minimizing the project duration. This objective aligns with minimizing total cost under the simplifying assumption that all contributors to the project charge the same hourly rate. By minimizing the total time spent on tasks, the LP model implicitly minimizes the total cost, as the cost is directly proportional to the time spent on each activity. Therefore, the LP model simultaneously considers both time and cost estimates in its optimization process.

Part 3:
I used the PuLP library to implement the linear programming problem. The three scripts for each scenario construct the project plan, define the objective function to minimize project duration and consider task dependencies. Output includes critical path time and total project duration. Results and code are stored in my repository. 

Part 4: 
For the best-case scenario, the critical path comprises tasks starting from "Describe Product" and "Develop Marketing Strategy" and ending at "Write Client Proposal," with a total project duration of 89 days. In the expected scenario, the critical path remains the same, but the durations of individual tasks are adjusted based on expected time estimates. The total project duration in this scenario is 137 days. In the worst-case scenario, the critical path remains unchanged, but the durations of individual tasks are adjusted to reflect the worst-case time estimates. The total project duration in this scenario is 185 days.
In all scenarios, the critical path represents the sequence of tasks that determine the overall project duration. Tasks along this path are crucial and cannot be delayed without affecting the project's completion time. It is important to monitor and manage these critical tasks closely to ensure timely project delivery.
In Appendix C I have included the constructed Gantt chart with the program code that helped create the graph located in the repository. 

Part 5: 
Our project entails developing a comprehensive plan for the creation of a new product, encompassing tasks from conceptualization to prototype delivery. It involves various stages, including product description, marketing strategy formulation, design, implementation, testing, and proposal writing. Ignoring costs related to software licensing and cloud hosting, the project cost primarily revolves around labor expenses. With an average hourly rate of $80 for each worker role, the total project cost can be estimated based on the projected hours. For the best-case scenario, expected, and worst-case scenarios, totaling 135, 204, and 276 hours respectively, the projected costs amount to $10,800, $16,320, and $22,080.
Regarding the delivery timeline, the expected completion time for the product prototype depends on the critical path identified in the project plan. In the best-case scenario, where the project duration spans 89 days, I anticipate delivering the prototype within approximately 3 months from project commencement. In the expected scenario, where the project duration spans 137 days, I expect to deliver the product within an estimated 4.5 months. Lastly, in the worst-case scenario, where the project duration spans 185 days, I expect to deliver the product within an estimated 6 months.  Moreover, the inclusion of additional independent contractors could potentially accelerate the project timeline by increasing workforce efficiency. However, the precise reduction in project duration would hinge on factors such as contractor availability and expertise. If I  expanded on this project and conducted a thorough analysis of resource allocation and task dependencies, I could better gauge the specific impact on the project timeline with additional hands working to create it.

Appendix A















Appendix B






Appendix C



