**Project Description**
Here at Northwestern, as Spring quarter gets underway, it’s easy to get bogged down under piling assignments. That’s why we developed CanvAssist, a dynamic to-do list that takes all of your assignments from Canvas and compiles them into a streamlined, AI-assisted list of assignments. 

Using the Canvas API, CanvAssist is able to take in a user’s profile and create a tiered list of assignments from all of their classes. The tiering is determined by a combination of metrics. These include the due date, a time estimate (generated by ChatGPT or inputted by the user) and the point value. From this a “priority number” is created, which takes into account how soon an assignment is due and how long it will take relative to other assignments, and how much it is worth relative to other assignments in that class through z-scores. Since time estimates are more variable, it is weighted half as much as other metrics. The program then ranks your assignments by this priority number, giving a suggested order in which you should tackle your assignments.

We then pass the assignment description, pulled from the Canvas API, into a formatted prompt for ChatGPT, which produces multiple JSON files. These JSON files include a step-by-step list for tackling the assignment, as well as hyperlinks to potentially useful sources on the web. These are displayed to a user after clicking on an assignment As previously mentioned, it generates a time estimate for how long such an assignment will take. It also returns a streamlined description of the project, with helpful outlines and tips provided to give you a solid grasp of the overall assignment. 

With the help of CanvAssist, students can manage their time more effectively and efficiently, no matter the workload, making both stress and late assignments a thing of the past. 

https://youtu.be/QaQvjapXwRk 

*Technological Notes*
